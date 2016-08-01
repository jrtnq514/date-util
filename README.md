# date-util
Date formatter element/utility for your Polymer project.

##Site
http://jrtnq514.github.io/date-util/

##Install
With bower

`bower install date-util --save`

##Constructor
*Note: You may change the default format ("MM/dd/yyyy H:mm:ss.zzz") in the constructor for every usage of that `DateUtil()` instance .*

```js
var date = new DateUtil();
```
```js
var date = new DateUtil( <format> );
```
**format**

The format in which the the date string will be returned. Ex. `"MM/dd/yyyy H:mm:ss.zzz"` 

##Usage
*Note: You may use the date formatter element as an html tag or in javascript. For either, if no format is provided the default format ("MM/dd/yyyy H:mm:ss.zzz") will be used.*

###For use in html
*Note: This will display the formatted date in your html.*

**Using default format**
```html
<date-util></date-util>
```
**Using custom format**
```html
<date-util format=" <format> "></date-util>
```
###For use in javascript
**Using default format**
```js
var date = new DateUtil();
date.now();
```
**Using custom format for single instance**
```js
var date = new DateUtil();
date.now( <format> );
```

##Format 

####Patterns
  - **MM** - month
  - **dd** - day
  - **yyyy** - year(full)
  - **yy** - year(last 2)
  - **H** - hour
  - **mm** - minute
  - **ss** - second
  - **zzz** - millisecond
  - **Month** - month name
  - **Mon** - abbreviated month name
  - **Day** - day of the week
  
####Example Formats
* "MM/dd/yyyy" => 05/29/2015
* "H:mm:ss.zzz" => 11:48:34.130
* "Day dd of Month yyyy" => Friday 29 of May 2015
 

##Used In
[**log-util**](https://github.com/dylanstanfield/log-util) by [Dylan Stanfield](https://github.com/dylanstanfield)
