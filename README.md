# SKJQueryFramework
Created my own componenets such as accordian,grid,etc which can be used in a way similar to JQuery resources.
You can use include my JS file in your application and can make use of my resources.
Eg - If you want to send HTTP Request then you can use - 

$$$.ajax({
"url": "servletOne",
"methodType": "GET",
"success": function(responseData){
var designations=JSON.parse(responseData){
},
"failure": function(){
alert('some problem exist');
}
});
