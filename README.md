## Developer Setup

- In the Squarespace site, make sure developer mode is enabled in advanced settings
- *npm install -g @squarespace/server*
- *squarespace-server https://antievictionmap.squarespace.com*
[it uses the current directory to run dev server so make sure you're inside the template repo]
- In your browser, go to *localhost:9000*
- (Changes to the template will live reload)
- To save changes, git commit them and git push to this repository as a remote (https://github.com/antievictionmappingproject/squarespace)
- To deploy to live site, git push to the remote https://antievictionmap.squarespace.com/template.git (will need Squarespace credentials)
