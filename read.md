"jeykll build --watch" in root folder generates the sites files in the /_site directory, and will automatically be regenerated when changes are made to the files in root (assuming that the "--watch" command was used, and autoregeneration was not canceled) 

"jeykll serve" will run the files in /_site on a local server accesible at https://localhost:4000 by default

Do not place files in the /_site directory, they will be cleared out the next time jeykll generates files there

:-) 