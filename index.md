# Predicting Application Use to Reduce User Wait Time
Our goal for this project was to lower the user wait time when loading programs by predicting the next used application. In order to obtain the needed data, we created data collection libraries. Using this data, we created a Hidden Markov Model (HMM) and a Long Short-Term Memory (LSTM) model, but the latter proved to be better. Using LSTM, we can predict the application use time and expand this concept to more applications. We created multiple LSTM models with varying results, but ultimately chose a model that we think had potential. We decided on using the model that reported a __% accuracy.

### Problem Statement
App wait time is the amount of time an application needs to be fully loaded. This is depicted as a cursor with a spinning wheel. The longer this cursor status is present, the longer the user must wait for the application to be fully loaded and usable. For example, Google Chrome takes an average of 10 seconds to be fully loaded up. As a result, user experience may be affected by such wait time.

In an effort to reduce app wait time, we collected data on application use and app wait time for a single user over several weeks. With this data we plan to build a series of models to predict which application the user will open with an emphasis on when and for how long. With the series of models, we will evaluate each one and select the one we think is most fitting.

### Data Collection

We built upon Intel® System Usage Report (SUR), which is a framework that will be used to collect our own data for this project. This was designed to track and manage system usage in an accurate and efficient way. Intel SUR can be used to run custom input libraries (IL) to record data as needed. We will be writing custom ILs in order to collect the data that is needed for our task.

Once started, Intel® Energy Checker Energy Server (ESRV) will execute all IL and collect samples every second. If needed, a signal can be sent to collect samples so that data is only recorded as needed. Once terminated, the ESRV will stop running and write all of the data (as specified in the ILs) into a database file. For every instance that the collector is started, a new database file will be created.

### 


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SasamiScott/dsc_capstone/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
