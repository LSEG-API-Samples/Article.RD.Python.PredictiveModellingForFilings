# Using AI modeling to interpret 10-Q filings

As outlined within Investopedia's, [Stock Analysis: Forecasting Revenue and Growth](https://www.investopedia.com/articles/active-trading/022315/stock-analysis-forecasting-revenue-and-growth.asp#:~:text=Analysts%E2%80%99%20forecasts%20are%20crucial%20to%20setting%20expected%20stock,buy%20or%20sell%20a%20stock%20cannot%20be%20made.),  <em>Making forward projections requires numerous inputs; some come from quantitative data and others are more subjective. The reliability and accuracy of the data drive the forecasts</em>.  Much of this information that determines projections, is available within company reports.  While its true that analysts projections are largely driven based on reported metrics, subjective predictions are a result of many factors, including the language and reporting done within company filings reports.

While it is critical to factor all inputs when making forward projections, is it possible to find any correlation with projections based on the interpretation of language within company reports?  By utilizing intelligent models that have been trained on financial data, I will investigate the question of whether the interpretation of finanical text can provide any indication of the direction of a given company's outlook.

Refer to the [Using AI modeling to interpret 10-Q filings]() defined within the Refinitiv Developer Community for more details.

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Platform Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

License(s):

- A [Refinitiv Data Platform (RDP)](https://developers.refinitiv.com/refinitiv-data-platform/refinitiv-data-platform-apis) license with access to the [Filings](https://api.refinitiv.com/) data services

[Development Environment](https://developers.refinitiv.com/en/api-catalog/eikon/eikon-data-api/tutorials#setting-up-a-python-development-environment)

- Notebook is presently designed to work against the Refinitiv Data Platform only 
- Packages: [rdp](https://pypi.org/project/refinitiv-dataplatform/) [pandas](https://pypi.org/project/pandas/) numpy matplotlib
- RDP for Python installation:  '**pip install refinitiv-data**'

## <a name="setup"></a>Setup

The package includes a single Jupyter Notebook, a couple of supporting modules and a RDP configuration file to define credentials to connect into the platform
  
* **Platform Access**
  
  Within the APIs configuration file: *refinitiv-data.config.json*, ensue you define the following parameters defined under *root.sessions.platform.rdp*:

  * app-key
  * username
  * password
  

### <a id="authors"></a>Author

* **Nick Zincone**



