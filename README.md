Download Link: https://assignmentchef.com/product/solved-cse-102-homework-9
<br>
CSE102 HW09In this homework, you are going to implement a game. Suppose that a botanist looking for a quite rare flower by walking randomly in a forest. He/she is sure about that the rare flower in that forest certainly. He must find the rare flower before his water runs out. Otherwise, he faints in the forest.A forest contains the followings: Map [Integer][Integer]: This is a 2D array. Width [Integer]: This stores number of rows of the map. Height [Integer]: This stores number of columns of the map. Flower_X [Integer]: This is the X coordinate of the rare flower. Flower_Y [Integer]: This is the Y coordinate of the rare flower.The botanist contains the followings: Coord_X [Integer]: This is the X coordinate of the botanist. Coord_Y [Integer]: This is the Y coordinate of the botanist. Water_Bottle_Size [Integer]: This is the volume of water bottle in milliliters.Function: void init_game (Forest forest, Botanist botanist)This function reads a csv file called “init.csv” and initiates both the forest and the botanist. The first line contains volume of Botanist’s water bottle. The second line contains height and width of the forest. Starting from the third line, forest map is defined. Trees, the botanist and the rare flower are illustrated as #, B and F.Sample init.csv5010,10#,#,#,#,#,#,#,#,#,#B, , , ,#,#, , , ,##, ,#, , , , ,#, ,##, ,#,#,#,#, ,#, ,##, ,#, , , , ,#,#,##, ,#, ,#, , , , ,##, ,#, ,#,#,#,#,#,##, ,#, , , , , , ,##, ,#,#,#,#, ,#, ,##, , , , ,#,F,#,#,#Function: void print_map (Forest forest)This function shows the forest map on screen.Function: void search (…)This is a recursive function that walks (up, down, left and right) on the forest to find the rare flower. Botanist is so thirsty that he/she drinks his/her water 1 ml at every step. Botanist says “I have found it on (x,y)!” whenever he/she finds it before his/her water runs out. Otherwise, he shouts out “Help! I am on (x,y)” and faints.

Sample Screen Output (Success)

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/03/662.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/03/662.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Sample Screen Output (Fail)

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/03/383.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/03/383.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>