# HTML

<div class="html-table">

| Sl.no | Item name | Item-value | Item-description |
|:--:|:--:|:--:|:--|
| 1 | intial-scale | 1.0 | sets the default zoom level (1 -> 100%) |
| 2 | "meta (Name="description")" | "Random text" | defines description for the search engine |
| 3 | /script | "Java Script code" | Javascript code |
| 4 | "&nbsp" | "single space" | non-breaking-space |
| 5 | "/strong" | | <strong id="here-here">bolds the text</strong> |
| 6 | "/em" | | <em>italic text</em> |
| 7 | "/u" | | <u>underlined text</u> |
| 8 | "/strike" | | <strike>strike through text</strike> |
| 9 | "/ul" | "/li" | <ul><li>unordered-list</li><ul> |
| 10 | "/ol" | "/li" | <ol><li>ordered-list</li><ol> |
| 11 | "img" | src="" | <img src="https://cdn.newsapi.com.au/image/v1/6ca36c5256b97133b87bb3635de8930b" height=100px;> |
| 12 | "/video" | [autoplay, muted, controls] |     <video width="50%" controls><source src="assets/stop_jeans.mp4" type="video/mp4"></video>|
| 13 | "a" | href="" | <a href="#here-here">adds a url to the object</a>|
| 14 | "a target="""| _blank<br> _self<br> _parent<br> _top | blank= new tab<br> self= same area (default)<br> parent= parent frame<br> top= full body of the window|
| 15 | "a href="#" | "#name" | doesn't let the user to redirect to another webpage <br><br>checks if name is available in any id in the current web page and shifts to that|
| 16 | nowrap |  | keeps the text in a single line |
| 17 | table \<table\>|| creates a table|
| 18 | \<tr\> | \<\/tr\>| creates a new row inside the table |
| 19 | \<td\> | | holds data, which is put inside \<tr\> |
| 20 | background | image/video url | sets the background for the given item |
| 21 | \<form\> | \<\/form\> | contains the form <br> - name = "nameofform" <br> - action = "submit.php" (url where the info is sent to) <br> - method="post/get" |
| 22 | Get | method="get" | - requests method from a resource <br> - name& value pairs are sent in the url string <br> - can be cached/ in history |
| 23 | Post | method="post" | - submits data to be processed <br> - sends name/value in http body <br> - cannot be cached/ in history |
| 24 | \<input\/\> | | - takes input from the user |
| 25 | \<input **type** \/\> | "text", "number", "email" ... | |
| 26 | \<input **name** \/\> | "name of the feild" ... | - important as is used to identify in the script using the name |
| 27 | \<input **maxlength** \/\> | "50" ... | limits the input upto given value |


</div>























<style>
    .html-table {
        font-family : Monospace;
        }
    .html-table th{
        background : gray;
        font-size: 20px;
        color: black;
        
    }
    .html-table tr:nth-child(1) {background: gold; color:black; font-weight:600;}
    .html-table tr:nth-child(4) {background: gold; color:black; font-weight:600;}
    .html-table tr:nth-child(14) {background: gold; color:black; font-weight:600;}
    .html-table tr:nth-child(18) {background: gold; color:black; font-weight:600;}
    .html-table tr:nth-child(19) {background: gold; color:black; font-weight:600;}
    *{
        scroll-behaviour: auto;
    }
</style>
