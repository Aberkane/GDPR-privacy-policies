# Towards Automated GDPR-compliance in Organizations: A Natural Language Processing Based Machine Learning Approach

## Abstract
Recent works show that privacy policies often do not meet the General Data Protection Regulation (GDPR) requirements. To explore the underlying causes of non-compliance, this study leverages machine learning (ML) and natural language processing (NLP) to analyze data processing entities' organizational factors that correlate with GDPR-compliance practices as disclosed in privacy policies. In particular, we have examined the effect of six organizational factors and their subclasses on the disclosure of five GDPR privacy policy core requirements in privacy policies. The contributions of this study are threefold. First, we have developed five NLP-based classification models—achieving a precision of at least 0.909—to assess the GDPR-compliance practices of data processing organizations as divulged in privacy policies. Second, we have collected a data set of 8 614 organizations in the EU, containing organizational information and the GDPR-compliance promises derived from the organization's privacy policy. Lastly, we have analyzed the organizational factors that affect the disclosure of the five GDPR privacy policy core requirements in privacy policies. The analysis revealed, among other things, that being a public company typically positively affects the disclosure of the GDPR privacy policy core requirements. In contrast, the results reveal that being classified as a small and medium-sized enterprise negatively affects the disclosure of two GDPR privacy policy core requirements. Finally, concerning the impact of the location of the data processing entity, the results demonstrate that companies located in Ireland meet most of the GDPR requirements, while companies located in Poland fail to disclose the majority of the considered GDPR requirements.

## Authors
**Abdel-Jaouad Aberkane**, **Seppe vanden Broucke**, and **Geert Poels**<br/>
_Faculty of Economics and Business Administration<br/>
Department of Business Informatics and Operations Management (EB24)<br/>
UGent Business Informatics group_

## Full Journal Article
Currently under review at ACM TOPS.

## Scripts
- Stage 1: [Training Classification Models](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%201%20-%20Classification%20and%20Calibration.ipynb)
- Stage 2: [Scraping](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%202.1%20-%20Privacy%20Policy%20Scraper.ipynb) & [Classification of Scraped Privacy Policies](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%202.2%20-%20Classification%20of%20Scraped%20Privacy%20Policies.ipynb)
- Stage 3: [Analysis](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%203%20-%20Analysis.ipynb)

## Data
- [Data set containing organizational information and GDPR classification (based on privacy policy) of 8 614 organizations in the EU.](https://raw.githubusercontent.com/Aberkane/GDPR-privacy-policies/gh-pages/8614.csv)


<!-- ## Welcome to GitHub Pages
[Link](url)

You can use the [editor on GitHub](https://github.com/Aberkane/GDPR-compliance/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Aberkane/GDPR-compliance/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
 -->
