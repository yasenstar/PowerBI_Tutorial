 PowerBI Tutorial
(Jack Hyman)

Get the book --

- Amazon: https://www.amazon.com/Microsoft-Power-Dummies-Jack-Hyman/dp/1119824877
- Wiley: https://www.wiley.com/en-us/Microsoft+Power+BI+For+Dummies-p-9781119824893


# Part 0: Introduction

## 0.0 Preface

### What does Business Intelligence (BI) require?

#### Basic: querying data sources, reporting, caching data, and visualizing data

#### If you had to address your organization's needs, what would they do?

#### Would taking structured, unstructured, and semistructured data and making sense of it be part of your organizational requirements?

#### Perhaps developing robust business analytics outputs for executive consumption?

#### Is the mandate from the leadership the delivery of complex reports, visualizations, dashboards, and key performance indicators?

### Brief history of Power BI

#### Power BI was initially conceived as part of the SQL Server Reporting Team back in 2010.

#### Then, Power BI made its way into the Office 365 suite in September 2013 as an advanced analytics product.

#### Power BI was built around Microsoft Excel core add-ins: Power Query, Power Pivot, and Power View.

#### Along the way, Microsoft added a few artificial intelligence features, such as the Q&A Engine, enterprise-level data connectors, and security options via the Power BI Gateway.

#### The product became so popular with the enterprise business community that, in July of 2015, Power BI was separated from the Office family, becoming its own product line.

#### Finally, in late 2019, Power BI merged with other Microsoft products to form the Power Platform family, which consists of Power Apps (mobile), Power Automate (workflow), and Power BI (business intelligence)

## 0.1 About this Book

### Target Audience

#### Anyone interested in business analytics, focusing as it does on the general platform capabilities across the Power BI platform

### What will be learnt from here?

#### Business Analysts who need to find a tool as the source to complete variable critical tasks in your field

#### Data Professionals who wish to understand the foundational activities across the Power BI platform into using Microsoft's business intellegence (BI) platform

#### Developers who want to find tips, tricks and techniques from Power BI (or beyond) especially DAX area

#### IT Professionals that can treat this as a starting point if you want to enter the world of Microsoft enterprise business intelligence

#### Managers or Executives to get understand of the Power BI product which help your to bring guidelines for business intelligence requirements to the team

## 0.2 Foolish Assumptions

### This book/course is for users who want to learn about the critical features across the 3 Power BI platforms: Desktop, Services and Mobile

### Have already downloaded a copy of Power BI Desktop

### Have at least signed up for a Power BI Free Services account, but preferably have a Power BI Pro account

### Have access to the Internet

### Have a meaningful dataset

## 0.3 Icons Used in This Book: Tip, Remember, Technical Stuff, On the Way, Warning

## 0.4 Beyond the Book

### Power BI for Dummies Cheat Sheet

Another cheat sheet: https://www.dummies.com/article/technology/information-technology/data-science/general-data-science/microsoft-power-bi-for-dummies-cheat-sheet-289744/


### Sample Dataset

# Part 1: Put Your BI Thinking Caps On

Learning Outcomes:

- Get introduced to the types of data used in enterprise BI solutions
- Identify the roles, responsibilities, and products produced by BI professionals
- Discover the licensing options and core features available with Power BI


## CH01 A Crash Course in Data Analytics Terms: Power BI Styles

Chapter Learning Outcomes:

-  Figuring out the different types of data Power BI can handle
-  Understanding your options for business intelligence tooling
-  Familiarizing yourself with Power BI terminology


### 01.0 Preface

#### Dealing with data isn't always a chore (苦差事) -- data be be fund to explore as well

### 01.1 What is Data, Really?

#### Data contains facts. Sometimes, the facts make sense; sometimes, they're meaningless unless you add a bit of context.

#### Information is the collective body of all the data parts, that results in the factoids making logical sense

#### 01.1.1 Working with Structured Data
 (see:)
##### Structured data conforms to a tabular format, meaning that each column and row must maintain an interrelationship.
 
In Power BI, the structured data conform to a formal specification of tables with rows and columns, commonly referred to as adata schema.


##### The most accessible data sources for BI tools are structured

##### Platforms that offer robust structured data options:

###### Microsoft SQL Server

###### Microsoft Azure SQL Server

###### Microsoft Access

###### Azure Table Storage

###### Oracle

###### IBM DB2

###### MySQL

###### PostgreSQL

###### Microsoft Excel

###### Google Sheets

#### 01.1.2 Looking at Unstructured Data
 (see:)
##### Video, audio, photo, or text file is considered unstructured data

#### 01.1.3 Adding Semistructured Data to the Mix
 (see:)
##### Semistructured data contains tags that make the data easier to organize in some form of hierarchy.

##### Nonrelational data system or NoSQL databases are best associated with semistructured data.

##### If the serialized language can communicate and speak the same language, a semistructured dataset has great potential

### 01.2 Looking Under the Power BI Hood (引擎罩, 兜帽)
 
Power BI is a product that brings together many smaller, cloud-based apps and services with a specific objective: to organize, collect, manage, and analyze big datasets.


##### Power Query: a data connection tool you can use to transform, combine, and enhance data across several data sources

##### Power Pivot: a data modeling tool

##### Power View: a data visualization tool you can use to generate interactive charts, graphs, maps and visuals

##### Power Map: a visualization tool for creating 3D map renderings

##### Power Q&A: an artificial intelligence engine that allows you to ask questions and receive responses using plain language

##### Power BI Desktop: a free, all-in-one solution that brings together all the apps described in this list into a single graphical user interface

##### Power BI Services: a cloud-based user experience to collaborate and distribute products such as reports with others
 
Big Data is a concept where the buisness and data analyst will evaluate extremely large datasets, which may reveal patterns and trends relating to human behaviors and interactions not easily identifiable without the use of specific tools.


#### 01.2.1 Posing Questions with Power Query

##### Before Power BI became its own product line, it was originally an advanced query and data manipulation add-in for Excel, circa (大约) 2010

##### One of the justifications for the switch to a dedicated product was the need for a more robust query editor.

###### With the Excel editor, it was a single data source

###### With Power BI's Power Query, you can extract data from numerous data sources

### 01.3 Knowing Your Power BI Terminology

### 01.4 Business Intelligent (BI): The Definition

## CH02 The Who, How, and What of Power BI

### 02.1 Highlighting the Who of Power BI

### 02.2 Understanding How Data Comes to Life

### 02.3 Examining the Various Types of Data Analytics

### 02.4 Taking a Look at the Big Picture

## CH03 Oh, the Choices: Power BI Versions

### 03.1 Why Power BI versus Excel?

### 03.2 Power BI Products in a Nutshell

### 03.3 Examining the Details of the Licensing Options

### 03.4 On the Road with Power BI Mobile

### 03.5 Working with Power BI Report Server

### 03.6 Linking Power BI and Azure

## CH04 Power BI: The Highlights

### 04.1 Power BI Desktop: A Top-Down View

### 04.2 Services: Far and Wide

# Part 2: It's Time to Have a Data Party

## CH05 Preparing Data Sources

### 05.1 Getting Data from the Source

### 05.2 Managing Data Source Settings

### 05.3 Working with Shared versus Local Datasets

### 05.4 Storage Modes

### 05.5 Considering the Query

### 05.6 Exporting Power BI Desktop Files and Leveraging XMLA

## CH06 Getting Data from Dynamic Sources

### 06.1 Getting Data from Microsoft-Based File Systems

### 06.2 Working with Relational Data Sources

### 06.3 Importing Data from a Non-relational Data Source

### 06.4 Importing JSON File Data into Power BI

### 06.5 Importing Data from Online Sources

### 06.6 Creating Data Source Combos

### 06.7 Dealing with Modes for Dynamic Data

### 06.8 Fixing Data Import Errors

## CH07 Cleaning, Transforming, and Loading Your Data

### 07.1 Engaging Your Detective Skills to Hunt Down Automalies and Inconsistencies

### 07.2 Stepping through the Data Lifecycle

### 07.3 Evaluating the Transforming Column Data Types

### 07.4 Tweaking Power Query's M Code

### 07.5 Configuring Queries for Data Loading

### 07.6 Resolving Errors During Data Import

# Part 3: The Art and Science of Power BI

## CH08 Crafting the Data Model

### 08.1 An Introduction to Data Models

### 08.2 Dealing with Table and Column Properties

### 08.3 Managing Cardinality and Direction

### 08.4 Data Granularity

## CH09 Designing and Deploying Data Models

### 09.1 Creating a Data Model Masterpiece

### 09.2 Managing Relationships

### 09.3 Arranging Data

### 09.4 Working with Extended Data Models

### 09.5 Publishing Data Models

## CH10 Perfecting the Data Model

### 10.1 Matching Queries with Capacity

## CH11 Visualizing Data

### 11.1 Looking at Report Fundamentals and Visualizations

### 11.2 Dealing with Table-Based and Complex Visualizations

### 11.3 Dabbling in Data Science

### 11.4 Questions and Answers

## CH12 Pumping Out Reports

### 12.1 Formatting and Configuring Report Visualizations

### 12.2 Filtering and Sorting

### 12.3 Configuring the Report Page

### 12.4 Refreshing Data

## CH13 Diving into Dashboarding

### 13.1 Configuring Dashboards

### 13.2 Creating a New Dashboard

### 13.3 Enriching Your Dashboard with Content

### 13.4 Pinning Reports

### 13.5 Customizing with Themes

### 13.6 Working with Dashboard Layouts

### 13.7 Integrating Q&A

### 13.8 Setting Alerts

# Part 4: Oh, No! There's a Power BI Programming Language!

## CH14 Digging Into DAX

### 14.1 Discovering DAX

### 14.2 Dealing with Data Types

### 14.3 Operating with Operators

### 14.4 Making a Statement

### 14.5 Ensuring Compatibility

## CH15 Fun with DAX Functions

### 15.1 Working with DAX Parameters and Naming Conventions

### 15.2 Using Formulas and Functions

## CH16 Digging Deeper into DAX

### 16.1 Working with Variables

### 16.2 Writing DAX Formulas

### 16.3 Best Practices for DAX Coding and Debugging in Power BI

## CH17 Sharing and the Power BI Workspace

### 17.1 Working Together in a Workspace

### 17.2 Creating and Configuring Apps

### 17.3 Slicing and Dicing Data

### 17.4 Troubleshooting the Use of Data Lineage

### 17.5 Datasets, Dataflows, and Lineage

### 17.6 Defending Your Data Turf

# Part 5: Enhancing Your Power BI Experience

## CH18 Making Your Data Shine

### 18.1 Establishing a Schecule

### 18.2 Protecting the Data Fortress

### 18.3 Sharing the Data Love

### 18.4 Refreshing Data in Baby Steps

### 18.5 Treating Data Like Gold

### 18.6 Configuring for Big Data

## CH19 Extending the Power BI Experience

### 19.1 Linking Power Platform and Power BI

### 19.2 Powering Up with Power Apps

### 19.3 Integrating OneDrive and Power BI

### 19.4 Collaboration, SharePoint, and Power BI

### 19.5 Automating Workflows with Power BI

### 19.6 Unleashing Dynamics 365 for Data Analytics

# Part 6: The Part of Tens

## CH20 Two Ways to Optimize DAX Using Power BI

### 20.01 Focusing on Logic

### 20.02 Formatting Your Code

### 20.03 Keeping the Structure Simple (KISS)

### 20.04 Staying Clear of Certain Functions

### 20.05 Making Your Measures Meaningful

### 20.06 Filtering with a Purpose

### 20.07 Transforming Data Purposefully

### 20.08 Playing Hide-and-Seek with Your Columns

### 20.09 Using All Those Fabulous Functions

### 20.10 Rinse, Repeat, Recycle

## CH21 Ten Ways to Make Compelling Reports Accessible and User-Friendly

### 21.01 Navigating the Keyboard

### 21.02 Having a Screen Reader As Your Companion

### 21.03 Standing Out with Contract

### 21.04 Recognizing Size Matters (with Focus Mode)

### 21.05 Switching between Data Tables and Visualizations

### 21.06 A Little Extra Text Goes a Long Way

### 21.07 Setting Rank and Tab Order

### 21.08 It's All About Titles and Labels

### 21.09 Leaving Your Markets

### 21.10 Keeping with a Theme

# Microsoft Certification

## Power BI Data Analyst Associate

### Skilles

#### Clean, Transform and Load Data in Power BI

#### Design a Data Model in Power BI

#### Add Measures to Power BI Desktop Models

#### Optimize a Model for Performance in Power BI

#### Design Power BI Reports

#### Enhance Power BI Report Designs for the User Experience

#### Perform Analytics in Power BI

#### Create and Manage Workspaces in Power BI

#### Manage Datasets in Power BI

### Learning Resource

#### 1. Get Started with Microsoft Data Analytics

#### 2. Prepare Data for Analysis with Power BI

#### 3. Model Data with Power BI

#### 4. Build Power BI Visuals and Reports

#### 5. Manage Workspaces and Datasets in Power BI

## Power Platform Solution Architect Expert (PL-600)
