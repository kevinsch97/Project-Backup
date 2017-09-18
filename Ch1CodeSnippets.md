Code Snippets

#1
------------------------------------------------------------------------------------------------

			<script>
				 /* 
				 Information on available plants including link to USDA website
				 ref:  page 31
				 */
				 document.write("<p>Plant choices for <a href='http://planthardiness.ars.usda.gov'>hardiness zones</a> 5a-6b</p>"); // page 29
			 

			 </script>

------------------------------------------------------------------------------------------------

#2
------------------------------------------------------------------------------------------------

			 //declare and initialize variables to hold the image source values   Ref page 38-39
			 
				 var blanket = "https://cdn.glitch.com/8a1b3cd3-54ce-4fe1-9505-65aa3773d79%2Fblanket.jpg?1503962836872";
				 var bluestem = "https://cdn.glitch.com/8a1b3cd3-54ce-4fe1-9505-f65aa3773d79%2Fbluestem.jpg?1503962836872";
				 var rugosa = "https://cdn.glitch.com/8a1b3cd3-54ce-4fe1-9505-f65aa3773d79%2Frugosa.jpg?1503962836872";
			 

------------------------------------------------------------------------------------------------

#3
------------------------------------------------------------------------------------------------
         <ul>
		 <!--ref page 44-->
            <li onclick="document.getElementById('plantImg').src=blanket">Blanket Flower</li>
            <li onclick="document.getElementById('plantImg').src=rugosa">Hedge Rose</li>
            <li onclick="document.getElementById('plantImg').src=bluestem">Little Bluestem</li>
         </ul>
------------------------------------------------------------------------------------------------