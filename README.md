# calculus-group-activity-

# Green's Theorem – Mathematics Project

This project explains **Green’s Theorem** in simple language and verifies it using a Python program.  
It includes the explanation, conditions, applications, an example, and the code used for verification.

---

## 1. Introduction

Green’s Theorem is a result from vector calculus that connects:

- A **line integral** around a closed curve, and  
- A **double integral** over the region inside the curve.

It basically says that what happens around the boundary of a region is related to what happens inside the region.

---

## 2. Statement of Green’s Theorem (Simple Version)

If a curve completely closes a region, then:
Line Integral around the boundary

Double Integral inside the region


More specifically:
Integral of (P dx + Q dy) around the boundary

Integral of (dQ/dx – dP/dy) over the region



Where:
- P(x, y) and Q(x, y) are functions
- dQ/dx means “partial derivative of Q with respect to x”
- dP/dy means “partial derivative of P with respect to y”

---

## 3. Conditions to Use Green’s Theorem

Green’s Theorem can be used only when:

1. The curve is **closed** (forms a full loop).
2. The curve is **positively oriented** (traversed anticlockwise).
3. The region is **simple and connected**.
4. P and Q have **continuous partial derivatives**.

---

## 4. Applications of Green’s Theorem

- Used to convert line integrals to double integrals  
- Used to find area using integration  
- Used in fluid flow and circulation  
- Helpful in electromagnetism  
- Base for Stokes’ Theorem in higher dimensions  

---

## 5. Example Used in This Project

### Vector field used:
P(x, y) = -y
Q(x, y) = x


### Region:
Unit square:
x ranges from 0 to 1
y ranges from 0 to 1



### Double Integral

dQ/dx = 1
dP/dy = -1
So, dQ/dx – dP/dy = 2



Area of square = 1  
So the double integral =  
2 × 1 = 2


### Line Integral

The Python program calculates the line integral around all 4 sides of the square and the result is also:

### Result:
Double Integral = 2
Line Integral = 2


Both match → **Green’s Theorem is verified.**


## 6. Python Program

The file `greens_theorem.py` in this repository:

- Calculates the line integral  
- Calculates the double integral  
- Shows that both values are equal  

Run it with:

python greens_theorem.py


## 7. Project Structure

📁 Green-Theorem-Project
│── README.md
│── greens_theorem.py


## 8. Conclusion

This project proves that:

Integral around boundary
Integral inside the region


