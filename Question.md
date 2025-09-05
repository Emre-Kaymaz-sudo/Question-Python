# Body Mass Index (BMI) Calculator — Programming Task

## Task

Read the user’s **weight (kg)** and **height (meters)**, compute the **Body Mass Index (BMI)**, and print the BMI value and its category.

---

## Rules & Guidelines

### Academic Integrity (Mandatory)

* **All code must be your own work. Plagiarism will result in disqualification.**
* **External sources** (e.g., Stack Overflow, GitHub repositories, online tutorials) **may only be used for reference, not for direct copying.**
* **The use of AI tools** (e.g., ChatGPT, GitHub Copilot, CodeWhisperer, etc.) **or any automated code generation system is strictly prohibited.**
* **You must complete the task individually. Collaboration with others is not allowed.**

### Submission & Quality

* Write **clear** and **well-documented** code. Include comments where necessary.
* Ensure your solution is **working**, **optimized**, and **readable**.
* **Submit** your solution before the given deadline. Late submissions will not be accepted unless previously approved.
* You may ask **clarifying questions** about the problem statement, but **no hints or solutions** will be provided.

---

## Objective

This assignment is designed to evaluate your coding knowledge, problem-solving skills, and ability to write clean, efficient, and maintainable code.

---

## BMI Formula

```markdown
BMI = weight(kg) / (height(m))²
```

### Categories

* BMI < 18.5 → **Underweight**
* 18.5 ≤ BMI < 25 → **Normal**
* 25 ≤ BMI < 30 → **Overweight**
* BMI ≥ 30 → **Obese**

---

## Input Format

* First line: a `double` (float) value — **weight**
* Second line: a `double` (float) value — **height**

## Output Format

* First line: `BMI: <value>` (two digits after the decimal point)
* Second line: `Status: <category>`

### Sample Input 1

```plaintext
70
1.75
```

### Sample Output 1

```plaintext
BMI: 22.86
Status: Normal
```

### Sample Input 2

```plaintext
95
1.68
```

### Sample Output 2

```plaintext
BMI: 33.67
Status: Obese
```

---

## Constraints

* 0 < weight ≤ 300
* 0 < height ≤ 2.5

If the user enters an invalid value, print `Invalid value`.

---

## Hint

* You can compute the square using `height ** 2` (or `Math.pow(height, 2)` in Java).
* To format to two decimals, use your language’s formatting (e.g., Python: `f"{bmi:.2f}"`, Java: `System.out.printf("%.2f", bmi);`).

---

## Evaluation Criteria

* **Code correctness and functionality**
* **Code readability and documentation**
* **Problem-solving approach**
* **Efficiency and optimization**
