markdown
# Latest Mutual Fund NAV MCP Server

Welcome to the `latest-mutual-fund-nav` MCP server. This server is designed to provide real-time access to the latest Net Asset Value (NAV) data for mutual funds in India. The information is dynamically updated, ensuring you have access to the most current data available from the Association of Mutual Funds of India (AMFI).

## Overview

This MCP server offers a comprehensive solution for accessing NAV data for all mutual funds in India. It maintains an up-to-date database that reflects the latest changes as soon as they are published by AMFI. Additionally, it provides access to historical NAV data, allowing users to analyze trends and make informed decisions.

### Key Features

- **Real-time NAV Updates**: Access the latest NAV information as soon as it is updated by AMFI.
- **Historical NAV Data**: Retrieve NAV information for previous dates to analyze performance over time.
- **Comprehensive Mutual Fund Data**: Access a wide range of mutual fund details through master data retrieval.

## Tools and Functions

The `latest-mutual-fund-nav` MCP server offers several tools for interacting with NAV data. Below is a list of available tools and their functions:

1. **Latest NAV Tool**
   - **Function Name**: `latest`
   - **Description**: Fetch the latest NAV data for mutual funds.
   - **Parameters**:
     - `Mutual_Fund_Family` (optional): Define the mutual fund family.
     - `Scheme_Type` (optional): Define the scheme type (e.g., Open, Close).
     - `Scheme_Category` (optional): Define the scheme category.
     - `Scheme_Code` (optional): Define the scheme code. Supports multiple comma-separated values.
     - `ISIN` (optional): Define the ISIN. Supports multiple comma-separated values.

2. **Historic NAV Tool**
   - **Function Name**: `historic`
   - **Description**: Fetch historical NAV data.
   - **Parameters**:
     - `Mutual_Fund_Family` (optional): Define the mutual fund family.
     - `Scheme_Type` (optional): Define the scheme type (e.g., Open, Close, Interval).
     - `Scheme_Category` (optional): Define the scheme category.
     - `Scheme_Code` (optional): Define the scheme code. Supports multiple comma-separated values.
     - `Date` (*): Specify the date in the format yyyy-mm-dd.

3. **Master Data Tool**
   - **Function Name**: `master`
   - **Description**: Fetch master data for mutual funds.
   - **Parameters**:
     - `AMC_Code` (optional): Define the mutual fund family.
     - `RTA_Agent_Code` (optional): Define the scheme type (e.g., CAMS, KARVY).
     - `ISIN` (optional): Define the scheme category.
     - `Scheme_Type` (optional): Define the scheme type.

## Conclusion

The `latest-mutual-fund-nav` MCP server is a powerful tool for individuals and organizations looking to stay updated with the latest mutual fund NAV information in India. By leveraging the real-time and historical data capabilities, users can make more informed investment decisions and gain deeper insights into mutual fund performance.

Feel free to explore the various tools and functions this server offers to optimize your mutual fund data retrieval experience.