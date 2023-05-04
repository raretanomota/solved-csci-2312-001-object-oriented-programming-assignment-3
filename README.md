Download Link: https://assignmentchef.com/product/solved-csci-2312-001-object-oriented-programming-assignment-3
<br>
<strong>Assignment 3</strong>

(Remember ROCkET programming methodology!)

Create a class called WaterVehicle that has the following member variables to represent the ship as described in Assignment 1:

<ul>

 <li>length of ship (in number of grid spaces)</li>

 <li>starting grid location</li>

 <li>horizontal or vertical orientation on grid</li>

 <li>sunk (Boolean indicating whether the ship has been sunk or not)</li>

</ul>




You will also need to create a reasonable complement of member functions (constructors, accessor, and mutator functions) to create the ships, to set the location of the ship, get the location of the ship, determine if the ship was hit, and determine if the ship is sunk.




Then create a Carrier, a Battleship, a Cruiser, a Submarine, and a Destroyer which are all of type WaterVehicle and have the following lengths:




<table>

 <tbody>

  <tr>

   <td width="169">Ship Type</td>

   <td width="125">Number of Grid Squares</td>

  </tr>

  <tr>

   <td width="169">Carrier</td>

   <td width="125">5</td>

  </tr>

  <tr>

   <td width="169">Battleship</td>

   <td width="125">4</td>

  </tr>

  <tr>

   <td width="169">Cruiser</td>

   <td width="125">3</td>

  </tr>

  <tr>

   <td width="169">Submarine</td>

   <td width="125">3</td>

  </tr>

  <tr>

   <td width="169">Destroyer</td>

   <td width="125">2</td>

  </tr>

 </tbody>

</table>







Then write a program which will allow input of the ship length, grid location, and orientation.  Assume the grid where the submarine is to be placed is a 10 by 10 grid and is indexed as described in Assignment 1.  Randomly generate 15 torpedo shots in the main of the program, output the shot grid locations to the screen, and then output whether the torpedo hit any ship and if it did, whether that ship was sunk.  You will need private member variables to keep track of where a ship has been hit to understand if it has been sunk.




Finally overload the &lt;&lt; operator to print a WaterVehicle with tabs between fields:

<ul>

 <li>length of ship (in number of grid spaces)</li>

 <li>starting grid location</li>

 <li>horizontal or vertical orientation on grid</li>

 <li>sunk (Boolean indicating whether the ship has been sunk or not)</li>

</ul>

Demonstrate the use of this operator for each WaterVehicle after the torpedos have been fired.




<strong> </strong>

<strong>Grading Rubric</strong>

Follow best practices in programming with declarations in .h files and implementations in .cpp files. Ensure your name is on every file in comments. Update your makefile (not makefile.txt!) AFTER you have tested successfully on the csegrid, update your readme.txt file then move over to your system. Create a folder named lastnameOB1 and place (just) your .h, .cpp, readme.txt, and makefile in that folder. Zip the folder and turn it into Canvas by the due date.

<strong> </strong>

You may (and are encouraged to) discuss general strategy with classmates (or other help) but you MUST document all extra help other than the textbook (including web sites) with comments. Failure to document extra help may result in a zero for the assignment. While you should help your classmates, stop short of giving exact lines of code or pseudocode. If we can’t determine who shared and who copied, we may give you both a zero for the assignment.

<strong> </strong>

<table>

 <tbody>

  <tr>

   <td width="312">Correct and Complete Functionality</td>

   <td width="48">14</td>

  </tr>

  <tr>

   <td width="312">Compile and Fault Tolerance (on csegrid)</td>

   <td width="48">2</td>

  </tr>

  <tr>

   <td width="312">makefile and readme.txt</td>

   <td width="48">2</td>

  </tr>

  <tr>

   <td width="312">Documentation / Comments</td>

   <td width="48">2</td>

  </tr>

 </tbody>

</table>

<strong> </strong>