## Kendo Grid filter JSON to [Sequelize](http://docs.sequelizejs.com/en/latest/) query condition JSON converter

## Installing
	$ npm install kendo-grid-filter-sequelize-converter
 
## Usage
```javascript
 var Filtering = require('kendo-grid-filter-sequelize-converter');
 
 var f = new Filtering();
 var result = f.resolveFilter(req.query.filter);
 ```
