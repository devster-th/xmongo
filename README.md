# xmongo
Easier working with mongodb

This thing help working with mongodb easier, like you can do:

//in your mainProgram.js
const XD = require('./xmongo3.js')

//get data from mongodb
let data = await XD.$({find:{country:/thailand/i}, from:'xdb.countries'})

so it's more like natural language, unlike the mongodb's headache style of command especially when you have little complex of the thing.

no license.
The doc is in the file xmongo-doc.html already uploaded to this repository.

