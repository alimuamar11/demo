## Try it

[https://my-json-server.typicode.com/typicode/demo](https://my-json-server.typicode.com/typicode/demo)

## Use your own data

Fork it and change `db.json` values or create a repo with a `db.json` file.

##https://medium.com/@royanimesh2211
Step 1:

Create a folder with any name you want. I named it FakeJSONPlaceholder.

Step 2:

npm init
Step 3:
Now we have a package.json file inside the folder.
Time to Install the JSON server now. Write to the terminal:
npm install --save json-server
Step 4:
Create a new file & name it db.json
Put the JSON data you want to retrieve in your apps. I am pasting this data in db.json
Step 5:

In package.json replace the existing value of key name: “scripts” to:

"scripts": {"json:server": "json-server --watch db.json"},

Step 6:

Time to run the server. Write the command:

npm run json:server

The server should start on http://localhost:3000
