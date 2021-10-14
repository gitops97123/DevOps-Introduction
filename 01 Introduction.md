#   Start DevOps Courses Introduction 

## Introduction

SDLC process involves collection of software requirements from the customer, development of the software by the development team, and testing of functionalities of the software by the testers, is well known. 

Introduction in 2009 by patrick Debios, the DevOps is a practical field that covers several disciplines while understanding the funcational as well as the technical aspects of software development in an organisation in DevOps is derived by joining two terms "Development" and "Operations". DevOps is a philosophy which says that a single team of engineers can develop the software right from scratch to its installation, collecting feedback and performing updates, if required. 


 ## Session Objectives


 * Discuss the tradional approach to software testing 
 * Describe software testing and its methods 
 * Explain agile methodology 
 * Describe DevOps 


# SDLC 

The SDLC is used in system or software engineering to describe the phases through which the software should go before it is completely developed. the phases of the SDLC focus on plannning, designing, building, testing, and finally, delivering the complete software product. 

![new repository](https://github.com/gitops97123/DevOps-Introduction/blob/main/icons/01.png?raw=true)

## Software Testing 
 The software can be tested in the following two ways: 

* **Manual Testing**: In this process, software is tested manually with the perception of the end user's requirements. it checks for all the planned features, executes test cases without using automation tools and generates reports.
  
* **Automation Testing**: In this process, software testing is done automatically by using automation tools, test scripts are executed, and test results are generated automation tools. Examples of popular testing tools are - Selenium and Quick Test Professionals. 

## Testing Methods

* **Static Testing**: Testing of the code is performed without executing the program. it can uncover defects such as unclear or mislaid requirements, defects in modelling, complex coding, and nonconformity in quality standards. it is a static way of inspecting documentation and files, it involves inspection, review and walkthrough. 

* **Dynamic testing**: It checks the funcational behaviour of the system, such as its memory usage, CPU usage, and overall performance. it provides techniques to start testing and identify and fix detects. Testing is done to ensure that the software system works in accordance with the customer requirement. 
  
         Test Case ----> Test Environment -----> Test Case -----> Error Reporting -----> Test Closure 
          Design         Setup                   Execution

* **Black-Box Testing**: It is a software method which tests a software product for its functionality without concentrating on its internal structure code. it is also known as input/output testing, data-driver testing, or specification testing. In black-box testing, testers are not concerned with the internal structure or behaviour of a program. 

                                        Black-Box
                                         Testing 
                                           |
        ___________________________________|_____________________________________________
        |              |                   |                |              |            |
        Equivalence   Boundary        state transition  Logic-Based    All Pair      Use Case-
        Partitioning  Value Analysis    Testing         Testing        Testing       Based Testing


* **White-Box Testing**: It is also called glass box, clear box, or structural testing. In  white-box testing, the system is viewed as a white box.

    In white-box testing, you can inspect the internal components of a system. In white-box testing, the actual implementation of the system is tested. Unit testing is majorly related to white-box testing; however, white-box testing can be applied to integration and system testing as well. The main difference between white-box tesing and black-box testnig is that white-box testing is based on the analysis of the internal structure of the system or its components while black-box testing is concerned with only the functionality of the system. 

                                    White Box Testing 
            __________________________________|___________________
           |                    |             |                  |
            Statement       Decision    conditional            Path 
            Testing          Testing     Testing               Testing

* **Functional Testing**: Functional testing tests the input/output behaviour  of a system. It checks the functional requirements of a system. The functional requirements specify the behaviour of the system. They define what a system must be able to do. It is also known as specification-based testing as it tests against fixed specfications. It is based on functions and features and their interoperability with the specific systems. 
* **Non-Funcational Testing**: Non-functional requirements of software do not describe how the software functions, instead they define the attributes of the behaviour of the system. They define what the quality of system output should be. These requirements impact customer and user satisfaction. Non-Functional testing evaluates non-funcational requirement such as usability, performance, and efficiency.

# Testing Levels 

* **Unit Testing**: Unit Testing performms testing on a single software component or unit at a time. In unit testing, the tests are performed to check the functioning of software modules, programs, objects, classes, etc. that are separatley testable. 
* **Integration Testing**: When developers or testers create a group of components to form larger subsystems, this connection of components is called integration. The two integration testing are: 
  * **Component Integration Testing**:  It is performed when the components are integrated together and the interactions between them are tested. 
  * **System Integration Testing**: System integration testing is performed to check the integration between different systems or between hardware and software. 
* **System Testing**: when integration testing is executed, the next level of testing is system testing. it is used to check if the finalised integrated product meets the specified requirements. 


# Introduction to Agile Methodology 

![new repository](https://github.com/gitops97123/DevOps-Introduction/blob/main/icons/02.jpg?raw=true)

Agile testing is a rapid process of software testing that aims towards increasing the flexibility and effectiveness of the workflow. In this model, the software undre development is divided into separate working/functional modules. Each module is developed/tested as an iteration. The defects that are discovered in an iteration are fixed in the next/subsequent iteration. 

## Agile Software Development Model 

The agile software development model uses the incremental method for developing target applications or software. the model uses iterations with model of developement is usually 1 to 4 weeks long. 

