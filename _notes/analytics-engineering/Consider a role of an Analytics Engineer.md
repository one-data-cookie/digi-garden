---
title: Consider a role of an Analytics Engineer
title-cs: Pojmenoval bych se jako Analytics Engineer
category: analytics-engineering
tags: [idea]
season: autumn
dates: [17 Dec 2020, 22 Feb 2021]
sources: Misc
---

Three roles in one:
![](/assets/src/three-data-roles.png)

---

> These are only possible through the one-two punch of deep business context and technical excellence.

To se dá samozřejmě napasovat na ledacos, ale u Analytics je to podle mě stěžejní, aby to člověk měl v dobré rovnováze.

> "Analytics Engineers"

To se mi velmi líbí, i v návaznosti na ten předchozí bod. Řekl bych, že to mnohem víc vystihuje, jak technická ta role často je. "Data Analyst" spíš evokuje výhradně analyzování, ale my -- troufám si říct -- docela dost i tvoříme. Nepotřebuju ke své práci nutně nálepku, ale tahle mi přijde asi nejvhodnější, co jsem se zatím setkal. Navíc totiž -- jak se tam zmiňuje -- je to dostatečně obecný na to, aby to nesvazovalo a člověk si v tom mohl najít to svoje.

> The Analyst, The Engineer, The Visualizer

U nás nejsme tak specializování, spíš jsme každej na nějaké škále pro všechny tři, ale tu práci to pěkně shrnuje do tří person, přičemž každou používáme ve správnej čas podle potřeby.

![Analyst, Engineer, Visualiser](https://miro.medium.com/max/2720/1*Pm_2Ai349Qh0W-caNQ9agQ.png)

> Since the problem space is so varied, we align our analytics professionals with the listed business area verticals rather than organizing them within a single functional horizontal. The expectation is that individuals in these roles possess deep business context and are thought leaders alongside their business counterparts. This enables them to fully understand where their partners are coming from. It also means Analytics and Visualization Engineers are a specialized resource and a rare commodity. There are many more questions and stakeholders than analytics team members, and the job is not to take on every request. Instead, these individual contributors are given freedom to choose their projects and are responsible for prioritizing the ones that will have the most business impact (and deprioritizing the rest). This requires a lot of judgment and embodies our "context not control" culture.

Jen tak na okraj -- tento odstavec pěkně popisuje i náš způsob uvažování nad umístěním té role v rámci hierarchie. Určitě ještě nejsme tak daleko, ale snažíme se to tam směřovat, řekl bych.

-- [Source](https://netflixtechblog.com/analytics-at-netflix-who-we-are-and-what-we-do-7d9c08fe6965)

---

Analytics engineers deliver well-defined, transformed, tested, documented, and code-reviewed data sets. Because of the high quality of this data and the associated documentation, business users are able to use BI tools to do their own analysis while getting reliable, consistent answers.

Analytics engineers are like librarians. They curate the catalog so that the researchers can do their work more effectively.

- Is it possible to build a single table that allows us to answer this entire set of business questions?
- What is clearest possible naming convention for tables in our warehouse?
- What if I could be notified of a problem in the data before a business user finds a broken chart in Looker?
- What do analysts or other business users need to understand about this table to be able to quickly use it?
- How can I improve the quality of my data as its produced, rather than cleaning it downstream?

As data tools changed, so did the people who used them. People who weren't on data teams began developing data literacy. This was good: business users wanted to self-serve and be data-driven. The downside was that these people often knew just enough SQL to be dangerous. If you've ever been to a meeting where two executives have different numbers for the same metric, you've experienced the result of this.

-- [Source](https://blog.getdbt.com/what-is-an-analytics-engineer/)

---

He wasn't interested in laying the foundation for an analytics function that scaled with more people, he wanted to build an analytics function that scaled with code.

So instead of churning out monthly Excel reports, Sagar's job is now to:

* Extract data from front-end tools and load it into Snowflake using an automated data pipeline tool. He chose Stitch.
* Transform data using dbt to write SQL transformations within the data warehouse.
* Deliver clean, tested, and ready-to-use data to Looker for analysis.
* Analyze data and provide insights and recommendations across the organization.

- Manage requests
- Maintain a tidy dbt project
- Test data
- Educate others

-- [Source](https://blog.getdbt.com/the-four-priorities-of-an-analytics-team-of-one-lessons-from-lola-com/)

--- 
They have more engineering skills than your average analyst and are more curious to solve analytical business questions than your average data engineer.

An analytics engineer is a technical analyst that applies software engineering best practices to the production and maintenance of analytics code. The analytics engineering workflow cleans and transforms raw data into consumable information and business logic. In the process, the analytics engineering workflow tests data to ensure it is of high quality, documents all business logic, and ensures data models are running reliably in a production environment.

For modern data teams, the ideal setup is for analysts, who have a much better understanding of the business logic that goes into data transformation, to own most or all of the transformation process. (ETL vs ELT)

They'll likely write better SQL than either your data analysts or your data engineers.

SQL is the key here as the whole analytics engineering is built upon it.

-- [Source](https://blog.getdbt.com/hiring-analytics-engineer/)
