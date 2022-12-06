# jquery-ussing-css
<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script>
$(document).ready(function(){
$("p").on({
mouseenter: function(){
$(this).css("background-color","lightgray");
},
mouseleave: function(){
$(this).css("background-color","lightblue");
},
click: function(){
$(this).css("background-color","yellow");
}
});
});
</script>
</head>
<body>

<p> hello world this is a query using css</p>

</body>
</html>
