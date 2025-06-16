# APC
# Arbitrary-Precision-Calculator

Welcome to the Arbitrary Precision Calculator project! This calculator is designed to handle very large numbers with precision beyond the limits of standard data types. By leveraging the double linked list data structure and advanced C programming techniques, this calculator can perform arithmetic operations on numbers of arbitrary length.

FEACTURES
1. Addition: Perform addition on arbitrarily large numbers.
2. Subtraction: Subtract one arbitrarily large number from another.
3. Multiplication: Multiply large numbers with precise results.
4. Division: Divide large numbers and obtain both quotient and remainder.

DATA STRUCTURES

Double Linked List
We use a double linked list to store each digit of the large numbers. This allows efficient insertion, deletion, and traversal of digits, which is crucial for performing arithmetic operations on numbers with many digits.
1. Node: Each node in the list represents a four digit.
2. List: The list can grow dynamically to accommodate numbers of any length.

ADVANCED C TECHNIQUES
This project utilizes several advanced features of C to manage memory and optimize performance:
1. Dynamic Memory Allocation: To handle numbers of varying lengths.
2. Pointer Manipulation: For efficient traversal and modification of the linked list.
3. Custom Data Structures: Implementation of the double linked list for digit storage.
4. Error Handling: Robust handling of edge cases and invalid input.

EXAMPLE EXECUTION
To compile and run this project, you need a C compiler (GCC recommended)
./a.out
Enter input (num1 operator num2) : 6464667478339292928272 + 7774747746363637383393030
Result : 7781212413841976676321302
Do you want to continue (y/n) : y
Enter input (num1 operator num2) : -65464646467438383833847474 - 676733373738352424353
Result : -6546532320812122186271827
Do you want to continue (y/n) : y
Enter input (num1 operator num2) : 63535435363894242584849 * 53434353678333
Result : 339497492434119088964292717305376717
Do you want to continue (y/n) : y
Enter input (num1 operator num2) : 6464647484838625363737 / 6363633
Result : 1015873713150746
Do you want to continue (y/n) : n
CONTRIBUTING  :   Contributions are welcome! If you have suggestions, bug reports, or want to contribute improvements, please submit a pull request.
CONTACT   :   For any inquiries or feedback, feel free to contact NANDHU MADHU via email at nandhumadhu142@gmail.com.



