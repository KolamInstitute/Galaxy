An HTML5 Framework for Knowledge Database Visualization based on Geographic coordinates - Community Edition

> This project is intended to provide a dedicated template for open source GIS mapping solution. 
> It is based on Leaflet.js, a lightweight library and its plugins. Just add this code to your HTML5 document header:

```html
    <link rel="stylesheet" type="text/css" href="app/galaxy-ui.css" />
    <link rel="stylesheet" type="text/css" href="app/galaxy-map.css" />
```

```html
    <script type="text/javascript" src="app/galaxy-core.js"></script>
    <script type="text/javascript" src="app/galaxy-conf.js"></script>
    <script type="text/javascript" src="app/galaxy-mod.js"></script>
```

***
![gowiki](http://www.kolam-institute.org/images/galaxy1logo.jpg)


![gowiki](http://www.vpul.upenn.edu/gic/images/arrow2.gif)   Documentation: https://github.com/KolamInstitute/Galaxy/wiki


====================================================


| Packages      | Type         | Usage  | Deploy |
| ------------- |:-------------:| -----:|-----:|
| Core app      | JS | Touch | YES ![check](http://www.digium.com/sites/digium/files/icon-green-check.png)|
| UI Design    | CSS      |   Theme | YES ![check](http://www.digium.com/sites/digium/files/icon-green-check.png)|
| Data test | JSON      |    Test | YES ![check](http://www.digium.com/sites/digium/files/icon-green-check.png)|



### Browsers Tested ###
Internet Explorer 6-8, Firefox 3-3.6, Safari 3-4, Chrome 3-5, Opera 9.6-10.5


====================================================

THIS DOCUMENTATION IS IN PROGRESS !!!
* * *
[**DATA STRUCTURE**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**LAYERING**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**STORAGE**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**CORE**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**UI**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**MODULES**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan)

![gowiki](http://www.vpul.upenn.edu/gic/images/arrow2.gif)   Demo app 0.6: http://www.kolam-institute.org/dev/package%20061/index.html

![gowiki](http://www.vpul.upenn.edu/gic/images/arrow2.gif)   Demo app 0.8: http://www.kolam-institute.org/galaxy/map.html

![gowiki](http://www.vpul.upenn.edu/gic/images/arrow2.gif)   Demo app 0.9: Coming soon !
* * *
**Goals (V1):**
* **Data vizualisation**: JSON/CSV ([See more details](https://github.com/KolamInstitute/Galaxy-/wiki/GeoJson-specifications))
* **Views**: Map/table/charts/timeline
* **Screens**: desktop/tablet/smartphone
* **Templates**: CSS themes and iconset

**Core Dependencies:**
* `Leaflet.js` >>> https://github.com/Leaflet/Leaflet
* `Recline.js` >>> https://github.com/okfn/recline
* `D3.js` >>> https://github.com/mbostock/d3

**UI Dependencies:**
* `Jquery.js` >>> https://github.com/jquery/jquery
* `Jquery Mobile.js` >>> https://github.com/jquery/jquery-mobile

**Notes:** 
At the actual stage of development, we have only integrate Leaflet into a full html5 user inteface + some small JS code to manage contents. We are using Recline to view dataset from directories and we have tested D3 for its impressive capabilities...

**Validator** 
`Checked` ![check](http://www.digium.com/sites/digium/files/icon-green-check.png)
`Pending` ![check](http://i212.photobucket.com/albums/cc118/gollum-greg/icons/icon_redX.png)

Development Focus (Level 1-3)
-------------------------
<table>
    <thead>
        <tr>
            <th>Level</th>
            <th>Title</th>
            <th>Sources</th>
            <th>Tested</th>
            <th>Status</th>
            <th>Demo</th>
            <th>Comments</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Map Engine</td>
            <td>Leaflet.js</td>
            <td>Yes</td>
            <td>0.4.5</td>
            <td><a href="#" target="_blank">Run</a></td>
            <td>Leaflet is a great lib !</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Map Plugins Repo.</td>
            <td>plugins.js</td>
            <td>Yes</td>
            <td>0.4.5</td>
            <td><a href="http://archfirst.org/examples/mobile-grid-evaluation/no-framework-html-table" target="_blank">Run</a></td>
            <td></td>
        </tr>
        <tr>
            <td>3</td>
            <td>Html5 UI</td>
            <td>ui.css</td>
            <td>0.9</td>
            <td>Done</td>
            <td><a href="http://archfirst.org/examples/mobile-grid-evaluation/no-framework-html-table-iscroll" target="_blank">Run</a></td>
            <td>Can be replaced soon by Jquery Mobile</td>
        </tr>
        </tr>
    </tbody>
</table>



***
