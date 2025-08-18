# Class 6

## 🛠️ Data Structures

Structured data types in your code
  * [Arrays](https://www.youtube.com/watch?v=am6e1U2BHkA&vl=en)
  * Dictionaries/Hashes ([Objects](https://www.youtube.com/watch?v=_5jdE6RKxVk) in .js, [HashMap](https://processing.org/examples/hashmapclass.html) in Java)

Loading data payloads from external files or APIs
  * Text file
    * `loadStrings()` - [p5 example](https://p5js.org/reference/p5/loadStrings)
  * [CSV](https://www.howtogeek.com/348960/what-is-a-csv-file-and-how-do-i-open-it/) (spreadsheet/tabular data)
    * `loadTable()` - [p5 example](https://p5js.org/reference/p5/loadTable)
  * [JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
    * [json validator](https://jsonlint.com/)
    * `loadJSON()` - [p5 example](https://p5js.org/reference/p5/loadJSON)
  * [XML](https://www.sitepoint.com/really-good-introduction-xml/)
    * `loadXML()` - [p5 example](https://p5js.org/reference/p5/loadXML)

## 🛠️ APIs

* "[WTF is an API?](https://maggieappleton.com/api/)"
* Load some data!
  * `loadJSON()` [demo](https://editor.p5js.org/cacheflowe/sketches/aHrrTAQFw)
  * vanilla `fetch()` [demo](https://editor.p5js.org/cacheflowe/sketches/FTI18-cxJ)
* Example of swapping an API:
  * [q5.js](https://github.com/LingDong-/q5xjs)
  * [q5 Example](https://editor.p5js.org/cacheflowe/sketches/IRhjHom9p)
* How does code talk to other code?
  * [Example live-code](https://editor.p5js.org/cacheflowe/sketches/488Fdh1O1) w/collision detection

## 🛠️ Databases

* Databases are searchable data structures 
* Relational & queryable databases allow for large sets of searchable data
  * Pro: More powerful and reliable than a data file
  * Pro: Hosted in the cloud, a db can share data between users
  * Con: More difficult to set up and work with
  * Some different types of databases: SQL, Mongo, GraphQL
* What's the best tool for the job?
  * [Or which tool is most in fashion?](../images/databases-relational-or-not.png)
* Data search [example](https://editor.p5js.org/cacheflowe/sketches/GOzYzYViFF)

## 🛠️ Data Visualization

* Types of data viz
  * [Traditional visual components](https://datavizproject.com/)
  * [Storytelling](https://www.youtube.com/watch?v=sFIDCtRX_-o)
  * [Art](https://www.youtube.com/watch?v=UxQDG6WQT5s)
* Data sources
  * [awesome-json-datasets](https://github.com/jdorfman/awesome-json-datasets)
  * [public-apis](https://github.com/public-apis/public-apis)
  * [freepublicapis.com](https://www.freepublicapis.com/)
  * Topic-specific:
    * [OpenWeather](https://openweathermap.org/api)
    * [Spacekit](https://typpo.github.io/spacekit/)
* Data Viz drawing tools
  * [Make your own!](https://vimeo.com/showcase/2573675) - This is a Processing-specific series, but would port easily to p5js
  * [D3](https://d3js.org/)
  * [chart.js](https://www.chartjs.org/docs/latest/samples/information.html)
  * [Vizzu](https://lib.vizzuhq.com/latest/examples/presets/)
  * [deck.gl](https://deck.gl/)
  * Other [data viz libraries](https://medium.com/nightingale/navigating-the-wide-world-of-web-based-data-visualization-libraries-798ea9f536e7)
    * [More libraries](../images/chart-libraries.webp)
    * https://roughjs.com/
    * https://semiotic.nteract.io/
    * http://dimplejs.org/
    * https://vega.github.io/vega/
    * https://github.com/antvis/G2
    * https://plotly.com/javascript/

## 📝 Homework:

Watch:

* [The Pudding](https://pudding.cool/)
* [Daniel Shiffman: Introduction to Data and APIs in JavaScript](https://www.youtube.com/watch?v=rJaXOFfwGVw)
* [Giorgia Lupi: How we can find ourselves in data](https://www.youtube.com/watch?v=sFIDCtRX_-o)
* [Aaron Koblin: From Data to Digital Art](https://www.youtube.com/watch?v=-SETcTrdcU4)
* [Data Becomes Art in Immersive Visualizations](https://www.youtube.com/watch?v=99gMbK2QCKE)
* [Refik Anadol: Art in the age of machine intelligence](https://www.youtube.com/watch?v=UxQDG6WQT5s)

**Build a data visualization**

* Types of visuals to consider
  * A chart
  * An interactive visual representation
  * A storytelling device
  * An abstract interpretation of the data
* Data sources
  * Handcrafted/hard-coded arrays, objects
  * Loaded data files (json, csv, xml, text)
  * API requests
* Inspiration
  * [Nadieh Bremer](https://www.visualcinnamon.com/)
  * [Nikcy Case](https://ncase.me/)
  * [Shirley Wu](https://shirleywu.studio/)
  * [Nicholas Felton: Annual Reports](http://feltron.com/FAR08.html)
  * [FlowingData](https://flowingdata.com/)
* Steps
  * Find or create some interesting data
  * Load your data source into your environment
  * Draw something based on your data

## 📋 Review code

* Present your generators
