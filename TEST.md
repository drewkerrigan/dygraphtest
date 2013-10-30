<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="content-type" content="text/html; charset=UTF-8">
  <title> - jsFiddle demo</title>
  <script type='text/javascript' src="https://raw.github.com/drewkerrigan/dygraphtest/master/dygraph.js"></script>


<script type='text/javascript'>//<![CDATA[ 
window.addEvent('load', function() {
g = new Dygraph(document.getElementById("graph"),
                 // For possible data formats, see http://dygraphs.com/data.html
                 // The x-values could also be dates, e.g. "2012/03/15"
                 "X,Y,Z\n" +
                 "1,0,3\n" +
                 "2,2,6\n" +
                 "3,4,8\n" +
                 "4,6,9\n" +
                 "5,8,9\n" +
                 "6,10,8\n" +
                 "7,12,6\n" +
                 "8,14,3\n",
                 {
                     // options go here. See http://dygraphs.com/options.html
                     legend: 'always',
                     animatedZooms: true,
                     title: 'dygraphs chart template'
                 });
                 
});//]]>  

</script>


</head>
<body>
  <!-- You may set style: "width: ...; height: ..." to size the chart -->
<div id="graph"></div>
  
</body>


</html>

