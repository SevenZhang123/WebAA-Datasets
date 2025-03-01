***Welcome to our datasets!***

Those datasets can be used for website association and other related tasks. For more information, please refer to the paper: 
""WebAA: Website Association Analysis via Multi-Resource Similarity""

There are two datasets here: Legal dataset and Illegal dataset.


# Legal dataset
All the websites in the legal dataset are normal websites.

The Legal dataset folder includes two txt files, namely "chinaz.txt" and "available_webistes.txt".

1. chinaz.txt: All websites crawled from the chinaz website ranking system, each column is a website.

2. available_webistes.txt: Available websites retained after filtering all websites in chinaz.txt. Each column represents each website and its organizational information and resource information. The format is as follows:
    website \t registration number , {external resources} , HTMLText's embedding vector
Note: The spaces in the above format are only used to separate each part, and there is no space in the actual file.


# Illegal dataset
All the websites in the illegal dataset are black and gray industry websites, for example gambling websites, porn websites.

The illegal dataset folder includes two txt files, namely "IDtracker.txt" and "available_webistes.txt".

1. IDtracker.txt: This is a dataset of black and gray industry websites that we collected from the paper-IDtracker. The author has performed organization-level aggregation based on the analysis ID, and each column represents an organization and its websites. The format is as follows:
    analysis ID , {the websites corresponding to this ID}

2. available_webistes.txt: Available websites retained after filtering all websites in IDtracker.txt. Each column represents each website and its organizational information and resource information. The format is as follows:
    website \t registration number , {external resources} , HTMLText's embedding vector


***We will update and maintain the dataset in real time, hoping that it can help community researchers in their research in related fields!***