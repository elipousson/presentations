## How can data and mapping help us understand vacancy and demolition?
### Baltimore Data Day

[Baltimore Heritage](http://baltimoreheritage.org/) |
2016 July 22

Eli Pousson and Johns Hopkins

---

![This Place Matters: Baltimore's Hebrew Orphan Asylum, September 8, 2010, Baltimore Heritage](https://c1.staticflickr.com/5/4113/4970821797_a07fa05333_b.jpg)

Note:

Who is Baltimore Heritage?

Founded in 1960, Baltimore Heritage is a nonprofit organization dedicated to preserving and promoting Baltimore's historic  building and neighborhoods.

With two staff members, 33 volunteer board members, and a host of volunteers, we lead tours, help homeowners, teach workshops, and more.

This presentation was put together by Eli Pousson, our Director of Preservation and Advocacy.

---

![Data + Heritage (Graphic)](/presentations/images/2016-07-14-data-heritage.png)

Note:

Over the past few months, we've been experimenting with using data and maps to support our work on historic preservation advocacy.

Most of our advocacy is focused on individual landmarks threatened with demolition or neglect. Our recent work with on data and mapping is focused on Baltimore's 16,000 vacant houses.

It is not easy to understand the complex issues around a single distressed historic building. Understanding the issues around 16,000 distressed historic buildings may be impossible. But we can't hope to promote the preservation and reuse of vacant buildings if we don't know more about them.

---

![2023-2027 Herbert Street. Courtesy Maryland Department of Housing and Community Development](http://baltimoreheritage.org/wp-content/uploads/2016/04/2023-2027-Herbert-St-Project-CORE-768x512.jpg)

Note:

- How can we promote alternatives to demolition if we don't know where demolition is taking place?
- How can we encourage residents to participate in the review of demolition projects when information about projects is confusing or difficult to access?
- How can we argue for the feasibility of building reuse if we don't know where market conditions make reuse difficult?

**We can't.**

---

![3208-3210 Elgin Avenue. Courtesy Maryland Department of Housing and Community Development.](http://baltimoreheritage.org/wp-content/uploads/2016/04/3208-3210-Elgin-Ave-Project-CORE-768x511.jpg)

Note:

Over the past few years, we have worked to  promote the reuse and preservation of vacant housing through new historic district designations and community organizing in several West Baltimore neighborhoods.  More recently, we have participated in the review of proposed strategic demolition projects through the Section 106 review process administered by the Maryland Historical Trust.

Data empowers us to take a more proactive approach to advocacy on vacant housing. We are using maps and data analysis to support our understanding of vacant housing and demolition in two ways:

1. **We need to see the "big picture"**:
	- How many vacant houses does Baltimore hold? Where they are located?
	- How many vacant houses are there in historic districts?
	- How can we explain the issues of vacant housing and demolition to our board, our members and our supporters?
2. **We need to take a close look at buildings and blocks**:
	- Where can we make a difference in the preservation and reuse of these buildings?  Where can residents make a difference?
	- How do we set our priorities with so many buildings that need attention and investment?

Today, we'll talk about:

- How we use data to support preservation advocacy on vacant housing;
- What tools and resources we use to work with data.
- What we are learning from our work with data so far.

---

Note:

Here is some of what we need to know:

- What neighborhoods are most affected by vacancy and demolition?
- What vacant buildings are most likely to be selected for demolition?
- Where are the opportunities for Baltimore City or private developers to invest in stabilization, preservation, and reuse?

---

Note:

This presentation is based on the past six months of experimenting and learning how we can incorporate data and mapping into our advocacy and outreach efforts. We are focused on how we can use these tools to inform and empower community residents in historic neighborhoods.

- How are we using data in our work on Project CORE?
- How can other nonprofits and advocacy groups use data to investigate housing and community development issues?

---

Note:

How do we use data to support preservation advocacy on vacant housing?

We want an early warning system. How can we know when properties are at-risk? How can we help inform neighborhoods about at-risk properties and support their work to promote preservation and reuse?

---

## Getting started

- Where can you find data?
- What tools can you use to work with data?
- How can you learn from working with data?

Note:

When thinking about our work it is important to remember that we are a tiny nonprofit. We don't have a big budget for consultants or for expensive software. Instead, we try to use free or cheap tools whenever we can.

We are not experts on data analysis. We are doing the best we can to figure it out as we go along.

With that in mind, we want to give you our take on three important questions:

1. Where can you find **data** related to vacant housing?
2. What **tools** can you use to work with the data?
3. What can you **learn** from looking at the data?

---

## Where are we finding data?

--

![Watercolor style map of Baltimore](/presentations/images/2016-07-14-watercolor-baltimore.jpg)

Note:

Most of the data we are using, you can find for free online from Baltimore City and the State of Maryland.

In a few cases, for data on Project CORE's 2016 demolition clusters or data on Baltimore's historic tax credit program, we had to contact city and state staff to ask for it. You may need to explain why you need a spreadsheet instead of a PDF file so you can do more than just print it out or read it on your computer.

--

![Open Baltimore (Screenshot)](/presentations/images/2016-07-14-open-baltimore.png)

Note:

[Open Baltimore](https://data.baltimorecity.gov/) provides a number of useful data sets for anyone trying to understand housing and development issues in Baltimore including:

- vacant building notices
- citations for code violations
- 311 service requests for vacant buildings
- housing permits for work on vacant houses
- and the Baltimore Housing Market Typology (just to name a few).

Using data from Open Baltimore presented real challenges. We've found data sets that are out of date, incomplete, and missing essential information. For example:

- Data on [Housing Citations](https://data.baltimorecity.gov/Housing-Development/Housing-Citations/pugq-wdem) from the Environmental Control Board lists the address for each violation but no coordinates. To use this data, we needed to geocode hundreds of addresses using a [Batch Geocoding service](http://www.findlatitudeandlongitude.com/batch-geocode/)
- Data on Vacant Building Notices from Baltimore Housing combines latitude and longitude into a single field and wraps them in parentheses. This small quirk of formatting makes it impossible to directly import the VBN data into most web mapping tools without splitting up the combined field.

--

![Maryland iMap: Maryland's Mapping & GIS Data Portal (Screenshot)](/presentations/images/2016-07-14-MD-iMAP.png)

Note:

We also used:

- [Maryland iMap: Maryland's Mapping & GIS Data Portal](http://data.imap.maryland.gov/) to find data on National Register designated historic districts and the Maryland Inventory of Historic Properties.
- [Baltimore Neighborhood Indicators Alliance](http://bniajfi.org/) for additional data and analysis on housing and vacancy in Baltimore.

---

## What tools are we using?

--

![Mapping Data By Five by Five, FR, The Noun Project](/presentations/images/noun_38253-900.png)

Note:

What tools can you use to work with data?

Once we collected our data, we used three free tools to do some analysis, make maps, and create visualizations:

- [Google Sheets](https://www.google.com/sheets/about/)
- [CARTO](https://carto.com/)
- [QGIS](http://qgis.org/)

--

![Google Sheets (Screenshot)](/presentations/images/2016-07-14-google-sheets-example.png)

Note:

We started with Google Sheets, a free spreadsheet application included with Google Drive, to make some simple charts and import our data from Open Baltimore into CARTO.

--

![CARTO (Screenshot)](/presentations/images/2016-07-14-carto-example.png)

Note:

CARTO is a web-based platform for geographical data visualization and analysis. They offer a basic free plan to everyone and a [20% discount for students and nonprofits](https://carto.com/pricing/#discount).

--

![QGIS (Screenshot)](/presentations/images/2016-07-14-qgis-example.png)

Note:

We wanted to do a few things that we couldn't accomplish with these two tools so we added one more.

[QGIS](http://qgis.org/) is a free and open-source Geographic Information System desktop application. It is a more complex and difficult tool than CARTO but there is a lot of useful [documentation available online](http://qgis.org/en/docs/index.html).

We can easily move our data from QGIS to CARTO using [a free plugin](https://github.com/gkudos/qgis-cartodb) that syncs GIS data from one program to the other. CARTO can also [work with ArcGIS](https://carto.com/blog/esri-and-cartodb-together/) for any planners or professional who use that application.

<!-- For more on how we import data from Socrata into Google Sheets and sync Google Sheets with CARTO, see ["How to create a property information system for your neighborhood"](http://elipousson.github.io/data/2016/06/06/property-information-system-neighborhood/) by Eli Pousson. !-->

---

Note:

One advantage of Google Sheets and CARTO is that they help us to **show our work**.  Both tools make it easy to share data and maps online, where we can look to residents, members, and partners for questions or comments.

One of the most exciting aspects of these tools is the opportunity to make complicated issues easier for people to understand. So far we have focused on creating descriptive visuals that we are using to get a better understand of the landscape of housing issues in historic neighborhoods.

Over the past few months, we have shared these new resources on social media and incorporated them into our communications with our members and supporters. By sharing our work, we have been able to get immediate feedback from residents and partners to help shape our approach and presentation.

We've also tried to make it easy to follow how we created these resources by making our data available online and by writing tutorials for neighborhood groups to follow our approach.

---

## What are we learning?

Note:

Our work is primarily description, about making it easier for us and others to understand and make connections.

--

<iframe width="960" height="700" frameborder="0" scrolling="no" src="https://plot.ly/~baltimoreheritage/3.embed"></iframe>

Note:

There are 16,638 vacant building notices in Baltimore City. 7,018 of those buildings, over 40% of the total, are located in historic districts listed on the National Register of Historic Places. 4,878 of that number (about 70%) are located in area's described by Baltimore Housing Market Typology as stressed.

Chart: https://plot.ly/~baltimoreheritage/1/

--

<iframe width="960" height="700" class="full-screen" frameborder="0" src="https://baltimoreheritage.carto.com/viz/c1c5b24a-d032-11e5-9637-0e5db1731f59/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Where are vacant buildings and historic districts?

The scale of vacant housing in historic districts varies. Eleven of the city’s 58 residential National Register designated historic districts have over 100 VBNs and two have over 1,000 VBNs: the Old West Baltimore Historic District with 2038 and Baltimore East/South Clifton Park Historic District with 1790.

Looking closer we've found that in:

- Reservoir Hill Historic District, 123 of 1557 buildings are vacant (7.9%)
- Upton’s Marble Hill Historic District, 48 of 348 buildings are vacant (13.8%)
- Union Square-Hollins Market Historic District, 239 of 1305 buildings are vacant (18.31%)
- Franklin Square Historic District, 338 of 1192 buildings are vacant (28.36%)

Map: [Vacant Building Notices and Historic Districts](https://baltimoreheritage.carto.com/viz/c1c5b24a-d032-11e5-9637-0e5db1731f59/public_map) (this map needs work)

Google Sheet: [Vacant Buildings - Historic Districts - Baltimore City](https://docs.google.com/spreadsheets/d/1fR7B9fbAblGgZVfb6_GFXeincgPruYjb5bWp811xLxs/edit?usp=sharing) (this data may show different things than the map)

--

<iframe width="960" height="700" frameborder="0" src="https://elipousson.carto.com/viz/cacbb1ba-1b63-11e6-b4fd-0ecfd53eb7d3/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Where do market conditions discourage reuse and rehabilitation in historic districts?

Vacant buildings on stressed market blocks present the greatest challenge for preservation and for anyone who cares about housing and community development in Baltimore. The significant number of vacant properties in historically black neighborhoods like Upton’s Marble Hill is no coincidence. Mortgage discrimination against black homeowners, exemplified by the 1930s-era policies of “redlining” black neighborhoods, as well as housing segregation, employment discrimination and unequal education, has limited reinvestment in these neighborhoods for generations and contributed to conditions of concentrated poverty. This history of discrimination remains a challenge and an important part of what makes these neighborhoods, the vacant buildings, historically significant in the present.

<!-- This map was created using QGIS and the CartoDB uploader. It is currently hosted on my personal elipousson CARTO account. -->

Map: [Vacant Buildings in Stressed Markets and Historic Districts](https://elipousson.carto.com/viz/cacbb1ba-1b63-11e6-b4fd-0ecfd53eb7d3/public_map)

--

<iframe width="960" height="700" frameborder="0" src="https://baltimoreheritage.carto.com/viz/b7346d6a-0018-11e6-ad61-0e8c56e2ffdb/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Where are property owners neglecting their buildings?

We can see the continued neglect of buildings in some neighborhoods by looking at citation data.

Baltimore Housing has used the new "Failed to Abate Unsafe Structure" citation to target neglectful property owners and encourage them to take action to mitigate the harm a vacant building can bring to a community. By looking at open citations, you can see where property owners are not doing enough.

Map: [Failed to Abate Unsafe Structure Open Citations: 2016](https://baltimoreheritage.carto.com/viz/b7346d6a-0018-11e6-ad61-0e8c56e2ffdb/public_map)

Google Sheet: [Failed to Abate Unsafe Structure - Data Dashboard](https://docs.google.com/spreadsheets/d/1iM2QJwN1LUZ9LzP5lMxSp3VR2XjibF2wtoN8ldY9re8/edit?usp=sharing)

--

<iframe width="960" height="700" frameborder="0" src="https://baltimoreheritage.carto.com/viz/343fb512-0014-11e6-a407-0ecfd53eb7d3/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Where are we tearing buildings down?

In some cases, demolition is seen as the only option.

Looking at the history of demolition permits over the past 14 years, East Baltimore stands out: Middle East, Broadway East, Oliver top the list of neighborhoods with the greatest number of demolition permits and South Clifton Park comes in fifth. West Baltimore is also represented with 208 demolition permits issued in Sandtown-Winchester, 154 in Harlem Park, and 143 in Poppleton.

<!-- This map just shows 2011-2016 - we should update the description here to focus on that period. -->

Map: [Demolition Permits and Historic Districts (2011-2016)](https://baltimoreheritage.carto.com/viz/343fb512-0014-11e6-a407-0ecfd53eb7d3/public_map)

Google Sheet: [Baltimore City Demolition Permits - Data Dashboard](https://docs.google.com/spreadsheets/d/1fNvFRqc6AqL-Fy-jXyerqzBIfzWRCbHDJg6qAchywdE/edit?usp=sharing)

--

### Where are property owners investing in rehabilitation?

Note:

Map: TK

Google Sheet: [Baltimore City Historic Property Tax Credit Program - Data (2003-2016)](https://docs.google.com/spreadsheets/d/1qh7NV7WyU8TxS0XLx0a3QvRYDSIfYHpXAFac7ttlJjE/edit?usp=sharing)

--

<iframe width="960" height="700" frameborder="0" src="https://baltimoreheritage.carto.com/viz/68692646-0057-11e6-acec-0e3ff518bd15/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Where is Project CORE tearing down buildings?

In March, Baltimore Housing and the Maryland Department of Housing and Community Development (DHCD) shared their 2016 plan for 75 demolition “clusters” (each cluster ranging in size from two to twenty-three buildings) for a total of 468 buildings in twenty-nine neighborhoods.

Neighborhoods with five or more demolition clusters include Broadway East, Shipley Hill, Middle East, and Sandtown-Winchester. Other affected neighborhoods include Mondawmin, Upton, Coldstream Homestead Montebello, and Central Park Heights.

Map: [CORE FY2016 Property List (Draft)](https://baltimoreheritage.carto.com/viz/68692646-0057-11e6-acec-0e3ff518bd15/public_map) (filtered to just show the demolition "T" clusters)

Google Sheet: [CORE FY16 Property List (Redacted Draft)](https://docs.google.com/spreadsheets/d/14XhBjhaOR-9d1N1XGf-haJkYflohKR1OXmOQEAKtRi8/edit?usp=sharing)

--

<iframe  width="960" height="700" frameborder="0" scrolling="no" src="https://plot.ly/~baltimoreheritage/5.embed"></iframe>

Note:

Is Project CORE tearing down buildings in historic districts?

About half the of demolition clusters are inside historic districts, including Baltimore East/South Clifton Park, Old West Baltimore, Franklin Square, Old East Baltimore, Coldstream Homestead Montebello, and East Monument.

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

---

## How did we approach our analysis?

- **Place**: Distribution, proximity
- **Time**: Trends, patterns, etc.

--

## Place

Note:

--

## Time

Note:

- Patterns of change over time:
	- demolition permits
	- historic tax credits

---

!["Vacants to Value at Work: Bringing down the blight on Tivoly Avenue!" from Baltimore Housing/YouTube](http://i.giphy.com/pXsKYQIOCpjdS.gif)


How do we use data to support preservation advocacy on vacant housing?

We want an early warning system. How can we know when properties are at-risk? How can we help inform neighborhoods about at-risk properties and support their work to promote preservation and reuse?

https://docs.google.com/document/d/1SHD_e1OZmX2-bYIckARlH90_S39KpjaIb20SIwDveYc/edit

---

Extra map

<iframe width="960" height="700" frameborder="0" src="https://elipousson.carto.com/viz/88fd2156-1b0e-11e6-9627-0e674067d321/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Where are property owners investing in vacant buildings?

Map: [Where are permits being issued for vacant buildings in 2016? ](https://elipousson.carto.com/viz/88fd2156-1b0e-11e6-9627-0e674067d321/public_map) (This is currently hosted on my personal elipousson CARTO account.)

Google Sheet: [Housing Permits for Vacant Buildings (2016)](https://docs.google.com/spreadsheets/d/10LpagmZana6lxO0aVemoDfrPjXPvTdLdTCPr9It09Jo/edit?usp=sharing)
