# Webpage: https://animal-trivia.netlify.app/

[Lab 8: Trivia](https://cs50.harvard.edu/college/2020/fall/labs/8/#lab-8-trivia)
================================================================================

You are welcome to collaborate with one or two classmates on this lab, though it is expected that every student in any such group contribute equally to the lab.

Write a webpage that lets users answer trivia questions.

![screenshot of trivia questions](https://cs50.harvard.edu/college/2020/fall/labs/8/questions.png)

## Getting Started

Here's how to download this lab into your own CS50 IDE. Log into [CS50 IDE](https://ide.cs50.io/) and then, in a terminal window, execute each of the below.

-   Execute `cd` to ensure that you're in `~/` (i.e., your home directory, aka `~`).
-   Execute `wget https://cdn.cs50.net/2020/fall/labs/8/lab8.zip` to download a (compressed) ZIP file with this problem's distribution.
-   Execute `unzip lab8.zip` to uncompress that file.
-   Execute `rm lab8.zip` followed by `yes` or `y` to delete that ZIP file.
-   Execute `ls`. You should see a directory called `lab8`, which was inside of that ZIP file.
-   Execute `cd lab8` to change into that directory.
-   Execute `ls`. You should see an `index.html` and a `styles.css` file.

## Implementation Details

Design a webpage using HTML, CSS, and JavaScript to let users answer trivia questions.

-   In `index.html`, add beneath "Part 1" a multiple-choice trivia question of your choosing with HTML.
    -   You should use an `h3` heading for the text of your question.
    -   You should have one `button` for each of the possible answer choices. There should be at least three answer choices, of which exactly one should be correct.
-   Using JavaScript, add logic so that the buttons change colors when a user clicks on them.
    -   If a user clicks on a button with an incorrect answer, the button should turn red and text should appear beneath the question that says "Incorrect".
    -   If a user clicks on a button with the correct answer, the button should turn green and text should appear beneath the question that says "Correct!".
-   In `index.html`, add beneath "Part 2" a text-based free response question of your choosing with HTML.
    -   You should use an `h3` heading for the text of your question.
    -   You should use an `input` field to let the user type a response.
    -   You should use a `button` to let the user confirm their answer.
-   Using JavaScript, add logic so that the text field changes color when a user confirms their answer.
    -   If the user types an incorrect answer and presses the confirmation button, the text field should turn red and text should appear beneath the question that says "Incorrect".
    -   If the user types the correct answer and presses the confirmation button, the input field should turn green and text should appear beneath the question that says "Correct!".

Optionally, you may also:

-   Edit `styles.css` to change the CSS of your webpage!
-   Add additional trivia questions to your trivia quiz if you would like!

### Testing

No `check50` for this lab, as implementations will vary based on your questions! But be sure to test both incorrect and correct responses for each of your questions to ensure that your webpage responds appropriately.

Run `http-server` in your terminal while in your `lab8` directory to start a web server that serves your webpage.

## How to Submit

1.  Download your `index.html` and `styles.css` files by control-clicking or right-clicking on the files in CS50 IDE's file browser and choosing Download.
2.  Go to CS50's [Gradescope page](https://www.gradescope.com/courses/157004).
3.  Click "Lab 8: Trivia".
4.  Drag and drop your `index.html` and `styles.css` files to the area that says "Drag & Drop". Be sure that each file is correctly named!
5.  Click "Upload".

You should see a message that says "Lab 8: Trivia submitted successfully!"
