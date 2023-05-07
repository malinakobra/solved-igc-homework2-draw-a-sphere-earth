Download Link: https://assignmentchef.com/product/solved-igc-homework2-draw-a-sphere-earth
<br>



<ol>

 <li>Draw a sphere: Earth</li>

 <li>The Earth is rotating.</li>

 <li>Add textures on the Earth</li>

</ol>

*Use GLSL to do this homework, otherwise you’ll get zero points.

<h1>Spec</h1>

<strong>Camera:</strong>

Posi&amp;on: (0, 0, 3)

Center: (0, 0, 0)

Up vector: (0, 1, 0)

<strong>Earth:</strong>

Slice: 360

Stack: 180

Radius: 1

Texture: earth_texture_map.jpg

<h1>Texture coordinates</h1>

slice

<h1>Score</h1>

Ø2. Add the texture on the sphere and rotate it. (25%)   Ex:

Ø3. Demo (10%) (We will ask you some questions about this homework)

<h1>Others</h1>

<ol>

 <li>Use Visual Studio 2017 or 2019 for this homework. (If you use Mac, you should bring your computer to demo.)</li>

 <li>You can do this homework from the “HW2Example” project file and follow the instrucOons in HW2guideline.pdf.</li>

 <li>Zip your Visual Studio project into “ StudentID_HW2.zip” , and upload it to New e3.</li>

 <li>The deadline is at 11:55 pm on November 25.</li>

 <li>If you submit your homework late, the score will be discounted. submit between (11/26 ̴ 12/2) : Your final score * 0.9 submit between (12/2   ̴ 12/9) : Your final score * 0.8 submit a_er 12/10 : Your final score * 0.7</li>

</ol>




How to draw a sphere

Draw a sphere

Draw a sphere

Triangle strip – Reuse some ver4ces to draw the triangles, so we can save the storage space.

According to the picture, we only need 5 ver4ces to store 3 triangles.

<table width="334">

 <tbody>

  <tr>

   <td width="66">V1</td>

   <td width="67">V2</td>

   <td width="67">V3</td>

   <td width="67">V4</td>

   <td width="66">V5</td>

  </tr>

 </tbody>

</table>

V2                                   V4                         Triangle 2 Triangle 3

V1

V3

<h1>Draw a sphere</h1>