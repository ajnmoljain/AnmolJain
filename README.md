# SpaceECE NGO Data Analysis Project

This repository contains the data and Power BI visualizations for SpaceECE NGO, focusing on [briefly state the focus of your data, e.g., child development, community outreach, etc.]. Data is collected through Google Forms, processed using Google Apps Script, and visualized in Power BI.

## Project Overview

This project aims to [state the project's goal, e.g., track child development milestones, analyze community needs, etc.]. We use a streamlined data pipeline to collect, process, and visualize data efficiently:

1.  **Data Collection:** Google Forms are used to collect data from [explain who is providing the data, e.g., parents, community members, etc.].
2.  **Data Processing:** Google Apps Script automates the transfer of data from Google Forms to a Google Sheet (acting as our Excel equivalent). A trigger function ensures this transfer happens automatically upon form submission.
3.  **Data Visualization:** The processed data in the Google Sheet is then used to create interactive dashboards and reports in Power BI.

## Data Collection (Google Forms)

[Optional: If you can share a sanitized example or description of your Google Form, do so here. For example:]

*   The Google Form collects information on [list key data points, e.g., child's age, developmental milestones, family background, etc.].
*   [Mention any data validation or constraints used in the form.]

## Data Processing (Google Apps Script)

The following Google Apps Script functions are used:

*   `onFormSubmit(e)`: This trigger function is activated when a new form response is submitted. It retrieves the new data and appends it to the designated Google Sheet.
*   [Optional: If you have other custom functions, describe them here.]

[Optional: You can include a snippet of your Apps Script code here, but be mindful of sensitive information. A high-level explanation is often sufficient.]

Example (Conceptual):

```javascript
function onFormSubmit(e) {
  // Get the form response
  // Get the spreadsheet
  // Append the new data to the spreadsheet
}
