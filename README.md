# date-util
Date formatter element for Polymer

##Usage
*Note: You may use the date formatter element as an html tag or in javascript. For either, if no format is provided the default format ("MM/dd/yyyy H:mm:ss.zzz") will be used.*

####In html
Using default format
```html
<date-util></date-util>
```
Using custom format
```html
<date-util format="<format>"></date-util>
```
####In javascript
Using default format
```js
var date = new DateUtil();
date.now();
```
Using custom format
```js
var date = new DateUtil();
date.now(<format>);
```

####Format Patterns
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
 

####Used In
[**log-util**](https://github.com/dylanstanfield/log-util) by [Dylan Stanfield](https://github.com/dylanstanfield)
