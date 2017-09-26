## Not All Customers Are Created Equal

Have you ever wondered who your most valuable customers are? This project, created for a software company, aims to discover what makes their users unique and how to identify those who stand out above the rest.

<img src="images/people.jpg" width="600">

## Updates

#### Current Progress

* Further cleaned up pipeline; combined all cleaning data files into one process
* Developed model to identify customers most likely to purchase the highest value license

#### Next Steps

* Develop mini-models to fill nulls more accurately
* Engineer more features in order to reduce errors

## Project Outline

#### Data Sources

Note: These data sources will be stored separately in a private repository.

* Mechanical Turk - Data from past experiment of identifying customers' website categories
* Intercom - Tracks data on customer communication such as Facebook messages and live webpage chat
* Drip - Tracks data on email related customer communication
* EDD - Tracks data on customer purchases
* Google Analytics - Tracks data on customer webpage browsing
* HubSpot - Tracks data on marketing and sales campaigns
* HelpScout - Tracks data on support tickets

File date range: 07/25/14 - 08/31/17

#### Project Goals

* Customer segmentation
  * Which groups generate the most revenue?
  * What factors are most predictive of revenue from each group?
  * Use this information to create custom marketing/landing pages/pricing for each group
* Reducing support tickets
  * What factors are most predictive of low numbers of support tickets?
  * Use this information for identifying high value, low involvement customers

#### Planned Methods

  * Obtaining data - used a combination of API's and direct downloads to obtain the data from the above sources
  * Customer segmentation - KMeans clustering
  * Profit predictions per cluster
    * Regression analysis
    * KNeighbors
    * Decision trees
    * SVR (linear kernel)
    * SGD

#### Technologies Used

* Python
* Pandas
* Numpy
* AWS (EC2 instance)

#### Deliverables

Slideshow presentation for broad project overview
