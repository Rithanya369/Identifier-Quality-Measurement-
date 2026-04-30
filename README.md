 Identifier Quality Measurement 

 Project Overview

This project analyzes the quality of identifier names (such as variable names) used in a program. It evaluates readability by computing the **average identifier length** and detecting poor naming practices.

 Objective

* To process identifier names using C
* To compute **Average Identifier Length**
* To identify poor naming using a flag: **Is_Poor_Naming**

 Technologies Used

* **Programming Language:** C
* **Concepts:**

  * Structures
  * Arrays
  * Strings (`strlen`)
  * Conditional statements

 How It Works

1. Input

* Number of identifiers
* Identifier names (strings)

2. Data Processing

* Identifiers are stored in a structure array
* Length of each identifier is calculated

3. Feature Computation

* **Average Identifier Length = Total Length / Number of Identifiers**

4. Flag Generation

* If any identifier length:

  * Less than 3 OR greater than 15
    → `Is_Poor_Naming = YES`
* Otherwise → `NO`

5. Output

* Displays:

  * Total Identifiers
  * Average Length
  * Naming Quality Flag

 How to Run

1. Open the `.c` file in Dev-C++ / Code::Blocks
2. Compile the program
3. Run the executable
4. Enter inputs as prompted

 Sample Input

Enter number of identifiers: 5
a total sum x averageValue

 Sample Output

Total Identifiers: 5
Average Identifier Length: 4.40
Is_Poor_Naming: YES

 Feature Justification

* Short names (<3) are unclear (e.g., `x`, `a`)
* Long names (>15) reduce readability
* Acceptable range: **3 to 15 characters**

 File Structure
 
```
RegNo_Name_HoT.c
RegNo_Name_Output.png
RegNo_Name_Explanation.pdf
README.md
```

 Conclusion

This program demonstrates how simple string analysis can be used to evaluate code readability. It converts raw identifier data into meaningful insights using basic C programming techniques.


