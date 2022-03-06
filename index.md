## Predicting Application Use to Reduce User Wait Time

Our goal for this project was to lower the user wait time when loading programs by predicting the next used application. In order to obtain the needed data, we created data collection libraries. Using this data, we created a Hidden Markov Model (HMM) and a Long Short-Term Memory (LSTM) model, but the latter proved to be better. Using LSTM, we can predict the application use time and expand this concept to more applications. We created multiple LSTM models with varying results, but ultimately chose a model that we think had potential. We decided on using the model that reported a __% accuracy.

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
