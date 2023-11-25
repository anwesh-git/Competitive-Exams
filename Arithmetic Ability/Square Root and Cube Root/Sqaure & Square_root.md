# Squares and Square Roots

## Squares

Remember $1-25$ squares:

| Number | Square | Number | Square | Number | Square | Number | Square | Number | Square |
|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| 1      | 1      | 6      | 36     | 11     | 121    | 16     | 256    | 21     | 441    |
| 2      | 4      | 7      | 49     | 12     | 144    | 17     | 289    | 22     | 484    |
| 3      | 9      | 8      | 64     | 13     | 169    | 18     | 324    | 23     | 529    |
| 4      | 16     | 9      | 81     | 14     | 196    | 19     | 361    | 24     | 576    |
| 5      | 25     | 10     | 100    | 15     | 225    | 20     | 400    | 25     | 625    |

### Cases:

#### First Case (25-75)

- Reference Point: 50
- Given number is how much +/- with the reference point
- Square that +/- number $\Rightarrow$ this will be the last two digits
- +/- that number with 25 $\Rightarrow$ this will be the remaining numbers

**Example:**

$49^2 = $

- Reference Point: 50
- $49 - 50 = -1 \Rightarrow 1^2 = 01$
- Then $25 - 1 = 24$
- Final answer is $2401$

$74^2 = $

- Reference Point: 50
- $74 - 50 = +24 \Rightarrow 24^2 = 576$
- Then $25 + 24$ = 49
- Final answer is $5476$

#### Second Case (75-125)

- Reference Point: 100
- Given number is how much +/- with the reference point
- Square that +/- number; this will be the last two digits
- +/- that number with the given number; this will be the remaining numbers

**Example:**

$112^2 = $

- Reference Point: 100
- $112 - 100 = +12 \Rightarrow 122 = 144$
- Then $112 + 12 = 124$
- Final answer is $12544$

$76^2 = $

- Reference Point: 100
- $76 - 100 = -24 \Rightarrow 242 = 576$
- Then $76 - 24 = 52$
- Final answer is $5776$

#### Any Digit Squares

$63^2 = $

- Reference Point: 60
- +/- the balance with respect to the reference point to the given number
- \(+3 - 3\)
- $66 \times 60 = 3960$
- Add the square of the balance number to that
- $3^2 = 9$
- $3960 + 9 = 3969$
- Final answer is $3969$

$209^2 = $

- Reference Point: 200
- +/- the balance with respect to the reference point to the given number
- \(+9 - 9\)
- $218 \times 200 = 43600$
- Add the square of the balance number to that
- $9^2 = 81&
- $43600 + 81 = 43681$
- Final answer is $43681$
- 
### If last digit is:

- 1 in square, then the answer of the last digit is also 1.
- 5 in square, then the answer of the last two digits will be 25. Remaining digits will be the given tens place multiplied by the next number of the tens place.

**Example:**

- $5^2 = 25$
- $15^2 = (1 \times 2)25 = 225$
- $25^2 = (2 \times 3)25 = 625$
- $35^2 = (3 \times 4)25 = 1225$
- $45^2 = (4 \times 5)25 = 2025$
- $55^2 = (5 \times 6)25 = 3025$
- $65^2 = (6 \times 7)25 = 4225$
- $75^2 = (7 \times 8)25 = 5625$
- $85^2 = (8 \times 9)25 = 7225$
- $95^2 = (9 \times 10)25 = 9025$
- $105^2 = (10 \times 11)25 = 11025$

## Square Roots

### Input and Output of Last Digits:

- Input of Last Digit: 1 $\Rightarrow$ Output of Last Digit: 1 or 9
- Input of Last Digit: 4 $\Rightarrow$ Output of Last Digit: 2 or 8
- Input of Last Digit: 9 $\Rightarrow$ Output of Last Digit: 3 or 7
- Input of Last Digit: 6 $\Rightarrow$ Output of Last Digit: 4 or 6
- Input of Last Digit: 5 $\Rightarrow$ Output of Last Digit: 5

**Examples:**

$\sqrt{10609} = $

- Last digit is 9 $\Rightarrow$ then the answer's last digit will be 3 or 7
- Forget the last two digits (because of square)
- 106 is near to the square of 10
- It must be 103 or 107
- To get the exact answer, multiply that number and the next number of that
- $10 \times 11 = 110$
- This number is compared with $106$
- If it is higher than 7, the answer is 103
- If it is lower than 3, the answer is 107
- 106 is less than 110, so the final answer is $103$

$\sqrt{144} = $

- Last digit is 4 $\Rightarrow$ then the answer's last digit will be 2 or 8
- Forget the last two digits
- 1 is near to the square of 1
- It must be 12 or 18
- To get the exact answer, multiply that number and the next number of that
- $1 \times 2 = 2$
- This number is compared with 1
- If it is higher than 8, the answer is 12
- If it is lower than 2, the answer is 18
- 1 is less than 2, so the final answer is $12$

$\sqrt{9801} = $

- Last digit is 1 $\Rightarrow$ then the answer's last digit will be 1 or 9
- Forget the last two digits
- 98 is near to the square of 9
- It must be 91 or 99
- To get the exact answer, multiply that number and the next number of that
- $9 \times 10 = 90$
- This number is compared with 98
- If it is higher than 9, the answer is 91
- If it is lower than 1, the answer is 99
- 98 is greater than 90, so the final answer is $99$

$\sqrt{61504} = $

- Last digit is 4 $\Rightarrow$ then the answer's last digit will be 2 or 8
- Forget the last two digits
- 615 is near to the square of 24
- It must be 242 or 248
- To get the exact answer, multiply that number and the next number of that
- $24 \times 25 = 600$
- This number is compared with 615
- If it is higher than 8, the answer is 242
- If it is lower than 2, the answer is 248
- 615 is greater than 600, so the final answer is $248$

$\sqrt{55696} = $

- Last digit is 6 $\Rightarrow$ then the answer's last digit will be 4 or 6
- Forget the last two digits
- 556 is near to the square of 23
- It must be 234 or 236
- To get the exact answer, multiply that number and the next number of that
- $23 \times 24 = 552$
- This number is compared with 556
- If it is higher than 6, the answer is 236
- If it is lower than 4, the answer is 234
- 556 is greater than 552, so the final answer is $236$

### Trick:

Multiple of a number with the next of that number will be:

- ${small}^2 + {small}$
- ${large}^2 - {large}$
