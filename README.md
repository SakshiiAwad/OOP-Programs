# Object-Oriented Programming (OOP) – C++

A collection of C++ programs based on Object-Oriented Programming concepts and real-time applications.

## 👩‍🎓 Student Information

| Details | Information |
|---|---|
| **Student Name** | Sakshi Awad |
| **PRN** | 126UAD2050 |
| **Class / Division** | F |
| **Course Name** | Artificial Intelligence & Data Science (AIDS) |
| **Subject** | Object-Oriented Programming (OOP) |
| **Programming Language** | C++ |

---

## 📖 About This Repository

This repository contains C++ programs developed as part of the Object-Oriented Programming (OOP) course. The programs are organized unit-wise for easy understanding, practice, and reference.

The repository also includes **Realtime Examples** that demonstrate the practical application of OOP concepts in real-world scenarios.

---

## 🎯 Objective

The objective of this repository is to understand and implement fundamental and advanced Object-Oriented Programming concepts using C++ through practical programs and real-time applications.

---

## 📂 Repository Structure

```text
OOP/
│
├── README.md
│
├── Unit1/
│   ├── 01_Basic_Data_Types.cpp
│   │   └── Stores student roll number, grade, and fee using basic data types.
│   │
│   ├── 02_If_Else.cpp
│   │   └── Checks whether a student has passed or failed using if-else.
│   │
│   ├── 03_Loop_Array.cpp
│   │   └── Uses a loop to display the marks of five students stored in an array.
│   │
│   ├── 04_Functions.cpp
│   │   └── Demonstrates a reusable addition function.
│   │
│   ├── 05_Class_Object.cpp
│   │   └── Demonstrates classes and objects using student details.
│   │
│   ├── 06_Constructor_Destructor.cpp
│   │   └── Demonstrates automatic object initialization and cleanup.
│   │
│   ├── 07_Static_Member.cpp
│   │   └── Counts the number of objects created using a static member.
│   │
│   └── 08_Inline_Friend_Function.cpp
│       └── Demonstrates inline and friend functions for accessing class data.
│
├── Unit2/
│   │
│   ├── 01_Basic_Single_Inheritance.cpp
│   │   └── Demonstrates single inheritance using Person and Student classes.
│   │
│   ├── 02_Protected_Member_Access.cpp
│   │   └── Demonstrates access to protected members from a derived class.
│   │
│   ├── 03_Public_vs_Private_Inheritance.cpp
│   │   └── Demonstrates the effect of public and private inheritance on accessibility.
│   │
│   ├── 04_Multilevel_Inheritance.cpp
│   │   └── Demonstrates a three-level inheritance hierarchy using Person, Employee, and Manager.
│   │
│   ├── 05_Hierarchical_Inheritance.cpp
│   │   └── Demonstrates multiple derived classes using Vehicle as a common base class.
│   │
│   ├── 06_Multiple_Inheritance.cpp
│   │   └── Demonstrates inheritance from two base classes using academic and sports records.
│   │
│   ├── 07_Multiple_Inheritance_Ambiguity.cpp
│   │   └── Demonstrates how to resolve ambiguity when two base classes contain methods with the same name.
│   │
│   ├── 08_Constructor_Destructor_Order.cpp
│   │   └── Demonstrates the construction and destruction order of inherited objects.
│   │
│   ├── 09_Parameterized_Base_Constructor.cpp
│   │   └── Demonstrates initialization of a parameterized base class from a derived constructor.
│   │
│   ├── 10_Function_Overriding.cpp
│   │   └── Demonstrates overriding a virtual member function in a derived class.
│   │
│   ├── 11_Abstract_Class.cpp
│   │   └── Demonstrates the use of an abstract class with a pure virtual function.
│   │
│   ├── 12_Virtual_Base_Class_Diamond_Inheritance.cpp
│   │   └── Demonstrates solving diamond inheritance ambiguity using a virtual base class.
│   │
│   ├── 13_Friend_Class.cpp
│   │   └── Demonstrates access to private data using a friend class.
│   │
│   ├── 14_Nested_Class.cpp
│   │   └── Demonstrates creation and use of a nested class.
│   │
│   ├── 15_Vehicle_Rental_System.cpp
│   │   └── Implements an inheritance-based vehicle rental system.
│   │
│   └── 16_Employee_Payroll_System.cpp
│       └── Implements an employee salary system using an abstract class and derived classes.
│
├── Unit3/
│   │
│   ├── 01_Function_Overloading.cpp
│   │   └── Demonstrates compile-time polymorphism using function overloading.
│   │
│   ├── 02_Area_Calculator_Function_Overloading.cpp
│   │   └── Calculates areas of different shapes using overloaded functions.
│   │
│   ├── 03_Unary_Minus_Operator_Overloading.cpp
│   │   └── Demonstrates unary minus operator overloading for a user-defined class.
│   │
│   ├── 04_Prefix_Postfix_Increment.cpp
│   │   └── Demonstrates prefix and postfix increment operator overloading.
│   │
│   ├── 05_Complex_Number_Addition.cpp
│   │   └── Demonstrates binary + operator overloading for adding complex numbers.
│   │
│   ├── 06_Relational_Operator_Overloading.cpp
│   │   └── Demonstrates relational operator overloading for comparing objects.
│   │
│   ├── 07_Friend_NonMember_Operator_Overloading.cpp
│   │   └── Demonstrates operator overloading using a friend non-member function.
│   │
│   ├── 08_Base_Pointer_Without_Virtual.cpp
│   │   └── Demonstrates static binding using a base pointer without a virtual function.
│   │
│   ├── 09_Base_Pointer_With_Virtual.cpp
│   │   └── Demonstrates run-time polymorphism using a virtual function and base pointer.
│   │
│   ├── 10_Base_Reference_With_Virtual.cpp
│   │   └── Demonstrates run-time polymorphism using a base-class reference.
│   │
│   ├── 11_Abstract_Class_Pure_Virtual_Function.cpp
│   │   └── Demonstrates abstract classes and pure virtual functions.
│   │
│   ├── 12_Polymorphic_Shape_Pointers.cpp
│   │   └── Processes different derived objects through a common abstract base interface.
│   │
│   ├── 13_Virtual_Destructor.cpp
│   │   └── Demonstrates safe destruction of derived objects through a base pointer.
│   │
│   ├── 14_Object_Slicing.cpp
│   │   └── Demonstrates object slicing and how references can avoid it.
│   │
│   ├── 15_Payment_Processing_System.cpp
│   │   └── Implements a real-world polymorphic payment processing system.
│   │
│   └── 16_Employee_Payroll_Mini_Project.cpp
│       └── Implements salary calculation using abstract classes and run-time polymorphism.
│
└── Realtime Examples/
    │
    ├── UnitI/
    │   │
    │   ├── 01_Smart_Agriculture_Sensor_Monitor.cpp
    │   │   └── Monitors soil moisture sensor readings using classes and objects.
    │   │
    │   ├── 02_Student_Attendance_Management.cpp
    │   │   └── Calculates student attendance percentage using OOP concepts.
    │   │
    │   └── 03_ECommerce_Product_Catalog.cpp
    │       └── Manages product details and tracks active product objects using static members.
    │
    ├── UnitII/
    │   │
    │   ├── 01_Employee_Payroll_System.cpp
    │   │   └── Calculates salaries for different employee types using inheritance.
    │   │
    │   ├── 02_Digital_Payment_Gateway.cpp
    │   │   └── Demonstrates different payment modes using an abstract interface.
    │   │
    │   └── 03_Vehicle_Fleet_Management.cpp
    │       └── Manages trucks, vans, and bikes using inheritance and function overriding.
    │
    └── UnitIII/
        │
        ├── 01_CAD_Shape_Drawing_System.cpp
        │   └── Calculates and processes different shapes using runtime polymorphism.
        │
        ├── 02_Complex_Number_Calculator.cpp
        │   └── Performs complex number calculations using operator overloading.
        │
        └── 03_Input_Validation_Service.cpp
            └── Validates different types of user data using function overloading.
