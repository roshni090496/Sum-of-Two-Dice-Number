#Sum of two Dice Number
Dice1=$((1+RANDOM%6))
echo "Dice 1 =" $Dice1
Dice2=$((1+RANDOM%6))
echo "Dice 2 =" $Dice2
sum=$((Dice1+Dice2))
echo "Sum of two Dice no = " $sum
