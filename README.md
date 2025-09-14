# Name: Navi Bountho

# UI: A ConstraintLayout with one TextView and nine buttons
    Defined some String Resources
    activity_main.xml
    strings.xml
# Code: A main activity with a matrix and two helper methods
 In MainActivity.java 
lines 14 - 16 initialize the cellState
line 32 and 48 is where the helper methods are declared.

# Cellstate a matrix of boolean indicating which lights are on or off
Line 16 is where the CellState is defined.

# Code to color each button based on their cellState
Line 32 with the recolor method

# code to get a handle on the GridLayout
  line 27 grid = findViewById(R.id.light_grid);

# How can the same functionality be achieved without an onCLickListener.
You could make it so that whenever you recolor() is called, it also counts the number of 
cellStates that are true and unpdate the value of score that way.





  
