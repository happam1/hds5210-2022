# Notes on the Midterm

* _Correctness    (out of 40):_ 40
* _Good Practices (out of 10):_ 8
* _Docs / Testing (out of 10):_ 10

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

Overall, nicely done. I know it's very convenient to use `x` and `y` as variable names in loops, but they don't give much context into what the code is doing. It would be more readable / understandable if you used variable names with some meaning. I've dropped 1 point from _Good Practices_ for this.

Another style-comment: You sometimes write very long lines of code that make it harder to read and understand. Coding isn't just about communicating your instructions to the computer. It's also about writing code that another personal can come along later and understand, and I want you to practice that in this class. Rule of thumb: if a line of code is longer than 120 characters, it's too long.


## Step 1
* Nice work. No additional comments.

## Step 2
* Nice work. No additional comments.

## Step 3
* Your code repeats the `datetime.strptime(visit_date, '%Y-%m-%d')).strftime('%A')` logic a couple of times. It would have been clearer if you pulled that out and assigned the answer to a variable, then just tested the variable. I've subtracted 1 _Good Practices_ point for this.
* I like that you broke out the special conditions into three separate tests even though only two were technically necessary. Having the layout of the code match the way the requirements are described is helpful for readability and traceability.

## Step 4
* _spamreader_ ?  Interesting choice of variable name.
* I like your use of `DictReader()` so that you can access columns by name rather than by position. You also avoid having to skip the header row manually that way, too.