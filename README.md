#  Azure Enterprise Data Analyst Associate (DP-500) Exam - Preparation

:wave: Given the lack of any courses or practice tests for the new [DP-500](https://docs.microsoft.com/en-us/learn/certifications/azure-enterprise-data-analyst-associate/), I've collected some **useful links** for each of the **skills measured** below: 

* [Implement and manage a data analytics environment (25–30%)](#implement-and-manage-a-data-analytics-environment-2530)
* [Query and transform data (20–25%)](#query-and-transform-data-2025)
* [Implement and manage data models (25–30%)](#implement-and-manage-data-models-2530)
* [Explore and visualize data (20–25%)](#explore-and-visualize-data-2025)

## Implement and manage a data analytics environment (25–30%)

### Govern and administer a data analytics environment

* manage Power BI assets by using Azure Purview
  * https://docs.microsoft.com/en-us/learn/modules/manage-power-bi-artifacts-use-microsoft-purview/
  * https://docs.microsoft.com/en-us/azure/purview/register-scan-power-bi-tenant?tabs=Scenario1
* identify data sources in Azure by using Azure Purview
  * https://docs.microsoft.com/en-us/azure/purview/microsoft-purview-connector-overview
  * https://docs.microsoft.com/en-us/azure/purview/manage-data-sources
* recommend settings in the Power BI admin portal
  * https://docs.microsoft.com/en-us/power-bi/admin/service-admin-auditing
* recommend a monitoring and auditing solution for a data analytics environment, including Power BI REST API and PowerShell cmdlets
  * https://docs.microsoft.com/en-us/power-bi/admin/service-admin-auditing
  * https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-audit-usage#create-audit-logs-for-internal-activity-auditing-and-compliance


### Integrate an analytics platform into an existing IT infrastructure

* identify requirements for a solution, including features, performance, and licensing strategy
  * https://docs.microsoft.com/en-us/power-bi/fundamentals/service-features-license-type
  * https://docs.microsoft.com/en-us/power-bi/enterprise/service-admin-licensing-organization
* configure and manage Power BI capacity
  * https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-capacity-settings
* recommend and configure an on-premises gateway in Power BI
  * https://docs.microsoft.com/en-us/power-bi/connect-data/service-gateway-onprem
* recommend and configure a Power BI tenant or workspace to integrate with Azure Data Lake Storage Gen2
  * https://docs.microsoft.com/en-us/power-query/connectors/analyze-data-in-adls-gen2
  * https://docs.microsoft.com/en-us/power-bi/transform-model/dataflows/dataflows-azure-data-lake-storage-integration
* integrate an existing Power BI workspace into Azure Synapse Analytics
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/quickstart-power-bi
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-visualize-power-bi

### Manage the analytics development lifecycle

* commit code and artifacts to a source control repository in Azure Synapse Analytics
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/cicd/source-control
* recommend a deployment strategy for Power BI assets
  * https://docs.microsoft.com/en-us/learn/modules/create-manage-workspaces-power-bi/4-development-lifecycle-strategy?ns-enrollment-type=learningpath&ns-enrollment-id=learn-bizapps.manage-workspaces-datasets-power-bi
* recommend a source control strategy for Power BI assets
* implement and manage deployment pipelines in Power BI
  * https://docs.microsoft.com/en-us/power-bi/create-reports/deployment-pipelines-best-practices
* perform impact analysis of downstream dependencies from dataflows and datasets
  * https://docs.microsoft.com/en-us/learn/modules/create-manage-workspaces-power-bi/5-troubleshoot-data 
* recommend automation solutions for the analytics development lifecycle, including Power BI REST API and PowerShell cmdlets

### Power BI REST API and PowerShell cmdlets 

* deploy and manage datasets by using the XMLA endpoint
  * https://docs.microsoft.com/en-us/power-bi/enterprise/service-premium-connect-tools
* create reusable assets, including Power BI templates, Power BI data source (.pbids) files, and shared datasets
  * https://microsoftlearning.github.io/DP-500-Azure-Data-Analyst/Instructions/labs/16-create-reusable-power-bi-artifacts.html
  * https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-data-sources


## Query and transform data (20–25%)

### Query data by using Azure Synapse Analytics

* identify an appropriate Azure Synapse pool when analyzing data
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/sql/develop-overview
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/sql/best-practices-serverless-sql-pool
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/sql/best-practices-dedicated-sql-pool
* recommend appropriate file types for querying serverless SQL pools
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse
* query relational data sources in dedicated or serverless SQL pools, including querying partitioned data sources
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-partition
* use a machine learning PREDICT function in a query
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-predict

### Ingest and transform data by using Power BI

* identify data loading performance bottlenecks in Power Query or data sources
  * https://docs.microsoft.com/en-us/power-bi/guidance/import-modeling-data-reduction
* implement performance improvements in Power Query and data sources
  * https://docs.microsoft.com/en-us/power-bi/guidance/directquery-model-guidance
  * https://docs.microsoft.com/en-us/learn/modules/understand-scalability-power-bi/3-implement-data-modeling-best-practices
  * https://microsoftlearning.github.io/DP-500-Azure-Data-Analyst/Instructions/labs/13-use-tools-to-optimize-power-bi-performance.html
* create and manage scalable Power BI dataflows
  * https://docs.microsoft.com/en-us/power-bi/transform-model/dataflows/dataflows-develop-solutions
  * https://microsoftlearning.github.io/DP-500-Azure-Data-Analyst/Instructions/labs/05-create-a-dataflow.html
* identify and manage privacy settings on data sources
  * https://docs.microsoft.com/en-us/power-bi/enterprise/desktop-privacy-levels
* create queries, functions, and parameters by using the Power Query Advanced Editor
* query advanced data sources, including JSON, Parquet, APIs, and Azure Machine Learning models
  * https://docs.microsoft.com/en-us/power-bi/connect-data/service-aml-integrate
  * https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-data-sources

## Implement and manage data models (25–30%)

### Design and build tabular models 

* choose when to use DirectQuery for Power BI datasets
  * https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-directquery-about 
* choose when to use external tools, including DAX Studio and Tabular Editor 2
  * https://microsoftlearning.github.io/DP-500-Azure-Data-Analyst/Instructions/labs/13-use-tools-to-optimize-power-bi-performance.html
* create calculation groups
  * https://docs.microsoft.com/en-us/analysis-services/tabular-models/calculation-groups?view=asallproducts-allversions#limitations
  * https://docs.microsoft.com/en-us/learn/modules/create-calculation-groups/
  * https://microsoftlearning.github.io/DP-500-Azure-Data-Analyst/Instructions/labs/07-create-calculation-groups.html
* write calculations that use DAX variables and functions, for example handling blanks or errors, creating virtual relationships, and working with iterators
  * https://docs.microsoft.com/en-us/dax/best-practices/dax-variables
  * https://docs.microsoft.com/en-us/dax/dax-function-reference
* design and build a large format dataset
  * https://docs.microsoft.com/en-us/power-bi/enterprise/service-premium-large-models
* design and build composite models, including aggregations
  * https://docs.microsoft.com/en-us/power-bi/guidance/composite-model-guidance
  * https://microsoftlearning.github.io/DP-500-Azure-Data-Analyst/Instructions/labs/08-create-a-composite-model.html
  * https://microsoftlearning.github.io/DP-500-Azure-Data-Analyst/Instructions/labs/12-improve-query-performance-with-aggregations.html
* design and implement enterprise-scale row-level security and object-level security
  * https://docs.microsoft.com/en-us/power-bi/guidance/rls-guidance
  * https://docs.microsoft.com/en-us/analysis-services/tabular-models/object-level-security?view=asallproducts-allversions

### Optimize enterprise-scale data models

* identify and implement performance improvements in queries and report visuals
  * https://daxstudio.org/documentation/features/run-benchmark/
* troubleshoot DAX performance by using DAX Studio
  * https://daxstudio.org/documentation/troubleshooting/ 
* optimize a data model by using Tabular Editor 2
  * https://docs.tabulareditor.com/te2/Power-BI-Desktop-Integration.html
  * https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-external-tools
* analyze data model efficiency by using VertiPaq Analyzer
* implement incremental refresh
  * https://docs.microsoft.com/en-us/power-bi/connect-data/incremental-refresh-overview
* optimize a data model by using denormalization

## Explore and visualize data (20–25%)

### Explore data by using Azure Synapse Analytics

* explore data by using native visuals in Spark notebooks 
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-data-visualization
  * https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-to-power-bi
  * https://docs.microsoft.com/en-us/learn/modules/understand-big-data-engineering-with-apache-spark-azure-synapse-analytics/5-visualize-data
* explore and visualize data by using the Azure Synapse SQL results pane

### Visualize data by using Power BI

* create and import a custom report theme
  * https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-report-themes
* create R or Python visuals in Power BI
  * https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-python-visuals
  * https://docs.microsoft.com/en-us/learn/modules/visuals-power-bi/6-python-visual
* connect to and query datasets by using the XMLA endpoint
  * https://docs.microsoft.com/en-us/power-bi/enterprise/service-premium-connect-tools
* design and configure Power BI reports for accessibility
  * https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-accessibility-creating-reports
  * https://docs.microsoft.com/en-us/learn/modules/understand-advanced-data-visualization-concepts/4-design-configure-power-bi-reports-for-accessibility
* enable personalized visuals in a report
  * https://docs.microsoft.com/en-us/power-bi/consumer/end-user-personalize-visuals
* configure automatic page refresh
  * https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-automatic-page-refresh
* create and distribute paginated reports in Power BI Report Builder
  * https://docs.microsoft.com/en-us/power-bi/paginated-reports/paginated-reports-save-to-power-bi-service
  * https://docs.microsoft.com/en-gb/learn/modules/create-paginated-reports-power-bi/
