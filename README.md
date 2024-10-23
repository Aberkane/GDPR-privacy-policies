# Factors related to GDPR compliance promises in privacy policies: a machine learning and NLP approach

## Abstract
This paper employs machine learning (ML) and natural language processing (NLP) techniques to examine the relationship between organizational factors, such as company size and headquarters location, of data processing entities and their GDPR compliance promises as disclosed in privacy policies. Our methodology comprises three main stages, each representing a key contribution. Firstly, we developed five NLP-based classification models with precision scores of at least 0.908 to assess different GDPR compliance promises in privacy policies. Secondly, we have collected a data set of 8,614 organizations in the EU containing organizational information and the GDPR compliance promises derived from the organization’s privacy policy. Lastly, we have analyzed the organizational factors correlating to these GDPR compliance promises. The findings reveal, among other things, that small or medium-sized enterprises negatively correlate with the disclosure of two GDPR privacy policy core requirements. Moreover, as a headquarters location, Denmark performs best regarding positively correlating with disclosing GDPR privacy policy core requirements, whereas Spain, Italy, and Slovenia negatively correlate with multiple requirements. This study contributes to the novel field of GDPR compliance, offering valuable insights for policymakers and practitioners to enhance data protection practices and mitigate non-compliance risks.

**Keywords** - general data protection regulation; data protection; privacy policy; natural language processing; machine learning. <br/>



## Authors
**Author(s) Blinded**<br/>

## Full Journal Article
Currently under review at the International Journal of Information Systems and Project Management (IJISPM)

## Scripts
- Stage 1: [Training Classification Models](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%201%20-%20Classification%20and%20Calibration.ipynb)
- Stage 2: [Scraping](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%202.1%20-%20Privacy%20Policy%20Scraper.ipynb) & [Classification of Scraped Privacy Policies](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%202.2%20-%20Classification%20of%20Scraped%20Privacy%20Policies.ipynb)
- Stage 3: [Analysis](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%203%20-%20Analysis.ipynb)
    - Output: [Statsmodels output](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Statsmodels%20output.txt)

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
