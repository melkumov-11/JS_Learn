# JS_Learn
Сумма через замыкание

<meta charset="utf-8">
<script>
	
    function sum(a) {
	return function(b) {
	    var sum = +(a + b);
	    alert(sum);
        }
    }

    sum(1)(2);
    sum(5)(-1);

</script>
