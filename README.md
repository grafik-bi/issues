## GRAFIK issues

This is a public issue tracker for GRAFIK, http://grafik.atlassian.net/.

GRAFIK is a locally run web-server that connects to your data sources and turns SQL queries into interactive tables and charts.
GRAFIK is designed as a good Unix tool: small but powerful, runs from command line and is controlled by text files, not GUI.
Its main features are:

- **Ease of use.** GRAFIK is a single executable with no dependencies that runs on your local machine. You don't need to publish your data to the cloud or let outsiders access your private network.

- **Simple syntax.** Every page is a Markdown file extended with SQL queries and formatting instructions to get charts and interactivity. You can put these files under version control, perform search/replace and do everything else you can do with ordinary text files, retaining full control over the end result.

- **Multi-platform.** GRAFIK runs equally well on Windows, Linux and Mac and can connect to a variety of data sources. You can easily combine data from multiple data sources on the same page.

- **Speed.** GRAFIK is a compiled Go code that can serve hundreds of users on a single machine. It also caches results of all database queries (and refreshes them periodically in the background) so that even complex dashboards with sophisticated analytics stay responsive.

- **Cost.** GRAFIK is free for personal, educational and non-commercial use. While we are still figuring out the business models, we don't like to charge you based on the number of users you have, or the number of queries you run, or the amount of data you store in your database. What you pay should only depend on how many copies of GRAFIK you need to run and on how many CPUs, and nothing else.

Feel free to create new issues to report bugs, suggest features or ask questions - GRAFIK developers will carefully review all the submissions.
