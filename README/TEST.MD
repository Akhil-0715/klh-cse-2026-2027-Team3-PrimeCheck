PrimeForge

Large Prime Generation & Validation Platform

DSA-3 Project


Project Title

Large Prime Generation and Validation using Randomized Algorithms


Team Members

1. K. Sai Akhil - 2520030021
2. Mohd. Rehan - 2520030066
3. T. Hasini - 2520030102


Supervisor

Dr. Ch Anuradha


Abstract

PrimeForge is a web-based project that focuses on generating and checking large prime numbers. The main part of the project is the Miller-Rabin Primality Test, which is used to check whether a given large number is prime or composite with high probability. The system will support numbers up to 1024 bits and will show the result, confidence level and time taken by the algorithm. As we continue developing the project, we plan to add prime number generation, performance comparison, randomized algorithms and parallel processing. The project is being developed as part of our DSA-3 course to apply the algorithms we learn to a practical application.


Introduction

Checking whether a very large number is prime can take a lot of time using simple methods. This becomes more difficult when the number contains hundreds or thousands of bits.

PrimeForge uses the Miller-Rabin Primality Test to solve this problem. It is a randomized algorithm that can test large numbers efficiently and give a result with a high level of confidence.

The project will be developed as a web-based Java application where users can enter large numbers and view the testing result and performance information.


Problem Statement

Determining whether a very large integer is prime or composite can be computationally expensive when traditional methods are used. There is a need for an efficient approach that can handle large integers, including values up to 1024 bits. PrimeForge addresses this problem by using the Miller-Rabin Primality Test, a randomized algorithm that can determine primality with a high level of confidence. The system will also provide the execution time and confidence level of the result through a web-based service.


Objectives

1. Implement the Miller-Rabin Primality Test in Java.
2. Test large integers up to 1024 bits.
3. Generate large prime number candidates.
4. Display the prime or composite result.
5. Calculate the confidence level of the result.
6. Measure and display execution time.
7. Compare the performance of different approaches.
8. Apply randomized algorithm concepts.
9. Explore parallel processing for prime testing.
10. Provide the features through a web-based application.


Literature Survey

Previous research on primality testing has led to several algorithms for checking large numbers.

1. Miller (1976) proposed a primality testing approach based on modular arithmetic.

2. Rabin (1980) developed a probabilistic version of the Miller test, which forms the basis of the Miller-Rabin test.

3. Miller-Rabin became a widely used probabilistic method because it can test large integers efficiently.

4. Large prime numbers and efficient primality testing are also important in areas such as public-key cryptography.

Based on these studies, our project uses Miller-Rabin as the main algorithm and focuses on its implementation, performance and practical use through a web application.


Methodology

The project will be developed step by step.

1. The user provides a large integer as input.
2. The system checks the input and its bit length.
3. The Miller-Rabin algorithm is applied to the number.
4. Random bases are selected for the required number of iterations.
5. The algorithm determines whether the number is composite or probably prime.
6. The confidence level is calculated based on the number of iterations.
7. The execution time is recorded.
8. The result is displayed through the web interface.
9. Large prime generation will be added by generating random candidates and testing them.
10. Other modules such as benchmarking, randomized hashing, reservoir sampling and parallel testing will be added later.


Algorithms and Data Structures

Miller-Rabin Primality Test

Used as the main algorithm for checking whether a large number is probably prime.

Modular Exponentiation

Used during the Miller-Rabin test to efficiently calculate powers under a modulus.

BigInteger

Java's BigInteger class will be used to work with integers larger than normal primitive data types.

Random Number Generation

Random values will be used for selecting bases and generating prime candidates.

Parallel Processing

Multiple independent tests can be processed in parallel to study the effect on execution time.


Planned Modules

1. Large Prime Validation

Check whether a large number is prime or composite using Miller-Rabin.

2. Large Prime Generation

Generate random large numbers and test them until a probable prime is found.

3. Confidence Analysis

Show how the number of Miller-Rabin iterations affects the confidence of the result.

4. Algorithm Benchmarking

Measure execution time for different input sizes and different numbers of iterations.

5. Deterministic vs Randomized Testing

Compare the randomized approach with other suitable primality testing methods.

6. Randomized Hashing

Implement a randomized hashing technique as an additional DSA module.

7. Reservoir Sampling

Implement reservoir sampling and demonstrate its use with a stream of values.

8. Parallel Prime Testing

Run independent prime tests in parallel and compare the performance with normal execution.

9. Performance Dashboard

Display results such as input size, primality result, confidence, iterations and execution time.


Hardware Requirements

1. Processor: Intel Core i3 or equivalent and above
2. RAM: Minimum 4 GB
3. Storage: Minimum 5 GB free space
4. Standard laptop or desktop
5. Internet connection for GitHub and web application testing


Software Requirements

1. Operating System: Windows / Linux / macOS
2. Java JDK 17 or above
3. VS Code / IntelliJ IDEA / Eclipse
4. Spring Boot
5. Maven
6. Git
7. GitHub
8. Chrome / Edge / Firefox


Technologies Used

1. Programming Language: Java
2. Backend: Spring Boot
3. Frontend: HTML, CSS, JavaScript
4. Large Integer Handling: Java BigInteger
5. Version Control: Git and GitHub


Dataset

No external dataset is required for this project.

The system will work with numbers entered by the user and numbers generated by the application.


Setup and Execution

Requirements

Java JDK 17 or above and Git should be installed.

Clone the Repository

git clone https://github.com/Akhil-0715/klh-cse-2026-2027-Team3-PrimeCheck.git

Go to the project folder:

cd klh-cse-2026-2027-Team3-PrimeCheck

The setup instructions will be updated as the Java backend and web application are developed.


Course Information

Course: Data Structures and Algorithms - 3
Academic Year: 2026-2027
Team: 3


Current Phase and Status

Phase 1 - Project Setup

Completed

1. Project topic selected
2. Project title finalized
3. Git repository initialized
4. GitHub repository created
5. README created
6. Team members added
7. Supervisor added
8. Project modules planned

To Do

1. Project folder structure
2. Miller-Rabin implementation
3. Prime validation
4. Confidence calculation
5. Large prime generation
6. Algorithm benchmarking
7. Randomized hashing
8. Reservoir sampling
9. Parallel prime testing
10. Backend development
11. Frontend development
12. Performance dashboard
13. Testing
14. Final documentation


Future Scope

1. Support numbers larger than 1024 bits.
2. Add more primality testing algorithms.
3. Improve performance using parallel processing.
4. Add graphs for performance comparison.
5. Improve the web interface.
6. Add more randomized algorithm demonstrations.
7. Explore the use of large prime generation in cryptography.


Results

The developed system is expected to identify whether a large integer is prime or composite using the Miller-Rabin Primality Test. It will show the result, confidence level, number of iterations and execution time. Further development will include large-prime generation, performance comparison and parallel processing.


Conclusion

PrimeForge aims to provide a simple and efficient way to test large numbers for primality using the Miller-Rabin Primality Test. The project will demonstrate the use of randomized algorithms and large integer processing in a practical application. Additional modules for prime generation, benchmarking and parallel processing will be added as the project develops.


Project Status

Current Status: Initial Setup

The GitHub repository and project documentation have been created. The next step is to set up the Java project and start implementing the Miller-Rabin Primality Test.