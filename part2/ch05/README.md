# Part 2 - Chapter 5: Preparing Data Sources

- [Part 2 - Chapter 5: Preparing Data Sources](#part-2---chapter-5-preparing-data-sources)
  - [5.1 Getting Data from the Source](#51-getting-data-from-the-source)
  - [5.2 Managing Data Source Settings](#52-managing-data-source-settings)
  - [5.3 Working with Shared vs. Loacl Datasets](#53-working-with-shared-vs-loacl-datasets)
  - [5.4 Sotrage Modes](#54-sotrage-modes)
    - [5.4.1 Import data into a data model](#541-import-data-into-a-data-model)
    - [5.4.2 Dual Mode](#542-dual-mode)
  - [5.5 Considering the Query](#55-considering-the-query)
    - [5.5.1 Addressing and Correcting Performance](#551-addressing-and-correcting-performance)
    - [5.5.2 Diagnosing Queries](#552-diagnosing-queries)
  - [5.6 Exporting Power BI Desktop Files and Leveraging XMLA](#56-exporting-power-bi-desktop-files-and-leveraging-xmla)

## 5.1 Getting Data from the Source

List of all data sources in Power BI Desktop:

https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-data-sources

## 5.2 Managing Data Source Settings

Method 1: change in `Source` step in specific query

Method 2: change from `Data Source Settings`

## 5.3 Working with Shared vs. Loacl Datasets

The name of `Power BI datasets` in the book is changed to `Power BI semantic models` now.

## 5.4 Sotrage Modes

### 5.4.1 Import data into a data model

1. Local Storage: Data files and folders can only be imported into Power BI
2. DirectQuery: For database connectivity, there are two alternatives exist:
     - Import the data locally
     - Create a connection to the data source with DirectQuery
3. Live Connection: use the analysis services integrated with Power BI Desktop or Power BI Service
4. Composite Models: combine both importing data and DirectQuery, or connect to multiple DirectQuery connections.

### 5.4.2 Dual Mode

You can choose one of three options for the storage modele: Import, DirectQuery, or Dual.

Live Connection or Composite as well are hybrid modes of Import and DirectQuery.

Dual mode allows for a table to be cached and retrieved in DirectQuery mode when necessary.

## 5.5 Considering the Query

The method that ensures the most **accuracy** is `Import mode`.

|| Import | DirectQuery | Live Connection |
| --- | --- | --- | --- |
| Maximum Size | Based on how you're licensed | Limited by your infrastructure | Services have dataset size limits like Import Data. Otherwise, infrastructure limits your size. |
| Number of Sources | Unlimited | Unlimited | One |
| Security | Row level based on user login | Row level security. Security is defined as the data source for some sources. However, row level security can still be used in Power BI Desktop. | Can use data source security based on current user login. |
| Refresh Cycle | Based on license:<br><ul><li>Pro: eight refreshes per day</li><li>Premium: unlimited refreshes per day</li></ul> | Shows latest data available in the source | Shows latest data available in the source |
| Performance Metrics | Optimal | Varies based on data sources | Optimal |
| Data Transformation | All features | Limited based on data source transformation language. | Not applicable |
| Modeling requirements | All features | Significant limitations | Analysis services and Power BI Services measures created with limitations. |

### 5.5.1 Addressing and Correcting Performance

### 5.5.2 Diagnosing Queries

## 5.6 Exporting Power BI Desktop Files and Leveraging XMLA

- PBIDS: Power BI Desktop
- XMLA: XML for Analysis

---

Last Updated at 2026-01-11