# NTWK8141

#!/bin/bash
# A script that uses conditional expressions and loops
count=10
while [ $count -gt 0 ]
do
        echo The loop count is $count
        count=$[ $count - 1 ]
done
#
if [ $count -eq 0 ]
then
        echo "Count is set to zero: $count"
else
        echo "Count is not set to zero: $count"
fi
exit

# ======using until loop==========
#!/bin/bash
# Week 12 Slide 22
# Complete the Real World Scenario: Adding Conditional Expressions and Loops
# Step 22 - Using an until loop

count=10

until [ $count -le 0 ]
do
  echo "The loop count is $count."
  count=$(( count - 1 ))
done

if [ $count -eq 0 ]
then
  echo "Count is set to zero: $count."
else
  echo "Count is not set to zero: $count."
fi

exit


NTWK8141 - Week 12
This folder includes all Bash scripts written and tested for Week 12 of this course.

Week 12 Slide 12
Complete the Real World Scenario: Writing a Simple Shell Script with Variables in Ch 19

See myScript.sh - testing variables such as username, filename, and command line arguments.
Week 12 Slide 22
Complete the Real World Scenario: Adding Conditional Expressions and Loops to a Shell Script in Ch 19

See myScript2.sh - uses while loop to reduce a variable to zero.

See myScript2-until.sh - uses until loop to reduce a variable to zero.
