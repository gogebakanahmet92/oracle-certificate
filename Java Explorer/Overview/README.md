# Overview

## Title and Objectives
- Explain Java Origins and Ecosystem
- Describe the Java Language
- Explore Java design mindset
- Describe common Java APIs
- Explain the use of Java in the Enterprise

## Java Origins and Ecosystem

- Origins and Evolution
    - A member of C-like family of programming languages
    - Originally designed for consumer electronics
    - Widely adopted across billions of devices, ranging from smartcards to supercomputers

- Ecosystem
    - Java Card
    - Java ME Micro-Edition
    - Java SE Standart-Edition
    - Java MP Micro-Profile
    - Java EE Enterprise-Edition

- Java is Cross Platform

    - Each Java Program only needs to be written and compiled once (Write Once Run Anywhere)
    - No platform-specific changes has to be applied to the source-code
    - A single, compiled version of a program can run on any platform
    - Java Programs are executed within a Java Virtual Machine (JVM)

## Java Language

- Code Structures 
    - Class, Package, Module 
- Syntax 
    - Java code is grouped into classes and classes contain methods and variables that fulfill their purposes
- Exception Handlind
    - Interrupt normal program execution when problem occurs
    - Decide what your program should do in case of an error
    - Write flexible code that can handle adverse circumstances

## Java Design

- Classes and Objects
    - A class represents a type of thing or concept
    - An object is an instance - a specific example of a class
- Reusing Code Through Inheritance
    - Reuse (inherit) attributes and behaviors across the class hierarchy
    - Top-level classes contain generic code reused by their descendants
    - Polymorphism
- Achieve Flexible Design
    - Interfaces
    - Enumerations
    - Generics
- Analysis, Design and Architecture
    - Use Unified Modelling Language (UML) to :
        - Analyze business requirements
        - Model code structure
        - Describe application deployment

## Java APIs

- Java Arrays and Collections
    - An array is a simple group of elements
    - The Collection API provides more flexible capabilities for managing group of elements
        - add, update, remove, search, rearrange

- Java Streams API
    - They efficiently filter, map and reduce large streams of data
    - They perform actions upon data using lambda expressions
    - Lambda expressions are a form of functional programming

- Java IO API
    - Transfer data through a series of interconnected streams
    - Read information from various sources - input direction
    - Write information to varius destinations - output direction

- Java Concurrency API
    - Takes advantages of multi-CPU-core architecture
    - Executes codes concurrently to achieve better performance and user experience

- Java Persistence API
    - Java Database Connectivity Protocol (JDBC) enables database connectivity and SQL statement execution
    - Java Persistence API (JPA) enables Java object-relational mappings
        - Application Logic, JPA, JDBC API provider neutral, Provider JDBC Driver (with native database protocol), Database any provider

- Java in Enterprise
    - Implement Web Services with Java
        - SOAP
            - Any Transport
            - XML
        - REST 
            - HTTP Transport
            - XML, JSON, Plain Text
    - Enterprise Java
        - Java EE Application Server 
            - WebLogic, JBoss, Tomcat
    - Java in Oracle Cloud
        - Developer Tools
        - Language and Frameworks
        - Cloud Native
        - Data Management
        - DevOps
        - Oracle Cloud Infrastructure