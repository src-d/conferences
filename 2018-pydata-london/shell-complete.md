# Neural Shell Completion: Deep Learning approach to improve your shell

**Updates:** https://github.com/src-d/conferences/issues/18

**Sent on:** 2018/03/01

**Status:** proposed

**Author:** Waren

**Abstract:**

#### Short:
Almost all developers use a terminal and command lines they write follow strong patterns. After gathering a dataset of histories, neural networks can be trained to accelerate your shell scripting by correcting misprints and predicting your next command based on your history. This talk also describes a full deep learning project written in Python from the data collection to the RNN implementation.


#### Long:
This talk follows the architecture of the [shell-complete](https://github.com/src-d/shell-complete) project, detailing the key points:

2. Build the dataset of 10K command line histories
    * Get the list of repositories with the [GitHub REST API](https://developer.github.com/v3/)
    * Scrap the command histories using [scrapy](https://scrapy.org/)
    * standardize contents from **bash/fish/zsh** histories.  
  
2. Process the data and implement specific neural networks that best suit the task
    * Efficient prefix storing in tries with [pygtrie](https://github.com/google/pygtrie)
    * Build the vocabulary of command lines based on **TF-DF** best prefixes
    * For the prediction task, implement a prefix based sequential model using [Keras](https://keras.io/)
    * Incorporate artificial spelling mistakes and train a **charRNN** to autocorrect them

3. Question the user experience in a real shell
    * Current beta version is a **dockerized** service
    * Further thoughts on improving developers' use cases


**Notes:**

I've been working at source{d} for a year, a Madrid based startup that is building tools to allow developers to do machine learning on source code. Last year, I had the chance to be invited to give a talk at PyData Warsaw and loved the experience. My talk was about *Analyzing GitHub, how developers change programming languages over time*, you can take a look at my presentation [here](https://warenlg.github.io/pydata-warsaw-2017/) For this new edition in London, I'd like to talk about my new Python project, shell-complete to improve developers' shell using deep learning NLP techniques.