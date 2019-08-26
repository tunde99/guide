---
title: Iterate Through an Array with a For Loop
---
## Iterate Through an Array with a For Loop

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/basic-javascript/iterate-through-an-array-with-a-for-loop/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
Task:
Declare and initialize a variable total to 0. Use a for loop to add the value of each element of the myArr array to total.

Solution:
// declaring and initializing array and variable, total
var myArr = [ 2, 3, 4, 5, 6]; 
var total = 0; 

for (var i = 0; i < myArr.length; i++){
  total += myArr[i];
}
console.log(total);
