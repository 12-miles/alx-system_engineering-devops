
Task 0

#!/bin/bash
alias ls="rm *"

Task 1

#!/bin/bash
echo hello $USER

Task 2

#!/bin/bash
export PATH=$PATH:/action

Task 3

#!/bin/bash
echo $PATH | tr -s ":" "\n" | wc -l

Task 4

#!/bin/bash
printenv

Task 5

#!/bin/bash
set

Task 6

#!/bin/bash
BEST="School"

Task 7

#!/bin/bash
export BEST="School"

Task 8

#!/bin/bash
echo "$((TRUEKNOWLEDGE+=128))"

Task 9

#!/bin/bash
echo $((POWER/DIVIDE))

Task 10

#!/bin/bash
echo $((BREATH**LOVE))

Task 11

#!/bin/bash
echo "$((2#$BINARY))"

Task 12

#!/bin/bash
printf "%s\n" {a..z}{a..z} | grep -v "oo"

Task 13

#!/bin/bash
printf "%.2f\n" $NUM

Task 14

#!/bin/bash
printf "%x\n" $DECIMAL

Task 15

#!/bin/bash
tr 'a-zA-Z' 'n-za-mN-ZA-M'

Task 16

#!/bin/bash
cat -n | grep [13579][[:space:]] | tr -s ' ' | cut -f2

Task 17

#!/bin/bash
printf "%o\n" $((5#`echo $WATER | tr 'water' '01234'` + 5#`echo $STIR | tr 'stir.' '01234'`)) | tr '01234567' 'bestchol'
