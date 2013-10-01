Open Data DB
=========
A simple "wiki" like way to create a list of companies powered by open data.

##Creating an Entry

1. Add a [new file](https://github.com/opendatadb/opendatadb.github.io/new/master/_posts) in the ```_posts``` directory. 

2. Use the following naming convention:

```
[year-month-day-name-of-company.md]
```

Where the date is the day you added the company. For example:

```
2013-09-30-opower.md
```

3. Create a file that follows this format:

```
---
layout: entry
company: ExampCompany
company-url: http://www.url.com
company-hq: San Francisco, CA
company-country: United States
company-type: Public
company-founded: 2010
company-employees: 200
company-description: ExampCompany is awesome is a positive place to find encouragement for your healthy activities and insights into your healthy routines.

categories:
- federal 
- state

tags:
- wellness
- consumer
- employer

dataset: Name of dataset goes here
dataset-url: http://hhs.gov
dataset-use: We use the dataset to do X.

---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed placerat id mi sed congue. [Long description of company and its open data practices go here.]

```

When you save the file, the company will be added.
