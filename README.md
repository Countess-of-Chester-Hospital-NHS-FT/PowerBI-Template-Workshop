# PowerBI-Template-Workshop
Resources for PowerBI template workshop for external users

We have developed a template to:
* Save us time when developing new KPI dashboards
* Ensure all our dashboards have a similar look and feel to enhance usability
* Enhance our ability to work collaboratively on dashboards
* Facilitate all metrics being available in SPC charts as per the Making Data Count agenda
* Be both as flexible and as compact as possible (allow many different metrics/timescales/comparisons to be made with the minimum number of pages/charts)

### Contents
* Power BI Template Populated Unfinished.pbix - This is the file to download for the code-along in the workshop.
* Power BI Template Populated Finished.pbix - This is a completed example with a bunch of measures added.
* Power BI Template.pbit - This is a template file containing no data.
* Note this repo isn't properly git version controlled - just contains the template and populated example dashboards for dissemination purposes.

### Using the template
* We are very happy for others to adapt our template for their needs - just download the .pbit or .pbix files
* Open the file and replace the fact table and dimension tables to your local data (we recommend leaving the calendar table as it is).
* The first 3 tabs of the template are a user guide for how to get started, we recommend following this guide
* If you have found this useful, please do let us know via the Discussions tab 🙂
* If you discover any issues or bugs please raise as an Issue or in Discussions

### Data
The example dashboards and csvs / zips contain fake ED attendance data generated using the Python Faker package. They have no relationship to our real data. No real patient data is contained in this repo. Feel free to use or share this data to populate your own examples or in your own training sessions (although be aware that it will not accurately represent the relationships, trends and patterns seen in real ED data).

### Acknowledgements
* This template makes use of the [SPC visual](https://github.com/AUS-DOH-Safety-and-Quality/PowerBI-SPC) developed by Western Australia Department of Health
* The template was primarily developed by [Patrick Devaney](https://github.com/paddy-devan)
* This template makes use of the [Deneb visual](https://github.com/PBI-David/Deneb-Showcase) - this allows you to use code to make any visual you like for free, that will also integrate with native powerBI fetaures like filters.

