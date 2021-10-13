# odd_even
#!/bin/bash
#for printing all the odd number lines
awk ' NR % 2 == 1 ' input.txt
source evenfile.sh
