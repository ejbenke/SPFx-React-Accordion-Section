## SPFx Collapsible Accordion Section web part

* Adds a collapsible accordion to a page.
* Allows user to select a list within their site from a property panel dropdown to populate the accordion structure (list must have a Title column and Content column).
* Can be deployed in a Teams tab in addition to Office 365 SharePoint site. See current [Microsoft documentation](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/using-web-part-as-ms-teams-tab) on how to deploy to Teams.

## SharePoint Framework Version 
1.8.2

## Applies to

* [SharePoint Framework](https:/dev.office.com/sharepoint)
* [Office 365 tenant](https://dev.office.com/sharepoint/docs/spfx/set-up-your-development-environment)

## Solution

Solution|Author(s)
--------|---------
SPFx Collapsible Accordion Section|Erik Benke


## Version history

Version|Date|Comments
-------|----|--------
1.0|August 14, 2019|Initial release
1.1|September 19, 2019|Minor updates, adding to Github


### Building the code

- Clone or download this repository
- Run in command line:
  - `npm install` to install the npm dependencies
  - `gulp serve` to display in Developer Workbench (recommend using your tenant workbench so you can test with real lists within your site)
- To package and deploy:
  - Use `gulp bundle --ship` & `gulp package-solution --ship`
  - Add the .sppkg to your SharePoint App Catalog

