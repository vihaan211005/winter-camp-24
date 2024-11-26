# Assignment 2

## Question 1: Karnaugh Maps (SOP and POS)
Simplify the following Boolean function using both **SOP (Sum of Products)** and **POS (Product of Sums)** forms using a Karnaugh Map:

\[
F(A, B, C, D) = \Sigma(0, 1, 2, 5, 8, 9, 10, 14)
\]

### 4-Variable Karnaugh Map

| AB\CD | 00  | 01  | 11  | 10  |
|-------|------|------|------|------|
| **00** | 1    | 1    | 0    | 1    |
| **01** | 1    | 1    | 0    | 0    |
| **11** | 0    | 0    | 0    | 0    |
| **10** | 1    | 1    | 0    | 0    |

- Use this K-map to derive the **SOP** and **POS** expressions.

---

## Question 2: Flip-Flop Counter
Design a **3-bit binary counter** using T flip-flops.

1. **State Diagram**:  
   The counter cycles through the binary states: \( 000 \rightarrow 001 \rightarrow 010 \rightarrow 011 \rightarrow 100 \rightarrow 101 \rightarrow 110 \rightarrow 111 \rightarrow 000 \).

---

## Submission Format
Submit as photo of answers. Markdown file for extra credits.