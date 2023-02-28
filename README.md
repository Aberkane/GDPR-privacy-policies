# An Analysis of Organizational Factors and their Relation with GDPR-Compliance: A Natural Language Processing Based Machine Learning Approach

## Abstract
**Purpose** - This study aims to explore the underlying causes of General Data Protection Regulation (GDPR) non-compliance by utilizing machine learning (ML) and natural language processing (NLP) to assess the correlation between organizational factors of data processing entities and their GDPR-compliant practices as disclosed in privacy policies.<br/>
**Design/methodology/approach** - The research approach was threefold. First, we have developed five NLP-based classification models—achieving a precision of at least 0.908—to assess the GDPR-compliance practices of data processing organizations as divulged in privacy policies. Second, we have collected a data set of 8614 organizations in the EU containing organizational information and the GDPR-compliance promises derived from the organization's privacy policy. Lastly, we have analyzed the organizational factors that correlate with the disclosure of five GDPR privacy policy core requirements in privacy policies.<br/>
**Findings** - The findings reveal, among other things, that small or medium-sized enterprises negatively correlate with the disclosure of GDPR privacy policy core requirements. Moreover, as a headquarters location, Denmark performs best regarding positively correlating with disclosing GDPR requirements. On the other hand, Spain, Italy, and Slovenia show a negative correlation with disclosing multiple GDPR requirements.<br/>
**Originality** - This study adds to the novel field of GDPR-compliance in practice and presents new insights into the challenge of GDPR-compliance. Our contributions can be a stepping stone for academics and professionals involved in developing targeted solutions to address the problem of non-compliance.<br/>

**Paper type** - Research paper <br/>
**Keywords** - General Data Protection Regulation, Data Protection, Privacy, Privacy Policy, Natural Language Processing, Machine Learning <br/>



## Authors
**Abdel-Jaouad Aberkane**, **Seppe vanden Broucke**, and **Geert Poels**<br/>
_Faculty of Economics and Business Administration<br/>
Department of Business Informatics and Operations Management (EB24)<br/>
UGent Business Informatics group_

## Full Journal Article
Currently under review at the Digital Policy, Regulation and Governance journal.

## Scripts
- Stage 1: [Training Classification Models](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%201%20-%20Classification%20and%20Calibration.ipynb)
- Stage 2: [Scraping](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%202.1%20-%20Privacy%20Policy%20Scraper.ipynb) & [Classification of Scraped Privacy Policies](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%202.2%20-%20Classification%20of%20Scraped%20Privacy%20Policies.ipynb)
- Stage 3: [Analysis](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%203%20-%20Analysis.ipynb)
 - Output: [Statsmodels output]([https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Stage%203%20-%20Analysis.ipynb](https://github.com/Aberkane/GDPR-privacy-policies/blob/gh-pages/Statsmodels%20output.txt))

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
