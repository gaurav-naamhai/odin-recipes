Hi this is a readme file for writng all the problems and doubts i faced during the test.




1.
../odin-recipes/recipes/poha.html     is wrong
but 
../recipes/poha.html is right why???




2.
while deploying it became an issue hat recipes were not coming why??
in index,html i did this:
 <!-- <li><a href="../recipes/poha.html">Poha</a></li> -->
 but it was wrong
why??:
index.html is at the root, not inside a subfolder. It shouldn't go ../ up. 
so i fixed it by doint this:
<!--<li><a href="recipes/poha.html">Poha</a></li> -->