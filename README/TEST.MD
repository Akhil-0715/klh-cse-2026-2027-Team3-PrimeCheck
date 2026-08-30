# PrimeForge

### Large Prime Generation & Validation Platform

**DSA-3 Project**

## Project Title

**Large Prime Generation and Validation using Randomized Algorithms**

**Repository Name:** `klh-cse-2026-2027-Team3-PrimeCheck`

## Team Members

1. K. Sai Akhil - 2520030021
2. Mohd. Rehan - 2520030066
3. T. Hasini - 2520030102

## Supervisor

**Dr. Ch Anuradha**

## Abstract

PrimeForge is a web-based project that focuses on generating and checking large prime numbers. The main part of the project is the Miller-Rabin Primality Test, which is used to check whether a given large number is prime or composite with high probability. The system will support numbers up to 1024 bits and will show the result, confidence level and execution time. As we continue developing the project, we plan to add prime number generation, performance comparison, randomized algorithms and parallel processing. The project is being developed as part of our DSA-3 course to apply the algorithms we learn to a practical application.

## Introduction

Checking whether a very large number is prime can take a lot of time using simple methods. This becomes more difficult when the number contains hundreds or thousands of bits.

PrimeForge uses the Miller-Rabin Primality Test to solve this problem. It is a randomized algorithm that can test large numbers much faster and give a result with a high level of confidence.

The project will be developed as a web-based Java application where users can enter large numbers and view the testing result and performance information.

## Problem Statement

Determining whether a very large integer is prime or composite can be computationally expensive when traditional methods are used. There is a need for an efficient approach that can handle large integers, including values up to 1024 bits. PrimeForge addresses this problem by using the Miller-Rabin Primality Test, a randomized algorithm that can determine primality with a high level of confidence. The system will also provide the execution time and confidence level of the result through a web-based service.

## Objectives

- Implement the Miller-Rabin Primality Test in Java.
- Test large integers up to 1024 bits.
- Generate large prime number candidates.
- Display the prime or composite result.
- Calculate the confidence level of the result.
- Measure and display execution time.
- Compare the performance of different approaches.
- Apply randomized algorithm concepts.
- Explore parallel processing for prime testing.
- Provide the above features through a web-based application.

## Literature Survey

Previous research on primality testing has led to several algorithms for checking large numbers.

- **Miller (1976):** Proposed a primality testing approach based on modular arithmetic.
- **Rabin (1980):** Developed a probabilistic version of the Miller test, which forms the basis of the Miller-Rabin test used today.
- **Miller-Rabin:** Became a widely used probabilistic method because it can test large integers efficiently.
- **Cryptography research:** Large prime numbers and efficient primality testing are important in areas such as public-key cryptography.

Based on these studies, our project uses Miller-Rabin as the main algorithm and focuses on its implementation, performance and practical use through a web application.

## Methodology

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

## Algorithms and Data Structures

### Miller-Rabin Primality Test

Used as the main algorithm for checking whether a large number is probably prime.

### Modular Exponentiation

Used during the Miller-Rabin test to efficiently calculate powers under a modulus.

### BigInteger

Java's `BigInteger` class will be used to work with integers larger than the normal primitive data types.

### Random Number Generation

Random values will be used for selecting bases and generating prime candidates.

### Parallel Processing

Multiple independent tests can be processed in parallel to study the effect on execution time.

## Planned Modules

### 1. Large Prime Validation

Check whether a large number is prime or composite using Miller-Rabin.

### 2. Large Prime Generation

Generate random large numbers and test them until a probable prime is found.

### 3. Confidence Analysis

Show how the number of Miller-Rabin iterations affects the confidence of the result.

### 4. Algorithm Benchmarking

Measure execution time for different input sizes and different numbers of iterations.

### 5. Deterministic vs Randomized Testing

Compare the randomized approach with other suitable primality testing methods.

### 6. Randomized Hashing

Implement a randomized hashing technique as an additional DSA module.

### 7. Reservoir Sampling

Implement reservoir sampling and demonstrate its use with a stream of values.

### 8. Parallel Prime Testing

Run independent prime tests in parallel and compare the performance with normal execution.

### 9. Performance Dashboard

Display results such as input size, primality result, confidence, iterations and execution time.

## Hardware Requirements

- Processor: Intel Core i3 or equivalent and above
- RAM: Minimum 4 GB
- Storage: Minimum 5 GB free space
- Standard laptop or desktop
- Internet connection for GitHub and web application testing

## Software Requirements

- Windows / Linux / macOS
- Java JDK 17 or above
- VS Code / IntelliJ IDEA / Eclipse
- Spring Boot
- Maven
- Git
- GitHub
- Chrome / Edge / Firefox

## Technologies Used

- **Language:** Java
- **Backend:** Spring Boot
- **Frontend:** HTML, CSS, JavaScript
- **Large Integer Handling:** Java BigInteger
- **Version Control:** Git and GitHub

## Dataset

No external dataset is required for this project.

The system will work with numbers entered by the user and numbers generated by the application.

## Setup and Execution

### Requirements

Make sure Java JDK 17 or above and Git are installed.

### Clone the Repository

```bash
git clone https://github.com/Akhil-0715/klh-cse-2026-2027-Team3-PrimeCheck.git