# Date and Time Named Entitiy Recognition

# Purpose of this Program

    - Build date and time named entity recognizer using regular expression 
    - Find patterns of fixed date
      ex) "January 15, 2014”, “the 21st of December”, “01/15/2014” (only the
           American notation), “Monday”, “Monday the 23rd”, “Monday, 2pm”, “Monday
           afternoon”
    - Find holidays (only American holidays)
    - Extract the longest expression mentioned
      ex) “.. The mayor addressed the audience on Feb. 14th, 2012..”
          -> "Feb. 14th, 2012" and not only "Feb. 14th" or just “2012”.

# How to Run

    - Clone this repository
    - Go to "assignment1.ipynb"
    - This program contains five headings.
    - Locate txt file that you'd like to extract the date and time in the    src/Data/Input folder and named it as "input.txt"
    - Run all cells
    - Check output.txt file
