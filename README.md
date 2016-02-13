IncrementalNumber

IncrementalNumber is a JQuery library for anyone who wants an Incremental animation of a number.

How to use

First you have to add the script incrementalNumber.js to your code. 
Next, simply add the class incrementalNumber to the tag of the number. 
This will search for all de tags with this class. 
Finally you have to pass the number as a parameter in data-value attr. 
Dont forget to call the function incrementalNumber when the document is ready!

<span class="incrementalNumber" data-value="100"></span> 

<script type="text/javascript"> 
 $(document).ready(function(){ 
  incrementalNumber(); 
 }); 
</script> 
Example: 100

Options

If the number is to big, you can add the parameter big-Number and de count start 10% less the total. 
<span class="incrementalNumber" big-number data-value="2123"></span>
Example: 2123

If the number is more big, you can especificate the start number like this: 
<span class="incrementalNumber" big-number="19800" data-value="20000"></span>
Example: 20000

You can add text to the end with the parameter set-text 
<span class="incrementalNumber" set-text="%" data-value="100"></span>
Example: 100%

The last option can set the total time of the "animate" with set-time in ms 
<span class="incrementalNumber" set-time="3000" data-value="100"></span>
Example: 100

If the numer is to big, this may not work. You have to use big-number also to make it.

This is all. Hope you like it. 


Barto!
