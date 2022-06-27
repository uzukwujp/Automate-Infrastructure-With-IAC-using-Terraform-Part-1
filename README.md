# Automate-Infrastructure-With-IAC-using-Terraform-Part-1
In this project we began the process of automating the infrastructure need to deploy the appilication in [project 15](https://github.com/uzukwujp/Darey.io-Internship/blob/main/project-fifteen.md)

This is a nice Introduction Infrastructure As Code(IAC) an important ternant of Devops practice. IAC can be done with several tools but in this project we made use of Terraform.

##The secrets of writing quality Terraform code

The secret recipe of a successful Terraform projects consists of:

- Your understanding of your goal (desired AWS infrastructure end state)
- Your knowledge of the IaC technology used (in this case – Terraform)
- Your ability to effectively use up to date Terraform documentation 

As you go along completing this project, you will get familiar with Terraform-specific terminology, such as:

- Attribute
- Resource
- Interpolations
- Argument
- Providers
- Provisioners
- Input Variables
- Output Variables
- Module
- Data Source
- Local Values
- Backend

Make sure you understand them and know when to use each of them.

Another concept you must know is data type. This is a general programing concept, it refers to how data represented in a programming language and defines how a compiler or interpreter can use the data. Common data types are:

- Integer
- Float
- String
- Boolean, etc.


## Best practices

Ensure that every resource is tagged using multiple key-value pairs. You will see this in action as we go along.
Try to write reusable code, avoid hard coding values wherever possible. (For learning purpose, we will start by hard coding, but gradually refactor our work to follow best practices).

