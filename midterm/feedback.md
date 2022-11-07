# Notes on the Midterm

* _Correctness    (out of 40):_ 40
* _Good Practices (out of 10):_ 8
* _Docs / Testing (out of 10):_ 6

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

Remember that docstring tests are VERY picky about formatting. There needs to 1 space between `>>>` and the command you want to run.

In all of your functions except step 1, you haven't included tests. I've deducted 4 points from _Docs / Testing_ for the missing tests.

## Step 1
* Nice work.

## Step 2
* Good work. No additonal comments.

## Step 3
* Using exception handling here is an interesting choice, especially because any exceptions you encounter end up returning None, as if the billing / service code combination couldn't be found? I've deducted 1 point from _Good Practices_ for this.

## Step 4
* Good approach, but you could have simplified this by moving the `if rate is None` code higher up.  Then you could just skip everything about accumulating partial totals. If the rate is None, you don't need to do any of the `if hospital in by_hospital` or `if month in by_month`.  I've deducted 1 _Good Practices_ point on this, too.