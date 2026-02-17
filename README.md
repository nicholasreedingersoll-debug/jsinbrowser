# cs2-prompt

## Setup files
1. Install Live Server
2. Create ```index.html``` and use ! shortcut to add required HTML tags
    - Set the title to **6.8 Browser Prompts**
    - Add an **h1** that says **6.8 Browser Prompts**
    - Add a **button** that says **Start example**
3. Create ```script.js```
    - Add ```console.log("Script started");``` at the beginning of the script file
    - Add ```<script src="script.js"></script>``` right before the ending ```</body>``` tag
4. Go Live to test your webpage
    - Use the inspection tool and select the console. You should see **Script started** in the console if your script is setup correctly

## Example - Recreate CodeHS 2.7 Girl Scout Designation

1. Define a ```startExample``` function in your script
    ```javascript
    function startExample() {

    }
    ```
2. Add ```onclick="startExample()"``` to the button tag
    ```html
    <button onclick="startExample()">Start example</button>
    ```
3. Write a program that will determine if a girl scout has reached ‘Gold’ status.

    Ask the user for three variables (Use ```prompt()``` to ask the user for data instead of ```readInt()```):
    - The number of boxes of cookies sold
    - The total number of badges they have
    - The number of volunteer hours they have worked  
    

    A girl scout has reached gold status if they sold at least 100 boxes of cookies, OR they sold at least 50 boxes and have at least 10 badges and have volunteered at least 25 hours. You will need to use both logical and comparison operators here.

    Once you determine their status, let them know! (Use ```alert()``` instead of ```println()```)

    For example, if the user gave the following input:
    ```
    How many boxes did you sell? 60
    How many badges do you have? 12
    How many hours have you volunteered? 30
    You should respond with the following output:
    ```
    ```
    Is gold status? True
    ```
4. Commit and push your changes

## Exercise - Recreate CodeHS 2.7 Rolling Dice

1. Define a new function named ```startExercise()``` in your ```script.js``` file
    ```javascript
    function startExercise() {

    }
    ```
2. Create a second button that says **Start exercise** and add an ```onclick``` attribute to call the ```startExercise()``` function
    ```html
    <button onclick="startExercise()">Star exercise</button>
    ```
3. Write a program that determines if the user rolled doubles in dice. (This means that the numbers showing on both dice match.) To do so, you need to prompt the user for two integers which will represent the dice rolls.

    Create a variable called rolledDoubles which has the true or false value of whether or not the two integer values are equal. Print that out.

    A sample output might look something like this:
    ```
    First die? 2
    Second die? 2
    Rolled doubles? true
    ```
4. Commit and push your changes, then submit the link to your GitHub repo (not your codespace) to the assignment on Canvas