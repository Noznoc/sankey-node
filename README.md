# NODE D3 SANKEY WEB APP

This is template code for developing a d3.js sankey diagram web app.

## Installation

1) Clone the repo to your local computer
2) Go to the folder directory from the command line or terminal and enter `npm install` to install the dependencies
3) Once dependencies are installed, in `public/javascripts/socket.js` update the `socket` variable to have the correct IP. If you are unsure of your IP, in the command line or terminal, enter `ipconfig`
4) Enter `npm start` to run the app
5) Now that the app is running, in your browser enter `http://localhost:3010` or `http:[IP]:3010` to share externally

## Development

Currently the sankey visualization is generated from dummy data (seen in `sankey.json`). To populate the visualization with your data, simply replace the sankey.json with your own either by copying/pasting the JSON into `sankey.json`, or renaming/replacing your JSON file with sankey.json, or relinking `var data` in `app.js` to your data file.

If you make any changes to the server, you will have to reset the app by selecting `Ctrl + C` and then entering `npm start` again.