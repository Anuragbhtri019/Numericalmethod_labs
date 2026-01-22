# Numerical Methods Labs (BSc CSIT – 3rd Sem)

This repository contains C programs for most of the **Numerical Methods** algorithms typically used in the **BSc CSIT 3rd semester Numerical Method** course.

> Repository: `Anuragbhtri019/Numericalmethod_labs`  
> Language: **C (100%)**

---

## 📚 Programs Included

All files are standalone C programs. The numbering roughly follows the usual order of topics in the course.

### 1. Root Finding Methods

- [`1_bisection.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/1_bisection.c)  
  Implementation of the **Bisection method** for finding roots of a nonlinear equation.

- [`2_secant.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/2_secant.c)  
  Implementation of the **Secant method**.

- [`3_newton-raphson.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/3_newton-raphson.c)  
  Implementation of the **Newton–Raphson method**.

- [`4_fixed-point.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/4_fixed-point.c)  
  **Fixed-point iteration** method.

- [`5_horner.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/5_horner.c)  
  **Horner’s method** for efficient evaluation of polynomials (and often used for root-finding support).

---

### 2. Interpolation & Curve Fitting

- [`6_lagrance-interpolation.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/6_lagrance-interpolation.c)  
  **Lagrange interpolation** to estimate values between known data points.

- [`7_newton-interpolation.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/7_newton-interpolation.c)  
  **Newton’s divided difference interpolation** method.

- [`8_least square.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/8_least%20square.c)  
  **Least squares** curve fitting (best fit line / curve for given data).

---

### 3. Numerical Integration

- [`9_trapezoidal.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/9_trapezoidal.c)  
  **Trapezoidal rule** for numerical integration.

- [`10_simpsons .c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/10_simpsons%20.c)  
  **Simpson’s rule(s)** for numerical integration (e.g., 1/3, 3/8 depending on implementation).

---

### 4. Systems of Linear Equations & Matrix Methods

- [`11-gauss-elimi.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/11-gauss-elimi.c)  
  **Gauss elimination method** for solving systems of linear equations.

- [`12-gauss-jordan.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/12-gauss-jordan.c)  
  **Gauss–Jordan elimination** method.

- [`13-Dolittle.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/13-Dolittle.c)  
  **Doolittle’s method** (LU decomposition).

- [`14-Cholesky.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/14-Cholesky.c)  
  **Cholesky decomposition** for symmetric positive definite matrices.

- [`15-jacobi.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/15-jacobi.c)  
  **Jacobi iterative method** for solving linear systems.

- [`16-Gauss-Seidel.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/16-Gauss-Seidel.c)  
  **Gauss–Seidel iterative method**.

- [`17-eigen value and vector.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/17-eigen%20value%20and%20vector.c)  
  Numerical computation of **eigenvalues and eigenvectors** (e.g., power method).

---

### 5. Differential Equations (ODEs & BVPs)

- [`18_euler,s differential.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/18_euler,s%20differential.c)  
  **Euler’s method** for solving first-order ordinary differential equations (IVP).

- [`19_heuns.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/19_heuns.c)  
  **Heun’s method** (improved Euler / predictor-corrector).

- [`20_shooting.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/20_shooting.c)  
  **Shooting method** for boundary value problems (BVPs).

---

### 6. Partial Differential Equations (PDEs)

- [`21_laplacian.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/21_laplacian.c)  
  Numerical solution of **Laplace’s equation** using finite difference methods.

- [`22_poisson.c`](https://github.com/Anuragbhtri019/Numericalmethod_labs/blob/main/22_poisson.c)  
  Numerical solution of **Poisson’s equation** using finite difference methods.

---

## 🧮 Summary of Numerical Methods

This repository gives working C implementations for:

- **Root Finding:** Bisection, Secant, Newton–Raphson, Fixed-point iteration, Horner’s support for polynomials  
- **Interpolation & Fitting:** Lagrange, Newton divided difference, Least squares  
- **Numerical Integration:** Trapezoidal, Simpson’s rule  
- **Linear Systems:** Gauss elimination, Gauss–Jordan, LU (Doolittle), Cholesky, Jacobi, Gauss–Seidel  
- **Eigen Problems:** Eigenvalues and eigenvectors (iterative method)  
- **ODEs:** Euler’s method, Heun’s method, Shooting method for BVPs  
- **PDEs:** Laplace and Poisson equations (finite differences)

These cover almost all standard topics of a **Numerical Methods** course in BSc CSIT (3rd semester).

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Anuragbhtri019/Numericalmethod_labs.git
cd Numericalmethod_labs
```

### 2. Compile and Run (Using GCC)

Each file is a separate C program. You can compile and run any program like this:

```bash
# Example: Bisection method
gcc 1_bisection.c -o bisection
./bisection

# Secant method
gcc 2_secant.c -o secant
./secant

# Gauss elimination
gcc 11-gauss-elimi.c -o gauss_elimination
./gauss_elimination
```

On Windows (PowerShell / CMD with MinGW or similar):

```bash
gcc 1_bisection.c -o bisection.exe
bisection.exe
```

> Note: Some programs may require you to enter input values (initial guesses, matrix size, step size, etc.) from the console. Follow the prompts displayed when you run each executable.

---

## 📂 Repository Structure

```text
Numericalmethod_labs/
├─ 1_bisection.c
├─ 2_secant.c
├─ 3_newton-raphson.c
├─ 4_fixed-point.c
├─ 5_horner.c
├─ 6_lagrance-interpolation.c
├─ 7_newton-interpolation.c
├─ 8_least square.c
├─ 9_trapezoidal.c
├─ 10_simpsons .c
├─ 11-gauss-elimi.c
├─ 12-gauss-jordan.c
├─ 13-Dolittle.c
├─ 14-Cholesky.c
├─ 15-jacobi.c
├─ 16-Gauss-Seidel.c
├─ 17-eigen value and vector.c
├─ 18_euler,s differential.c
├─ 19_heuns.c
├─ 20_shooting.c
├─ 21_laplacian.c
├─ 22_poisson.c
└─ README.md
```

All programs are in the root directory for simplicity.

---

## 🎯 Purpose / Learning Objective

The main aim of this repository is to:

- Provide simple, readable **C implementations** of numerical algorithms  
- Help **BSc CSIT 3rd sem** students understand how numerical methods are implemented in code  
- Serve as a quick reference for lab work, assignments, and exam preparation

If you are using this for study:

- Try to re-implement the algorithms yourself after reading the code  
- Experiment with different input values and analyze **convergence** and **errors**

---

## 📝 Notes & Improvements

- Some filenames contain spaces or punctuation (for example: `10_simpsons .c`, `8_least square.c`, `18_euler,s differential.c`).  
  - When compiling from the terminal, wrap such filenames in quotes, e.g.:

    ```bash
    gcc "10_simpsons .c" -o simpsons
    ./simpsons
    ```

- You can also rename the files locally to remove spaces for easier compilation.

---

## 👤 Author

**Anurag Bharti**  
GitHub: [Anuragbhtri019](https://github.com/Anuragbhtri019)

> Description: *“its about all the program mostly used in Bsc CSIT ,3rd sem Numerical Method .”*

---

## 📄 License
Free to use under the MIT license  
By default, all rights are reserved by the author.  
