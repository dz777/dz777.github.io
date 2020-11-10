## Analysis of the CFPB Consumer Complaints Database

Navajas, D.

Download CFPB Data: http://files.consumerfinance.gov/ccdb/complaints.csv.zip

*The data file is over 1 GB and well above the limit set by GitHub. Please download the csv file from the link above and unzip it.

This project examines and analyzes the complaints database from the Consumer Financial Protection Bureau. The CFPB consumer complaint database was downloaded directly from the CFPB website. In order to re-use the code from this project and run the analysis, download the data from the website link, unzip "complaints.csv.zip" in the same folder as the Jupyter notebook code and then run it. Complaints are published after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first.

The Consumer Complaint Database is a collection of complaints about consumer financial products and services that were sent to companies for response. Complaints are published either after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first.


## Analysis 

### Time series of daily number of complaints.

<img src="images/1timeseries_d_complaints.png">

Over time the number of complaints have increased and we can see very clear spikes and outliers in the beginning and the end of 2017.

### What's up with the spike? 

One day before before the sudden peak, on September 7, 2017, Equifax announced a data breach, stating that hackers had access to the sensitive information of around 143 million Americans. The hackers had access to names, Social Security numbers, birth dates, addresses, driver's license numbers, credit card numbers, and other documents.

<img src="images/2sept8_2017complaints_ratio.png">

After examining the company complaints, the data was as expected, the spike in complaints on September 8, 2017 was largely due to the Equifax data breach. Complaints of Equifax represented around 77% of the complaints on that day, demonstrating that the data breach did lead to a large increase in credit reporting and related issues complaints. 

It is no surprise that, as a result, in 2017, Senators Warren and Schatz introduced the Freedom from Equifax Exploitation [(FREE)](https://www.congress.gov/bill/115th-congress/senate-bill/1816/text?q=%7B%22search%22%3A%5B%22SECURE+Act%22%5D%7D&r=3&s=9) Act to give consumers more control over their financial data and more tools to protect themselves. The FREE Act would require credit reporting agencies to provide customers with stronger fraud alert protections and an additional free credit report. 

Not long after, Senators Warren and Warner introduced the Data Breach Protection Prevention and Compensation Act of [2018](https://www.congress.gov/bill/115th-congress/senate-bill/2289/text?q=%7B%22search%22%3A%5B%22data+breach+notification+law%22%5D%7D&r=12&s=2), which would have passed penalites on companies that failed to adequately protect consumer data and require the FTC to set cybersecurity standards for credit reporting agencies. 

{% include map.html %}



{% include fbar.html %}



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/dz777/dz777.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dz777/dz777.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
