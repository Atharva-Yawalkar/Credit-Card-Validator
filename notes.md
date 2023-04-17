American Express numbers start with 34 or 37 -> 15 digit numbers

Mastercard numbers start with 51, 52, 53, 54, or 55 -> 16 digit numbers

Visa numbers start with 4 -> Visa uses 13 and 16 digit numbers


4003600000000014

4003600000000014 % 10 = 4 to get last digit
4003600000000014 / 100 = 40036000000000 to move two digits over 

1st case: 4 + 3 + 0 = 7 add every alternate number start from last
2nd case: 1 * 2 + 6 * 2 + 4 * 2 = 2 + 12 + 8 = 2 + 3(1+2) + 8 = 13 start from second last number multiply the number and add. when we get two number by multiplying the number then we add those two digits 
Final sum = 7 + 13 = 20

20 % 10 = 0

1st case:
1. Iterate through the Credit Card (CC) number
2. Use modulo to get the last digit
3. Add last digit to sum
4. Divide the CC number 100
5. Repeat

2nd case:
1. Divide the CC number by 10
2. Iterate through the Credit Card (CC) number
3. Use modulo to get the last digit
4. Add last digit multiplied by 2 to sum
    4.1 Use modulo for the last digit
    4.2 Use divisionn for the 1st digit
    4.3 Sum these up
4. Divide the CC number 100
5. Repeat