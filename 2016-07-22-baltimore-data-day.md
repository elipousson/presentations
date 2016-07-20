## How can data and mapping help us understand vacancy and demolition?
### Baltimore Data Day

[Baltimore Heritage](http://baltimoreheritage.org/), 2016 July 22

[bit.ly/bmoreheritagedataday16](http://bit.ly/bmoreheritagedataday16)

---

![This Place Matters: Baltimore's Hebrew Orphan Asylum, September 8, 2010, Baltimore Heritage](https://c1.staticflickr.com/5/4113/4970821797_a07fa05333_b.jpg)

Note:

**Who is Baltimore Heritage?**

Founded in 1960, Baltimore Heritage is a nonprofit organization dedicated to preserving and promoting Baltimore's historic  building and neighborhoods.

With two staff members, 33 volunteer board members, and a host of volunteers, we lead tours, help homeowners, teach workshops, and more.

---

## Follow our presentation

[bit.ly/bmoreheritagedataday16](http://bit.ly/bmoreheritagedataday16)

Note:

Eli Pousson, our Director of Preservation and Advocacy, put together this presentation and is leading our efforts to incorporate data and mapping into our preservation advocacy.

We've posted our slides and notes online at[bit.ly/bmoreheritagedataday16](http://bit.ly/bmoreheritagedataday16)
where you can find links to more information for everything we talk about today.

---

## Preservation and Vacant Buildings

--

![American Ice Company, Franklin Street, September 14, 2012 (CC-BY)](/presentations/images/2012-09-14-american-ice-company-franklin-street.jpg)

Note:

Over the past few years, we have worked on vacant buildings in a few different ways:

- We organize tours and community events in historic neighborhoods with significant numbers of vacant buildings like Harlem Park and Franklin Square
- We advocate for the reuse of vacant historic buildings like the Hebrew Orphan Asylum or the American Ice Company
- We teach homeowners and developers about city and state historic tax credits which can be essential tools for the reuse of distressed historic buildings

Over the past two years, one of the most important opportunities we have to advocate for the preservation and reuse of vacant buildings is a regulatory review process known as **Section 106**.

Administered by the Maryland Historical Trust, Section 106 (named for the relevant section of the National Historic Preservation Act) require the Maryland Department of Housing and Community Development and Baltimore Housing to consider the impact of the city's strategic demolition program on the historic buildings and neighborhoods, consult with community groups, and, in some cases, mitigate any loss to historic buildings.

Unfortunately, this review process can be seen as a burden; a frustrating road block to the effort to rid the city of "blighted" buildings.

How can preservation be a more effective ally to neighborhoods struggling with large numbers of vacant buildings?

--

<iframe width="960" height="700" frameborder="0" scrolling="no" src="https://plot.ly/~baltimoreheritage/3.embed"></iframe>

Note:

There are 16,638 vacant building notices in Baltimore City.  7,018 of those, over 40% of the total, are located inside historic districts listed on the National Register of Historic Places. 4,878 of that subset, about 70%, are located on blocks described as "stressed" by the Baltimore Housing Market Typology.

When so many designated historic buildings are deteriorating from abandonment and neglect it makes it difficult to know where to focus our efforts. We know we can't save every vacant building in Baltimore. But, as the number of buildings targeted for demolition expands under Project CORE, we run the risk of losing important landmarks and fragmenting historic neighborhoods.

Chart: [Vacant building notices by market typology](https://plot.ly/~baltimoreheritage/3/)

--

![2023-2027 Herbert Street. Courtesy Maryland Department of Housing and Community Development](http://baltimoreheritage.org/wp-content/uploads/2016/04/2023-2027-Herbert-St-Project-CORE-1024x683.jpg)

Note:

Project CORE and the city's continuing challenges around vacant buildings is a also challenge for preservation in Baltimore. And a clear and detailed understanding of the situation is essential.

- How can we promote alternatives to demolition if we don't know where demolition is taking place?
- How can we encourage residents to participate in the review of demolition projects when information about projects is confusing or difficult to access?
- How can we argue for the feasibility of building reuse if we don't know where market conditions make reuse difficult?

**We can't.**

We believe data and mapping can help Baltimore Heritage take a more proactive approach to engaging with the regulatory review process. We think these tools can help us promote the reuse of vacant buildings and encourage reinvestment in historic neighborhoods.

--

![3208-3210 Elgin Avenue. Courtesy Maryland Department of Housing and Community Development.](http://baltimoreheritage.org/wp-content/uploads/2016/04/3208-3210-Elgin-Ave-Project-CORE-768x511.jpg)

Note:

Data can help us understand and focus our work on vacant buildings in a few different ways.

Effective information system can work as an early warning system: “spotting potential problem properties and areas before it is too late to handle them effectively” and providing “timely information to individuals or organizations responsible for taking action.”

This presentation is based on the past six months of experimenting and learning how we can incorporate data and mapping into our advocacy and outreach efforts. We are focused on how we can use these tools to inform and empower community residents in historic neighborhoods.

- How are we using data in our work on Project CORE?
- How can other nonprofits and advocacy groups use data to investigate housing and community development issues?

How do we use data to support preservation advocacy on vacant housing?

We want an early warning system. How can we know when properties are at-risk? How can we help inform neighborhoods about at-risk properties and support their work to promote preservation and reuse?

---

# Building a data and mapping toolbox

--

![Old toolbox, February 22, 2007, skistz/Flickr (CC BY-SA 2.0)](/presentations/images/2007-02-22-toolbox-skistz-cc-by-sa.jpg)

Note:

We are interested in sharing our experience with community organizations and small nonprofits who care about housing, community development, and historic preservation. We're also really interested in hearing from you about how you think we can use data to inform decision-making and educate residents, board members, and other stakeholders.

Image: [Old toolbox, February 22, 2007, skistz/Flickr (CC BY-SA 2.0)](https://www.flickr.com/photos/skistz/398429879/)

--

## Getting Started

- Where can you find **data**?
- What **tools** can you use to work with data?
- What can you **learn** from working with data?

Note:

We are not experts but we do have a bit of insight on these three questions. These are the questions you may want to ask to put together your own data and mapping toolbox:

1. Where can you find **data** related to vacant housing?
2. What **tools** can you use to work with the data?
3. What can you **learn** from looking at the data?

---

# Finding Data

--

![Watercolor style map of Baltimore](/presentations/images/2016-07-14-watercolor-baltimore.jpg)

Note:

We are using data that you can find for free online from Baltimore City and the State of Maryland. We are looking for information about both individual properties and whole neighborhoods.
--

![Open Baltimore (Screenshot)](/presentations/images/2016-07-14-open-baltimore.png)

Note:

[Open Baltimore](https://data.baltimorecity.gov/) provides useful data for anyone trying to understand housing and development issues in Baltimore including:

- vacant building notices
- citations for code violations
- 311 service requests on vacant buildings
- housing permits for work on vacant buildings
- and the Baltimore Housing Market Typology.

Using data from Open Baltimore can present real challenges. We've found data sets that are out of date, incomplete, and missing essential information. For example:

- Data on [Housing Citations](https://data.baltimorecity.gov/Housing-Development/Housing-Citations/pugq-wdem) from the Environmental Control Board lists the address for each violation but no coordinates. To use this data, we needed to geocode hundreds of addresses using a [Batch Geocoding service](http://www.findlatitudeandlongitude.com/batch-geocode/)
- Data on Vacant Building Notices from Baltimore Housing combines latitude and longitude into a single field and wraps them in parentheses. This small quirk of formatting makes it impossible to directly import the vacant building notice data into most web mapping tools without splitting up the combined field.

--

![Maryland iMap: Maryland's Mapping & GIS Data Portal (Screenshot)](/presentations/images/2016-07-14-MD-iMAP.png)

Note:

We also used:

- [Maryland iMap: Maryland's Mapping & GIS Data Portal](http://data.imap.maryland.gov/) to find data on National Register designated historic districts and the Maryland Inventory of Historic Properties.
- [Baltimore Neighborhood Indicators Alliance](http://bniajfi.org/) for additional data and analysis on housing and vacancy in Baltimore.

--

![Community Building by LA Great Streets, US, The Noun Project (PD)](/presentations/images/noun_476749.png)

Note:

Sometimes the data you need isn't available online. You can always ask for it. And ask again and again if you don't get an answer.

You may also need to tell  city and state staff about why you need a GIS data or a spreadsheet instead of a just a PDF file or (even worse) a photocopy. Getting data in standard accessible format is essential if you want to do more than just print it out or read it on your computer.

---

# Applying your tools

--

![Placemaking by LA Great Streets, US, The Noun Project (PD)](/presentations/images/noun_476738.png)

Note:

**What tools can you use to work with data?**

Don't forget, we are a tiny nonprofit. We don't have a big budget for consultants or for expensive software. Instead, we try to use free or cheap tools whenever we can.

Once we collected our data, we used three free tools to do some analysis, make maps, and create visualizations:

- [Google Sheets](https://www.google.com/sheets/about/)
- [CARTO](https://carto.com/)
- [QGIS](http://qgis.org/)

--

![Google Sheets (Screenshot)](/presentations/images/2016-07-14-google-sheets-example.png)

Note:

We started with Google Sheets, a free spreadsheet application included with Google Drive, to make some simple charts, sort and filter data, and to sync data from Open Baltimore to CARTO.

--

![CARTO (Screenshot)](/presentations/images/2016-07-14-carto-example.png)

Note:

CARTO is a web-based platform for geographical data visualization and analysis. They offer a free plan with basic features for everyone and a [20% discount for students and nonprofits](https://carto.com/pricing/#discount).

--

![QGIS (Screenshot)](/presentations/images/2016-07-14-qgis-example.png)

Note:

[QGIS](http://qgis.org/) is a free and open-source Geographic Information System desktop application. It is a more complicated tool than CARTO but there is a lot of useful [documentation available online](http://qgis.org/en/docs/index.html).

We can also easily move our data from QGIS to CARTO using [a free plugin](https://github.com/gkudos/qgis-cartodb) that syncs GIS data from one program to the other. CARTO can also [work with ArcGIS](https://carto.com/blog/esri-and-cartodb-together/) for any planners or professional who use that application.

<!-- For more on how we import data from Socrata into Google Sheets and sync Google Sheets with CARTO, see ["How to create a property information system for your neighborhood"](http://elipousson.github.io/data/2016/06/06/property-information-system-neighborhood/) by Eli Pousson. !-->

--

## Showing your work

![Community Led Design by LA Great Streets, US, The Noun Project (PD)](/presentations/images/noun_476748.png)

Note:

One final tool in our toolbox isn't a technology but an approach. We try to **show our work**. Web-based tools like Google Sheets and CARTO make it easy to share data and maps online, where we can invite residents, local preservationists, and partners to share their questions or comments. Sharing maps and data with stakeholders is a great way to solicit feedback and turn data and maps into stronger advocacy.

---

# Learning from data

Note:

Our work is primarily description, about making it easier for us and others to understand and make connections.

Here are a few of the questions we wanted to answer:

- What neighborhoods are most affected by vacancy and demolition?
- What vacant buildings are most likely to be selected for demolition?
- Where are the opportunities for Baltimore City or private developers to invest in stabilization, preservation, and reuse?

--

<iframe width="960" height="700" class="full-screen" frameborder="0" src="https://baltimoreheritage.carto.com/viz/c1c5b24a-d032-11e5-9637-0e5db1731f59/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

The scale of vacant housing in historic districts varies. Eleven of the city’s 58 residential National Register designated historic districts have over 100 VBNs and two have over 1,000 VBNs: the Old West Baltimore Historic District with 2038 and Baltimore East/South Clifton Park Historic District with 1790.

Looking closer we've found that in:

- Reservoir Hill Historic District, 123 of 1557 buildings are vacant (7.9%)
- Upton’s Marble Hill Historic District, 48 of 348 buildings are vacant (13.8%)
- Union Square-Hollins Market Historic District, 239 of 1305 buildings are vacant (18.31%)
- Franklin Square Historic District, 338 of 1192 buildings are vacant (28.36%)

Map: [Vacant Building Notices and Historic Districts](https://baltimoreheritage.carto.com/viz/c1c5b24a-d032-11e5-9637-0e5db1731f59/public_map) (this map needs work)

Google Sheet: [Vacant Buildings - Historic Districts - Baltimore City](https://docs.google.com/spreadsheets/d/1fR7B9fbAblGgZVfb6_GFXeincgPruYjb5bWp811xLxs/edit?usp=sharing) (this data may show different things than the map)

--

## Where do market conditions discourage preservation in historic districts?

--

<iframe width="960" height="700" frameborder="0" src="https://elipousson.carto.com/viz/cacbb1ba-1b63-11e6-b4fd-0ecfd53eb7d3/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

Vacant buildings on stressed market blocks present the greatest challenge for preservation and for anyone who cares about housing and community development in Baltimore. The significant number of vacant properties in historically black neighborhoods like Upton’s Marble Hill is no coincidence.

Mortgage discrimination against black homeowners, exemplified by the 1930s-era policies of “redlining” black neighborhoods, as well as housing segregation, employment discrimination and unequal education, has limited reinvestment in these neighborhoods for generations and contributed to conditions of concentrated poverty. This history of discrimination remains a challenge and an important part of what makes these neighborhoods, the vacant buildings, historically significant in the present.

<!-- This map was created using QGIS and the CartoDB uploader. It is currently hosted on my personal elipousson CARTO account. -->

Map: [Vacant Buildings in Stressed Markets and Historic Districts](https://elipousson.carto.com/viz/cacbb1ba-1b63-11e6-b4fd-0ecfd53eb7d3/public_map)

--

## Where are property owners neglecting their buildings?

--

<iframe width="960" height="700" frameborder="0" src="https://baltimoreheritage.carto.com/viz/b7346d6a-0018-11e6-ad61-0e8c56e2ffdb/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

We can see the continued neglect of buildings in some neighborhoods by looking at citation data.

Baltimore Housing has used the new "Failed to Abate Unsafe Structure" citation to target neglectful property owners and encourage them to take action to mitigate the harm a vacant building can bring to a community.

By looking at open citations, you can see where property owners are not doing enough. You can also see neighborhoods where Baltimore Housing is _not_ using this citation because it is difficult to cite a property owner when too many other buildings on the block are vacant.

Map: [Failed to Abate Unsafe Structure Open Citations: 2016](https://baltimoreheritage.carto.com/viz/b7346d6a-0018-11e6-ad61-0e8c56e2ffdb/public_map)

Google Sheet: [Failed to Abate Unsafe Structure - Data Dashboard](https://docs.google.com/spreadsheets/d/1iM2QJwN1LUZ9LzP5lMxSp3VR2XjibF2wtoN8ldY9re8/edit?usp=sharing)

--

## Where is Baltimore tearing buildings down?

--

<iframe width="960" height="700" frameborder="0" src="https://baltimoreheritage.carto.com/viz/343fb512-0014-11e6-a407-0ecfd53eb7d3/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

In some cases, demolition is seen as the only option.

Looking at the history of demolition permits over the past 14 years, East Baltimore stands out: Middle East, Broadway East, Oliver top the list of neighborhoods with the greatest number of demolition permits and South Clifton Park comes in fifth. West Baltimore is also represented with 208 demolition permits issued in Sandtown-Winchester, 154 in Harlem Park, and 143 in Poppleton.

<!-- This map just shows 2011-2016 - we should update the description here to focus on that period. -->

Map: [Demolition Permits and Historic Districts (2011-2016)](https://baltimoreheritage.carto.com/viz/343fb512-0014-11e6-a407-0ecfd53eb7d3/public_map)

Google Sheet: [Baltimore City Demolition Permits - Data Dashboard](https://docs.google.com/spreadsheets/d/1fNvFRqc6AqL-Fy-jXyerqzBIfzWRCbHDJg6qAchywdE/edit?usp=sharing)

--

### Where are property owners investing in rehabilitation?

--

Map: TK

Note:

Google Sheet: [Baltimore City Historic Property Tax Credit Program - Data (2003-2016)](https://docs.google.com/spreadsheets/d/1qh7NV7WyU8TxS0XLx0a3QvRYDSIfYHpXAFac7ttlJjE/edit?usp=sharing)

--

## Where is Project CORE tearing down buildings?

--

<iframe width="960" height="700" frameborder="0" src="https://baltimoreheritage.carto.com/viz/68692646-0057-11e6-acec-0e3ff518bd15/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Note:

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

## How can data and mapping help us understand vacancy and demolition?
### Baltimore Data Day

[Baltimore Heritage](http://baltimoreheritage.org/), 2016 July 22

[bit.ly/bmoreheritagedataday16](http://bit.ly/bmoreheritagedataday16)
