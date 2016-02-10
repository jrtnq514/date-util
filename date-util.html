<link rel="import"
      href="../polymer/polymer.html">
<!-- ----------------------
  Formats
  MM - month
  dd - day
  yyyy - year(full)
  yy - year(last 2)
  H - hour
  mm - minute
  ss - second
  zzz - millisecond
  
  Month - month name
  Mon - abbreviated month name
  Day - day of the week
  
---------------------- -->

<dom-module id="date-util">
	<style>
		:host {
			display: inline-block;
		}
		
		
	</style>

	<template>
		<span>{{dateDisplayed}}</span>
	</template>

</dom-module>

<script>
(function() {
    function getMonthName(monthNumber) {
        switch(monthNumber) {
            case 1:
                return "January";
            case 2:
                return "February";
            case 3:
                return "March";
            case 4:
                return "April";
            case 5:
                return "May";
            case 6:
                return "June";
            case 7:
                return "July";
            case 8:
                return "August";
            case 9:
                return "September";
            case 10:
                return "October";
            case 11:
                return "November";
            case 12:
                return "December";
        }
    }
    
    function getAbbrvMonthName(monthNumber) {
        switch(monthNumber) {
            case 1:
                return "Jan";
            case 2:
                return "Feb";
            case 3:
                return "Mar";
            case 4:
                return "Apr";
            case 5:
                return "May";
            case 6:
                return "June";
            case 7:
                return "July";
            case 8:
                return "Aug";
            case 9:
                return "Sept";
            case 10:
                return "Oct";
            case 11:
                return "Nov";
            case 12:
                return "Dec";
        }
    }
    
    function getDayOfWeek(dayNumber) {
        switch(dayNumber) {
            case 0:
                return "Sunday";
            case 1:
                return "Monday";
            case 2:
                return "Tuesday";
            case 3:
                return "Wednesday";
            case 4:
                return "Thursday";
            case 5:
                return "Friday";
            case 6:
                return "Saturday";
        }
    }

    function buildDate(format, date) {
    
        format = format.replace(/MM/g, ("0" + (date.getMonth()+1)).slice(-2));
        format = format.replace(/dd/g, ("0" + date.getDate()).slice(-2));
        format = format.replace(/yyyy/g, date.getFullYear());
        format = format.replace(/yy/g, date.getFullYear().toString().slice(-2));
        format = format.replace(/H/g, ("0" + date.getHours()).slice(-2));
        format = format.replace(/mm/g, ("0" + date.getMinutes()).slice(-2));
        format = format.replace(/ss/g, ("0" + date.getSeconds()).slice(-2));
        format = format.replace(/zzz/g, ("0" + "00" + date.getMilliseconds()).slice(-3));
        
        format = format.replace(/Month/g, getMonthName(date.getMonth()+1));
        format = format.replace(/Mon/g, getAbbrvMonthName(date.getMonth()+1));
        format = format.replace(/Day/g, getDayOfWeek(date.getDay()));
      console.log(format);
        return format;
    }

  DateUtil = Polymer({
    is: "date-util",
    
    properties: {
      format: {
        type: String,
        value: "MM/dd/yy H:mm:ss.zzz"
      },
      
      date : {
      
        type : Date,
        value: new Date()
      
      },
      
      dateDisplayed : {
      
        type : String,
        computed : 'computeDateDisplayed(format, date)'
      }
      
    },
    
    factoryImpl: function(format, date) {
      if(format != undefined && format != "") {
        this.format = newFormat;
      }
      
      if(date != undefined || date != null) {
        this.date=date;
      }
    },
    
    now: function(format) {
     
        return this.get(format,new Date());
    },
    
    get: function(format, date) {
    
      if(format == undefined || format == "" || format == null) {
        return buildDate(this.format, date);
      }else{
      return buildDate(format, date);
      }
    
    },
    
    computeDateDisplayed: function(format, date){
         return this.get(format,date);
        
    
    }
    
  });
})();
</script>