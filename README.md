# Project README: Mathematical Operations and Algorithms in Java

This project comprises a collection of Java classes focused on fundamental mathematical structures, numerical operations, and algorithmic sorting.

---

## 🛠 Project Components

The project is divided into specialized modules handling different mathematical domains and logic.

### 1. Numerical Operations (`SimpleNumericalOperations.java`)

* **Core Logic**: Implements basic arithmetic and value checking.
* **Methods**: Includes `add` for summation, and parity/sign checks like `isPositive` and `isNegative`.
* **Verification**: Tested using JUnit to ensure correct handling of positive numbers, negative numbers, and zero.

### 2. Polynomial Arithmetic (`Polynomial.java`)

* **Structure**: Represents polynomials using an array of integer coefficients.
* **Operations**: Supports adding and multiplying polynomials, as well as calculating derivatives.
* **Evaluation**: Features an `evaluate(double x)` method to calculate the polynomial's value at a specific point.
* **Verification**: Includes comprehensive tests for addition, multiplication, and derivative accuracy.

### 3. Matrix Algebra (`Matrix.java`)

* **Structure**: Uses 2D integer arrays (`int[][]`) to represent mathematical matrices.
* **Algebraic Operations**: Implements matrix addition, multiplication, and transposition.
* **Validation**: Enforces strict dimensional requirements; for example, addition requires identical dimensions, and multiplication requires matching inner dimensions.
* **Verification**: Tested for correct calculation results and proper exception handling for illegal dimensions.

### 4. Complex Number Management (`Cplx.java`)

* **Structure**: Defines complex numbers with `re` (real) and `im` (imaginary) double-precision components.
* **Arithmetic**: Supports addition (`add`), subtraction (`sub`), and multiplication (`mul`).
* **Assignment Operations**: Includes "Ass" variants (e.g., `addAss`, `subAss`) that modify the current object instance and return `this`.
* **Formatting**: Features a `toString` method that formats numbers as `re + imi` (e.g., `2.0 + 3.0i`).

### 5. Algorithmic Logic (`Main.java`)

* **BogoSort**: Implements the BogoSort (random sort) algorithm to sort integer arrays.
* **Utility Methods**: Includes helper functions for checking if an array is sorted (`isSorted`), shuffling array elements (`shuffle`), and generating test data.

---

## 🚀 How to Use

### Setup & Compilation

1. **Requirement**: Ensure a Java Development Kit (JDK) is installed.
2. **Organization**: Place the source files within a package named `practice_7`.
3. **Compilation**: Compile the `.java` files using a standard Java compiler (e.g., `javac practice_7/*.java`).

### Execution

* **Main Program**: Run the `Main` class to see the BogoSort algorithm in action. It will generate a random array, print its state "Przed sortowaniem" (before sorting), perform the sort, and print it "Po sortowaniu" (after sorting).

### Testing

* **JUnit 5**: The project includes several test classes (`SimpleNumericalOperationsTest`, `PolynomialTest`, `MatrixTest`, `CplxTest`) designed for the JUnit 5 framework.
* **Run Tests**: Execute these classes within a compatible IDE (like IntelliJ or Eclipse) or via the command line to verify the integrity of the mathematical logic.

---

## 📂 File Manifest

* `SimpleNumericalOperations.class`: Basic arithmetic logic.
* `Polynomial.class`: Array-based polynomial math.
* `Matrix.class`: 2D array matrix operations.
* `Cplx.class`: Complex number data structure and math.
* `Main.class`: Sorting algorithm entry point.
