Shrink
======
An attempt at behavior modification through monitoring and statistics. Based loosely on [behavior modification theory](http://en.wikipedia.org/wiki/Behavior_modification_therapy) and other [behavioral change theories](http://en.wikipedia.org/wiki/Behavioral_change_theories). __This is not guaranteed to help anyone, it is experimental software. USE AT YOUR OWN RISK__.

To Do
-----
- Setup local MySQL server
- Create MySQL subproject
- Create initial schema file
  - Users
     - id | alias | created | updated
  - Events
     - id | user_id | timestamp | log
- Create a dummy data script
- Create node subproject
- Add packages.json file for dependencies
  - [Async](https://github.com/caolan/async)
  - [Sequelize](http://sequelizejs.com/#installation)
  - [Express](http://expressjs.com/)
- Create a node script that connects to MySQL
- Create ORM models for MySQL tables
- Create and expose the graph API
  - `/:alias/:action?`
  - `logs?page` => `[ {date, log}... ]`
  - `hits?interval&range` => `[ {time, hits}... ]`
- Create nginx subproject
- Import dependencies
  - [jQuery](http://docs.jquery.com/Downloading_jQuery)
  - [Normalize.css](http://necolas.github.com/normalize.css)
  - [Modernizr](http://www.modernizr.com/)
  - [jQuery.tmpl](https://github.com/jquery/jquery-tmpl)
  - [Date.js](http://www.datejs.com/)
  - [Spin.js](http://fgnass.github.com/spin.js/)
  - [HighCharts](http://www.highcharts.com/documentation/how-to-use)
- Create index.html
  - Container for logs
  - Container for graph
- Create log template
- Implement log logic
- Implement graph logic
- Create dotcloud.yml file
- Modify the mysql project to work in production
- Modify the node project to work in production
- Modify the nginx project to work in production
- Deploy to production
- Purchase and bind domain names

Backlog
-------
- More themes
- Password protection
- Responsive layout
- AT&T App Store
  - <http://9to5mac.com/2012/01/09/att-unveils-own-api-for-html5-web-apps> 
