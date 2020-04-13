
# Ulbora CMS Template Designer
UlboraCMS is a self-contained CMS (no database needed) written in Golang. It uses a JSON datastore with content saved in both json files and in memory. You can download and upload a single binary backup file containing content, images, and templates as needed.


## Templates

You can build multiple templates with Ulbora CMS and switch between the templates through the administration screen. 

Start the designer with the following command:
./main

To design a new template, navigate to the static/templates folder and create a new folder for the template. Currently, cleanblog and creative are the only two templates listed in the templates folder. 

To get started quickly, you can do the following:

  * Copy one of the existing templates and rename it.
  * Navigate to the data/templateStore folder and copy a JSON file and name it to match the new template name
  * Open the JSON file that you just created and change the name attribute to match the name of the template
  * From the Admin screen under the template tab, switch to the new template


Now you can create the template and view your changes as you work.
After making changes to any HTML file, stop and start the designer as follows:
  * Stop: Ctrl+C
  * Start: ./main



[MIT](LICENSE)

