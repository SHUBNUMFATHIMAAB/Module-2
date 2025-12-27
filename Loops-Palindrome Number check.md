## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
<img width="485" height="175" alt="image" src="https://github.com/user-attachments/assets/18cc7c77-4a7a-4227-85dd-3aed0345ef5b" />

## Output
<img width="700" height="238" alt="image" src="https://github.com/user-attachments/assets/98534c68-6ad8-4157-bfa5-0ca38cd7f491" />

## Result
Thus the Python program that checks whether a given number is a "palindrome" using loops is created.
