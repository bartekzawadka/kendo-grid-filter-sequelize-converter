# Kendo Grid filter JSON to [[http://docs.sequelizejs.com/en/latest/|Sequelize]] query condition JSON

## Installing
 npm install kendo-grid-filter-sequelize-converter
 
## Usage
 var Filtering = require('kendo-grid-filter-sequelize-converter');
 
 var f = new Filtering();
 var result = f.resolveFilter(req.query.filter);
