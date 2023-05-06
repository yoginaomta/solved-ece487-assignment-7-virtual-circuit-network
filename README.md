Download Link: https://assignmentchef.com/product/solved-ece487-assignment-7-virtual-circuit-network
<br>
<ol>

 <li> The following figure shows a virtual circuit network. Station A is going to send information to Station B, through two switches: S<sub>1</sub> and S<sub>2</sub>. A virtual circuit is set up for this communication: A –&gt; S<sub>1</sub> –&gt; S<sub>2</sub> –&gt; B. For this virtual circuit, the VCIs over the three hops are 24, 15, and 66, respectively.</li>

 <li>Who are responsible to assign the three VCIs?</li>

 <li>Please give the switching tables at the two switches. iii) For communication from Station A to Station B, please give the VCI numbers included in the frames over the three hops.</li>

 <li> In a domain applying a distance vector routing protocol, station A and station B are neighbors. At a moment, the routing tables at the two stations are:</li>

</ol>

Station A                                                                                 Station B

<table width="638">

 <tbody>

  <tr>

   <td width="91">To</td>

   <td width="91">Cost</td>

   <td width="91">Next</td>

   <td rowspan="6" width="91"> </td>

   <td width="91">To</td>

   <td width="91">Cost</td>

   <td width="91">Next</td>

  </tr>

  <tr>

   <td width="91">A</td>

   <td width="91">0</td>

   <td width="91">–</td>

   <td width="91">A</td>

   <td width="91">4</td>

   <td width="91">–</td>

  </tr>

  <tr>

   <td width="91">B</td>

   <td width="91">4</td>

   <td width="91">–</td>

   <td width="91">B</td>

   <td width="91">0</td>

   <td width="91">–</td>

  </tr>

  <tr>

   <td width="91">C</td>

   <td width="91">12</td>

   <td width="91">B</td>

   <td width="91">C</td>

   <td width="91">9</td>

   <td width="91">–</td>

  </tr>

  <tr>

   <td width="91">D</td>

   <td width="91">13</td>

   <td width="91">–</td>

   <td width="91">D</td>

   <td width="91">5</td>

   <td width="91">–</td>

  </tr>

  <tr>

   <td width="91">E</td>

   <td width="91">10</td>

   <td width="91">–</td>

   <td width="91">E</td>

   <td width="91">9</td>

   <td width="91">–</td>

  </tr>

 </tbody>

</table>




And subsequently, station B shares its routing table with station A. Please determine the contents in station A’s routing table after the sharing.




<ol start="3">

 <li>For the following network topology, please use the Dijkstra algorithm to find the shortest path tree for Station A, and based on the shortest path tree, give the routing table at Station A. <strong>Please show your steps.</strong> Please use a square to represent a station in the permanent list, and a circle to represent a station in the tentative list.</li>

</ol>








