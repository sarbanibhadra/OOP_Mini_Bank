# MiniBank

In this activity, used objects to create a mini banking application.

## Instructions

### Part 1 - Add methods and properties to `MiniBank`

Updated the `MiniBank` constructor function with methods and properties as follows:

1. Defined a property named `statement`. Assign an initial value of an array containing the `balance` parameter passed to the constructor.

2. Added a `setBalance` function. This function should receive a `value` parameter and assign it to the `balance` property of `MiniBank`.

3. Wrote an `updateStatement` function that takes in a number and pushes it to the `statement` array.

4. Wrote a `getStatement` function that returns the `statement` property.

5. Wrote a `printStatement` function that prints each element in the `statement` array on its own line.

6. Wrote a `deposit` function that takes a value and performs the following:

   - Calls `updateStatement` to record the deposit transaction.
   - Calls `setBalance` to update the `balance` property.

7. Wrote a `withdraw` function that takes a value and performs the following:

   - Calls `updateStatement` to record the withdrawal transaction. (Be sure to use a negative number here.)
   - Calls `setBalance` to update the `balance` property.

### Part 2 - Create and use a `MiniBank` instance

1. Created a new `bank` object using the `MiniBank` constructor function.

2. Printed the `bank` balance.

3. Deposited some money into the `bank` object.

4. Printed the `bank` balance.

5. Withdrawn some money from the `bank` object.

6. Printed the `bank` balance.

## Results

Balance: 0

Deposited 85!

Balance: 85

Withdrew 20!

Balance: 65
1. 0
2. 85
3. -20

## BONUS 🏆

- Added code to throw an error if the user tries to withdraw more money than they have or tries to deposit or withdraw values that aren't positive numbers.

- Added code to return a copy of the `statement` array when `getStatement` is called, rather than returning the original array.

---

© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
