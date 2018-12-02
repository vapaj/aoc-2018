# aoc-2018
Advent of Code 2018

day 2: `perl -F"" -lane '$dd=0; $tt=0; for $c (@F) { $num=eval qq($_=~tr/$c//); $num==3 && ($tt=1) || $num==2 && ($dd=1) } $d+=$dd; $t+=$tt; END { print $d * $t }'`
