## How data can help us understand vacancy and demolition?
### Baltimore Data Day

Eli Pousson and Johns Hopkins, [Baltimore Heritage](http://baltimoreheritage.org/)

2016 July 22

---

# Introduction

Note:

--

## Who is Baltimore Heritage?

Note:

Founded in 1960, Baltimore Heritage, Inc. is Baltimore’s nonprofit historic and architectural preservation organization. With two staff members, 33 volunteer board members, and a host of volunteers, we work to preserve and promote Baltimore’s historic buildings and neighborhoods.

--

## We use data for preservation advocacy

- How do we use data to support preservation advocacy on vacant housing?
- What tools and resources do we use to work with data?

--

## We use data to talk about vacancy, demolition, and Project CORE

- How are we using data in our work on Project CORE?
- How can other nonprofits and advocacy groups use data to investigate housing and community development issues?

---

## How do we use data to support preservation advocacy on vacant housing?

![2023-2027 Herbert Street. Courtesy Maryland Department of Housing and Community Development](http://baltimoreheritage.org/wp-content/uploads/2016/04/2023-2027-Herbert-St-Project-CORE-768x512.jpg)

<span class="caption">2023-2027 Herbert Street. Courtesy Maryland Department of Housing and Community Development</span>

Note:

How data can assist in preservation advocacy efforts?

- **at the "big picture" level**: what is happening? where is it happening? do we care about this? why do we care about this? how can we explain our concerns to our board, members, supporters, and partners?
- **at the building and block level**: where are the opportunities for advocacy? do we have specific concerns we need to address in the advocacy process?

--

## We needed to know more about vacancy and demolition

- How can we promote alternatives to demolition if we don't know where demolition is taking place?
- How can we argue for the feasibility of building reuse if we don't know where market conditions make reuse difficult?
- How can we encourage residents to participate in the review of demolition projects when information about projects is confusing or difficult to access?

**We can't.**

--

## We are learning more by asking questions

- What neighborhoods are most affected by vacancy and demolition?
- What vacant buildings are most likely to be selected for demolition?
- Where are the opportunities for Baltimore City or private developers to invest in stabilization, preservation, and reuse?

---

## What tools and resources do we use to work with data?

Note:

How do we approach working with data on vacancy and demolition?

- **Free tools**: QGIS, Carto (formerly CartoDB) with a free nonprofit account, Google Sheets, Socrata
- **Show our work**: Publishing blog posts, Facebook group posts, asking for feedback, questions, comments

--

## Free tools

- [CARTO](https://carto.com/)
- [QGIS](http://qgis.org/)
- [Google Sheets](https://www.google.com/sheets/about/)

Note:

As a small nonprofit, we don't have a big budget for outside consultants or expensive software. Instead, we try to use free and open-source tools.

CARTO is a web-based platform for geographical data visualization and analysis. They offer a basic free plan to everyone and a [20% discount for students and nonprofits](https://carto.com/pricing/#discount).

QGIS is a free and open-source Geographic Information System desktop application. It may not be as pretty as ArcGIS but there is a lot of useful [documentation available online](http://qgis.org/en/docs/index.html).

We connect those two applications together using [a free plugin](https://github.com/gkudos/qgis-cartodb) that makes it easy to move data from QGIS to CARTO and back again. CARTO can also [work with ArcGIS](https://carto.com/blog/esri-and-cartodb-together/) for any planners or professional who use that application.

We also use Google Sheets, a free spreadsheet application included with Google Drive, to do both basic data analysis and to sync data from the Baltimore Open Data platform to CARTO.

For more on how we import data from Socrata into Google Sheets and sync Google Sheets with CARTO, see ["How to create a property information system for your neighborhood"](http://elipousson.github.io/data/2016/06/06/property-information-system-neighborhood/) by Eli Pousson.

--

## Show our work

- Baltimore Heritage account on Open Baltimore
- Posting on Baltimore's New Old House Forum and Bmore Historic
- Making data available with Google Sheets and GitHub

Note:

We also think it is important to show our work and clearly document our process so any interested stakeholders can see how we conducted our analysis.

To achieve this goal, we have been regularly sharing the data, maps, and visualizations we have created over the past six months through online communities related to housing and historic preservation in Baltimore. By sharing our work, we have been able to get immediate feedback from residents and partners to help shape our approach and presentation.

We also want to be transparent about data sources and share any data we get in formats that people can use. We are already using Google Sheets to do this and experimenting with using GitHub.

--


## Where did we get our data?

- We used open data from Baltimore City and the State of Maryland
- We had to ask for data (not just PDFs)
- We had to be persistent

TK: Image of Socrata Open Baltimore Data Portal

Note:

Add links and screenshots as appropriate.

---

## How did we approach our analysis?

- **Place**: Distribution, proximity
- **Time**: Trends, patterns, etc.

--

## Place

Note:

- Geographic distribution within:
	- neighborhoods
	- historic districts
	- market typology

--

## Time

Note:

- Patterns of change over time:
	- demolition permits
	- historic tax credits

---

## What did we learn from our data analysis?

Note:

- Our work is primarily description, about making it easier for us and others to understand and make connections.

Explain how we did the analysis:

- Google Sheets
- QGIS (w/ CartoDB connector)

Explain how we visualized the analysis:

- Google Charts (boo!)
- Google Sheets (yay?)
- Chartbuilder (yay?)
- CartoDB (yay!!)

--

TK: Charts on vacants in historic districts

Note:

- What proportion of vacants are in NR districts? Local districts?
- What proportion of distressed vacants are in NR districts? Local districts?

--

### Where are vacant buildings and historic districts?

<iframe width="100%" height="520" frameborder="0" src="https://baltimoreheritage.carto.com/viz/c1c5b24a-d032-11e5-9637-0e5db1731f59/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Map: [Vacant Building Notices and Historic Districts](https://baltimoreheritage.carto.com/viz/c1c5b24a-d032-11e5-9637-0e5db1731f59/public_map) (this map needs work)

Google Sheet: [Vacant Buildings - Historic Districts - Baltimore City](https://docs.google.com/spreadsheets/d/1fR7B9fbAblGgZVfb6_GFXeincgPruYjb5bWp811xLxs/edit?usp=sharing) (this data may show different things than the map)

--

### Where are we tearing buildings down?

<iframe width="100%" height="520" frameborder="0" src="https://baltimoreheritage.carto.com/viz/343fb512-0014-11e6-a407-0ecfd53eb7d3/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Map: [Demolition Permits in Baltimore City: 2015-2016](https://baltimoreheritage.carto.com/viz/343fb512-0014-11e6-a407-0ecfd53eb7d3/public_map)

Google Sheet: [Baltimore City Demolition Permits - Data Dashboard](https://docs.google.com/spreadsheets/d/1fNvFRqc6AqL-Fy-jXyerqzBIfzWRCbHDJg6qAchywdE/edit?usp=sharing)

--

## Where do market conditions discourage reuse and rehabilitation in historic districts?

<iframe width="100%" height="520" frameborder="0" src="https://elipousson.carto.com/viz/cacbb1ba-1b63-11e6-b4fd-0ecfd53eb7d3/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

This map was created using QGIS and the CartoDB uploader. It is currently hosted on my personal elipousson CARTO account.

Map: [Vacant Buildings in Stressed Markets and Historic Districts](https://elipousson.carto.com/viz/cacbb1ba-1b63-11e6-b4fd-0ecfd53eb7d3/public_map)

--

### Where are property owners neglecting their buildings?

<iframe width="100%" height="520" frameborder="0" src="https://baltimoreheritage.carto.com/viz/b7346d6a-0018-11e6-ad61-0e8c56e2ffdb/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Map: [Failed to Abate Unsafe Structure Open Citations: 2016](https://baltimoreheritage.carto.com/viz/b7346d6a-0018-11e6-ad61-0e8c56e2ffdb/public_map)

Google Sheet: [Failed to Abate Unsafe Structure - Data Dashboard](https://docs.google.com/spreadsheets/d/1iM2QJwN1LUZ9LzP5lMxSp3VR2XjibF2wtoN8ldY9re8/edit?usp=sharing)

--

### Where are property owners investing in rehabilitation?

Map: TK

Note:

Map: TK

Google Sheet: [Baltimore City Historic Property Tax Credit Program - Data (2003-2016)](https://docs.google.com/spreadsheets/d/1qh7NV7WyU8TxS0XLx0a3QvRYDSIfYHpXAFac7ttlJjE/edit?usp=sharing)

--

### Where are property owners investing in vacant buildings?

<iframe width="100%" height="520" frameborder="0" src="https://elipousson.carto.com/viz/88fd2156-1b0e-11e6-9627-0e674067d321/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Map: [Where are permits being issued for vacant buildings in 2016? ](https://elipousson.carto.com/viz/88fd2156-1b0e-11e6-9627-0e674067d321/public_map) (This is currently hosted on my personal elipousson CARTO account.)

Google Sheet: [Housing Permits for Vacant Buildings (2016)](https://docs.google.com/spreadsheets/d/10LpagmZana6lxO0aVemoDfrPjXPvTdLdTCPr9It09Jo/edit?usp=sharing)

--

## Where is Project CORE tearing down buildings?

<iframe width="100%" height="520" frameborder="0" src="https://baltimoreheritage.carto.com/viz/68692646-0057-11e6-acec-0e3ff518bd15/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Related Blog post:

Map: [CORE FY2016 Property List (Draft)](https://baltimoreheritage.carto.com/viz/68692646-0057-11e6-acec-0e3ff518bd15/public_map) (filtered to just show the demolition "T" clusters)

Google Sheet: [CORE FY16 Property List (Redacted Draft)](https://docs.google.com/spreadsheets/d/14XhBjhaOR-9d1N1XGf-haJkYflohKR1OXmOQEAKtRi8/edit?usp=sharing)

--

## Is Project CORE tearing down buildings in historic districts?

<iframe src="https://docs.google.com/spreadsheets/d/14XhBjhaOR-9d1N1XGf-haJkYflohKR1OXmOQEAKtRi8/pubchart?oid=1321192114&amp;format=interactive"></iframe>

Note:

Chart via [CORE FY16 Property List (Redacted Draft)](https://docs.google.com/spreadsheets/d/14XhBjhaOR-9d1N1XGf-haJkYflohKR1OXmOQEAKtRi8/edit?usp=sharing)

---

### What do we get out of using data in our advocacy?

- **More effective advocacy**: Fight where our help is needed and wanted. Fight for what matters. Fight where we can actually make a difference.
- **Greater resident participation**: Use data to help make the process more accessible and engaging to residents (both people who support preservation and those who want to see more demolition)

--

## More effective advocacy

--

## Helping people to participate

Note:

Our goal with a new Preservation Maryland funded project through the Community Law Center is to develop a workshop and toolkit for community groups in historic districts to ...

---

## How data can help us understand vacancy and demolition?
### Baltimore Data Day

Eli Pousson and Johns Hopkins, [Baltimore Heritage](http://baltimoreheritage.org/) | 2016 July 22

Note:

Additional questions:

- What is the proportion of land use in Baltimore historic districts? How does that compare to the city as a whole?
- What is the timeline for Baltimore's historic district designations?
