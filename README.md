# javascript-while-loop
JavaScript while loop statement
<body>
		<p id="demo"></p>
	<script>
		var i=1;
		var sum=0;
		while(i<=50){
         if(i%3==0 && i%5==0){
         	sum= sum+i;
         }
			i= i+1;
		}
		document.write(sum);
		document.write("<h1>End</h1>");
     </script>
	</body>
