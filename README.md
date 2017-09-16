# Setup

Assumes Polymer CLI, nom and node.js

1. Clone the repo

```
git clone bibliotech-form
```
2. Install dependencies
```
npm install -g bower
```
3. Run the server
```
polymer serve
```
4. View the form at http://127.0.0.1:8000/form in your browser

5. View success submits in the Network tab. Arguments will be visible in the hhtpbin response. Invalid forms will not be sent up  as shown in the network tab (I didn't get round to error handling :( )
