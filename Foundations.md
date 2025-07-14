## 🧠 What is DSA and Why It's Important

**DSA = Data Structures + Algorithms**

* **Data Structures** are ways of organizing and storing data (e.g., arrays, linked lists, trees).
* **Algorithms** are step-by-step procedures to solve problems (e.g., sorting, searching).

### ✅ Why DSA Matters:

* 📈 **Improves problem-solving skills**
* 💼 **Essential for coding interviews** at top companies
* ⚡ **Optimizes code performance**
* 🧩 Helps build efficient software, apps, and systems

---

## ⏱️ Time & Space Complexity (Big O Notation)

**Big O Notation** helps us measure how fast (time) and how much memory (space) an algorithm uses as input size grows.

### 📌 Time Complexity Examples:

| Operation                | Time Complexity |
| ------------------------ | --------------- |
| Constant (e.g., print x) | O(1)            |
| Loop through n items     | O(n)            |
| Nested loops (n × n)     | O(n²)           |
| Binary Search            | O(log n)        |

### 📌 Space Complexity:

How much extra memory your code uses. E.g., using an array of size `n` → O(n)

---

## ⌨️ Basic Input/Output in Python, C++, and Java

### ✅ Python:

```python
name = input("Enter your name: ")
print("Hello,", name)
```

### ✅ C++:

```cpp
#include <iostream>
using namespace std;

int main() {
    string name;
    cout << "Enter your name: ";
    cin >> name;
    cout << "Hello, " << name;
    return 0;
}
```

### ✅ Java:

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter your name: ");
        String name = sc.next();
        System.out.println("Hello, " + name);
    }
}
```

---

## 🔁 Variables, Loops, Conditions, Functions

### ✅ Variables

Store data.

```python
age = 20
```

### ✅ Loops

Repeat tasks.

```python
for i in range(5):
    print(i)  # prints 0 to 4
```

### ✅ Conditions

Make decisions.

```python
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

### ✅ Functions

Reuse code blocks.

```python
def greet(name):
    print("Hello", name)

greet("Ram")
