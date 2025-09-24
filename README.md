# CPP_exp9_pointers.cpp
#  POINTERS IN C++

---

##  AIM
To study and implement **Pointers in C++**.

---

##  Software Used
- **Visual Studio Code (VS Code)**

---

##  Theory

A **pointer** is a special variable used to store the memory address of another variable.  
In C++, pointers are widely used for direct memory access, dynamic memory allocation, and efficient handling of arrays and strings.

---

### 1. Pointer Basics
- A pointer is declared by placing an asterisk (`*`) before the variable name.  
**Example:**
```cpp
int x = 10;
int *ptr = &x;  // ptr stores the address of x
```
---

### 2️ Sum of Array Elements Using Pointers
**Aim:** Calculate the sum of elements in an array using pointer arithmetic.  

**Steps:**
1. Start  
2. Declare and initialize an integer array.  
3. Initialize a pointer to point to the first element of the array.  
4. Initialize a variable `sum = 0`.  
5. Repeat for each element in the array:  
   - Add the value pointed to by `(pointer + i)` to `sum`.  
6. Print the total sum.  
7. Stop  

---

### 3️ Reverse an Array Using Pointers
**Aim:** Reverse the elements of an array using two pointers.  

**Steps:**
1. Start  
2. Declare and initialize an array.  
3. Find the length of the array.  
4. Initialize `ptr` to point to the first element, and `ptr1` to point to the last element.  
5. Repeat until `ptr < ptr1`:  
   - Swap the values pointed to by `ptr` and `ptr1`.  
   - Increment `ptr` and decrement `ptr1`.  
6. Print the reversed array.  
7. Stop  

---

### 4️ Check if a String is Palindrome Using Pointers
**Aim:** Determine if a given string is a palindrome using two pointers.  

**Steps:**
1. Start  
2. Read the string from the user.  
3. Initialize `start` to point to the first character, and `end` to point to the last character (before `'\0'`).  
4. Repeat until `start < end`:  
   - If `*start != *end`, print **"Not a palindrome"** and stop.  
   - Else, increment `start` and decrement `end`.  
5. If loop completes, print **"Palindrome"**.  
6. Stop  

---

##  Conclusion
Pointers are one of the most powerful features of C++, enabling direct interaction with memory and providing flexibility in data manipulation.  
However, they require **careful handling** to avoid errors like **segmentation faults** and **memory leaks**.  

---
