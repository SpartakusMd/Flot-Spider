# Flot-Spider

This is a Radar / Spider chart plugin for jQuery [Flot](http://www.flotcharts.org) library.

# Options

        series: {
            spider: {
                active: true, // must be true to enable the spider
                show: false, 
                spiderSize: 0.8, // size compared to canvas
                lineWidth: 3, // width of legs
                lineStyle: "rgba(0,0,0,0.5)", // color of legs
                pointSize: 6, // size of dots at values
                scaleMode: "leg", // leg|all
                legMin: null, // specify min value
                legMax: null, // specify max value
				legValues: false, // show "axis" values
                connection: {width: 4}, // width of connecting lines
                highlight: {opacity: 0.5, mode: "point"},
                legs: {
			    	font: { family: "Times New Roman", size: 20 },
	                fillStyle: "Black",
	                legScaleMin: 0.95,
	                legScaleMax: 1.05,
	                legStartAngle: 0, // default is 3 o'clock position, -90 means first label is at the top
				    labelWidth: 0, // try to limit width of labels. 0 means no width and they will be on one line
				    labelSpace: 100, // distance from outer circle to center of label
                }
            }
        }



# Example

You can find an example on [jsfiddle.net](http://jsfiddle.net/SpartakusMd/peehncrg/)

# Credits
You can find the original version of this plugin on [jumflot.jumware.com](http://jumflot.jumware.com/examples/Experimental/spider.html)
