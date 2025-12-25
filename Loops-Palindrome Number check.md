Loops in Python: Palindrome Number Checker

🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

🧠 Algorithm
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

🧾 Program

<img width="787" height="215" alt="image" src="https://github.com/user-attachments/assets/f205d7f1-a80a-4a4a-86c2-7cb0ff5bb8e0" />

Output

<img width="1078" height="221" alt="image" src="https://github.com/user-attachments/assets/6cb1470f-3840-4ae1-b3c4-98175c1f618d" />

Result
Thus, the program has been successfully executed.
