# Company-Financial-Statements-API-
Income Statements API, Balance Sheet API and Cash Flow Statements API are contained within <a href="https://tradefeeds.com/company-financial-statements-api//" rel="nofollow">Tradefeeds Company Financial Statements API</a>. We provide historic data on both annual and quarterly income statements, balance sheets and cash flow statements of more than 7000 public companies listed on the NYSE, Nasdaq and other stock exchanges in the United States. We also provide you with data on income statements forecasts, balance sheets forecasts and cash flow statements forecasts. All financial statements forecasts are prepared by external financia analysts. The Company Financial Statements API database also includes the following feature of choosing several financials of different fiscal years and comparing them. Tradefeeds data is sourced from credible partners such as SEC as well as company official websites.

By accessing our Company Financial Statements API database, customers can end up the exhaustive process of searching actively data on financial statements themselves. Through fast and seamless JSON REST API, they get all data they need from Tradefeeds API database. The data is also retrieved in downloadable excel or csv files. Thus, we ensure that our diverse customers are satisfied with the data retrieval process - from developers who build their applications for a specific audience to in-house teams in all-sized companies. 

Tradefeeds subscription packages are developed in such a way to serve all customers' needs. For the moment, there is no free trial provided. In case that you are a researcher or a student, we could negotiate a free trial. <a href="https://tradefeeds.com/api-documentation/" rel="nofollow">Sign up for an API key</a> and we work out your case.

<h2><a id="user-content-api-features" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/Company-Financial-Statements-API#api-features" aria-hidden="true"></a>API Features</h2>

<li><strong>Current and historic financial statements</strong></li>
<li><strong>Financial statements forecasts</strong></li>
<li><strong>Filter by individual characteristics</strong></li>
<li><strong>Comparison between financials by choosing multiple points of comparison</strong></li>


<h2><a id="user-content-ways-to-access-company-data" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/Company-information-API#ways-to-access-company-financial-statements-data" aria-hidden="true"></a>Ways to access company financial statements data</h2>
<ul>
 	<li><strong>JSON REST API</strong></li>
 	<li><strong>Excel CSV download</strong></li>
 	<li><strong>PDF reports</strong></li>
 	<li><strong>Email link</strong></li>
</ul>



<h2>Documentation</h2>

Our <a href="https://tradefeeds.com/api-documentation/" rel="nofollow">documentation</a> includes input API filtering parameters, output response objects with explanation of their meaning. Clear request and response examples are given on the documentation page. Furthermore, we provide SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala

<h2>Request and response examples</h2>

<strong>Example 1: Income Statements</strong>


<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/incomestatements
    ?key=YOUR-KEY
        &stock_ticker_symbol=aapl</a></p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
        },
        "output": {
            "total_revenue": "347,155,000",
            "operating_revenue": "347,155,000"
            "cost_of_revenue": "204,804,000"
            "gross_profit": "142,351,000"
            "operating_expense": "42,413,000"
            "operating_income": "99,938,000"
            "net_non_operating_interest_income_expense": "345,000"
            "other_income_expense": "577,000"
            "pretax_income": "100,860,000"
            "tax_provision": "14,058,000"
            "net_income_common_stockholders": "86,802,000"
            "diluted_ni_available_to_com_stockholders": "86,802,000",
            "basic_eps": ""
            "diluted_eps": ""
            "basic_average_shares": ""
            "diluted_average_shares": ""
            "total_operating_income_as_reported": "99,938,000"
            "total_expenses": "247,217,000"
            "net_income_from_continuing_and_discontinued_operation": "86,802,000"
            "normalized_income": "86,802,000"
            "interest_income": "2,952,000"
            "interest_expense": "2,607,000"
            "net_interest_income": "345,000"
            "ebit": "103,467,000"
            "ebitda": "114,464,000"
            "reconciled_cost_of_revenue": "204,804,000"
            "reconciled_depreciation": "10,997,000",
            "net_income_from_continuing_operation_net_minority_interest": "86,802,000"
            "total_unusual_items_excluding_goodwill": "0"
            "total_unusual_items": "0"
            "normalized_ebitda": "114,464,000"
            "tax_rate_for_calcs": "0"
            "tax_effect_of_unusual_items": "0"
        }
    [





<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/incomestatements
    ?key=YOUR-KEY
        &sector=technology
        &industry=consumer_electronics
        &income_statement=total_revenue
        &year=2021</a></p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "347,155,000",
            },
        "basics": {
            "name": "Microsoft Corporation",
            "stock_ticker_symbol": "MSFT"
            "isin_identifier": "US5949181045"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "168,088,000",
            },
        "basics": {
            "name": "Dell Technologies Inc",
            "stock_ticker_symbol": "DELL"
            "isin_identifier": "US24703L2025"
            "exchange": "NYSE"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "96,814,000",
            },
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "...",
            }
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "...",
            },
        }
    [





<strong>Example 2: Balance Sheet </strong>


<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/balancesheets
    ?key=YOUR-KEY
        &stock_ticker_symbol=aapl</a></p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
        },
        "output": {
            "total_assets": "323,888,000",
            "total_liabilities_net_minority_interest": "258,549,000"
            "total_equity_gross_minority_interest": "65,339,000"
            "total_capitalization": "164,006,000"
            "common_stock_equity": "65,339,000"
            "net_tangible_assets": "65,339,000"
            "working_capital": "38,321,000"
            "invested_capital": "177,775,000"
            "tangible_book_value": "65,339,000"
            "total_debt": "112,436,000"
            "net_debt": "74,420,000"
            "share_issued": "16,976,763",
            "ordinary_shares_number": "16,976,763"
        }
    [





<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/balancesheets
    ?key=YOUR-KEY
        &sector=technology
        &industry=consumer_electronics
        &income_statement=total_assets
        &year=2021</a></p>





    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "323,888,000",
            },
        "basics": {
            "name": "Microsoft Corporation",
            "stock_ticker_symbol": "MSFT"
            "isin_identifier": "US5949181045"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "333,779,000",
            },
        "basics": {
            "name": "Dell Technologies Inc",
            "stock_ticker_symbol": "DELL"
            "isin_identifier": "US24703L2025"
            "exchange": "NYSE"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "123,415,000",
            },
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "...",
            }
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_assets": "...",
            },
        }
    [


<strong>Example 3: Cash Flow Statements</strong>

<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/cashflows
    ?key=YOUR-KEY
        &stock_ticker_symbol=aapl</a></p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
        },
        "output": {
            "operating_cash_flow": "104,414,000",
            "investing_cash_flow": "-9,849,000"
            "financing_cash_flow": "-94,328,000"
            "end_cash_position": "35,276,000"
            "income_tax_paid_supplemental_data": "19,627,000"
            "interest_paid_supplemental_data": "2,597,000"
            "capital_expenditure": "-9,646,000"
            "issuance_of_capital_stock": "1,011,000"
            "issuance_of_debt": "22,370,000	"
            "repayment_of_debt": "-7,500,000"
            "repurchase_of_capital_stock": "-83,410,000",
            "free_cash_flow": "94,768,000"
        }
    [





<p><a href="https://tradefeeds.com/api-documentation/">https://tradefeeds.com/api/v1/balancesheets
    ?key=YOUR-KEY
        &sector=technology
        &industry=consumer_electronics
        &cash_flow=operating_cash_flow
        &year=2021</a></p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "104,414,000",
            },
        "basics": {
            "name": "Microsoft Corporation",
            "stock_ticker_symbol": "MSFT"
            "isin_identifier": "US5949181045"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "76,740,000",
            },
        "basics": {
            "name": "Dell Technologies Inc",
            "stock_ticker_symbol": "DELL"
            "isin_identifier": "US24703L2025"
            "exchange": "NYSE"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "14,441,000",
            },
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "...",
            }
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "...",
            },
        }
    [


<h2>Customer support</h2>

In case that you encounter a data issue or you want to have more features added to the API, please contact us at support@tradefeeds.com.
 
<h2>Legal</h2>

<p> The use of Tradefeeds proprietary data and API database is subject to the&nbsp;<a href="https://tradefeeds.com/terms-and-conditions-on-data/">Tradefeeds Terms &amp; Conditions.</a></p>

