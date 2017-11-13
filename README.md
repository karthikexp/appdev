# appdev
Multiple Progress Bar - Responsive
---------------------------
Following points has covered into Multiple Progress Bar<br>
 •Must read data from the endpoint <br>
 •Multiple bars<br>
 •One set of controls that can control each bar on the fly<br>
 •Can't go under 0<br>
 •Can go over limit (defined in API), but limit the bar itself and change its colour<br>
 •Display usage amount, centered<br><br>
 
 Solution: <br>
 Step 1: Create the json file to pass data along with buttons, bars and limits<br>
 Step 2: Create the js file to read the data.<br>
 Step 3: Create css file and defined the css tags for body, progressbar, dropdown and button<br>
 Step 4: Give reference to index.html<br>
 Step 5: Onload event load the data from json.<br>
 Step 6: In same event bind the data into progress bar, dropdown and buttons.<br>
 Step 7: Write onclick event of button to increase/ decreas the width of progress bar.<br>
 Step 8: In same event check the condition as width should not greater than the limit.<br>
        Step 8.1: If width more than the limit progress bar will indicate as red color to say beyond the limit.  <br>      
 Step 9: If width goes less than 0 system will stop doing to decrease and width set as 0%.<br>
 Step 10: In the same event system will also check selection of progress bar in dropdown list.<br><br>
 
Note: Minified js and css files are in lib folder. <br>
 
 Test case 1:<br>
  Step 1: Select "Progress Bar 1" <br>
  Step 2: click button "10"<br>
 Output: First progress bar will increase 10% and it will show as "72%"<br>
 Test case 2:<br>
  Step 1: Select "Progress Bar 1" <br>
  Step 2: click button "38"<br>
 Output: First progress bar will increase 38% and it will show as "100%"<br>
 Test case 3:<br>
  Step 1: Select "Progress Bar 1" <br>
  Step 2: click button "-13"<br>
 Output: First progress bar will decrease 38% and it will show as "49%"<br>
 Test case 4:<br>
  Step 1: Select "Progress Bar 1" <br>
  Step 2: click button "-18"<br>
 Output: First progress bar will decrease 38% and it will show as "44%"
 
 
 
 


