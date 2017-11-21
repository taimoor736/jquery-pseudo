# jquery-pseudo
A simple jquery extension for managing pseudo class using jQuery css function.

## Dependency.
1. Jquery

``` html
<script src="js/jquery.js"></script>
<script src="js/pseudo.js"></script>
```

``` html
<script>
$(document).bind('ready',function(){
    
    $('#heading:after').css('color','red');
    
});
</script>
```
