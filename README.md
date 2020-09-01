# Build@Aspire

## Welcome
Welcome to Build@Aspire! Aspire is a powerful budgeting spreadsheet built on the foundation of Google Sheets. Aspire has thousands of users and serves the broad market of users all over the world who want a simple and full-featured budgeting tool. Even though Aspire has many built in features and functions, there are countless opportunities to extend these basic features with custom views and extensions. Build@Aspire is the official program through which Aspire can be extended and posted for the community at large to consume.

## How can I extend Aspire?
Extending Aspire is easy. In the Aspire Budgeting Docs, there's an entire section dedicated to the various ways in which you can reference Aspire's data. These references are called Named Ranges. They allow a value or range to be accessed without the consumer of the value(s) needing to worry about where the data is stored. This is useful because, as Aspire grows and changes, cells and locations of data may be relocated in the Aspire spreadsheet. Having these references (Named Ranges) removes the builder's concern of needing to update code and formulas with any new data locations. This allows you as the build to be totally focused on building great extensions and spreadsheets.

## Google Apps Script Documentation
You can learn more about the APIs available here in [Google's documentation](https://developers.google.com/apps-script/reference/spreadsheet)

## Build@Aspire classifications
Aspire can be extended in many ways. There are 3 classifications of Build@Aspire extensions. These are:
- Spreadsheets
- Mobile apps
- CLI tools & scripts

### Spreadsheets
Spreadsheets are the easiest way to extend Aspire. A few examples may include loan calculators, regional tax tools, or new report types. To be included in the Build@Aspire repository, there are a few guidelines that need to be followed. These guidelines are pretty minimal, but are in place to ensure the best user experience possible for users of Aspire and tools from the Build@Aspire repository.

Get the spreadsheet starter template.

All Build@Aspire spreadsheets should:
- Adhere to the Aspire Budgeting color palette
- Have a clear and concise UI with well described and intuitive controls
- Instructions for how to copy your spreadsheet into Aspire Budgeting
- Have links to:
  - The Aspire Budgeting website
  - The Aspire Budgeting subreddit
  - Your personal website, your Twitter page, etc.
- Include a `Getting Started` tab that contains:
  - An overview of what your spreadsheet does
  - How to use your spreadsheet
  - Contact information (Reddit username preffered) for the developer if users have a question or feedback
  - Screenshots of your spreadsheet in action
  
### Mobile apps
Mobile apps are another category of Aspire extensions. These can range from having simple functions like viewing balances to more complex functions like adding transactions or viewing reports.

If you're building a mobile app for Aspire, it should:
- Adhere to the Aspire Budgeting color palette
- Have a Github project or other proejct landing page with clear usage instructions
- Have an issue tracker
- Have a privacy policy
- Have links to:
  - The Aspire Budgeting website
  - The Aspire Budgeting subreddit
  - Your personal website, your Twitter page, etc.

### CLI tools & scripts
Lastly, CLI tools may exist to accomlish tasks like data transforms, data backups, etc.

If you're building a CLI tool for Aspire, it should:
- Have a Github project or other proejct landing page with clear usage instructions
- Have an issue tracker
- Have a privacy policy
- Have links to:
  - The Aspire Budgeting website
  - The Aspire Budgeting subreddit
  - Your personal website, your Twitter page, etc.

## Request to be added to Build@Aspire
If you would like your project to be added to the Build@Aspire repository, you can create an issue in this repository with the following information:
- Your project's name
- A brief description (in English, no more than 500 characters).
- The link to your project's landing page
- The classification of your project (must be `SPREADSHEET`, `MOBILE_APP`, or `CLI_TOOL`).
