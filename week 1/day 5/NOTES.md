# Salesforce Day 5 Notes

## Introduction

Today’s session focused on Apex Programming in Salesforce. Until now, I learned how Salesforce automation can be built using no-code tools like Flows and Process Automation.

However, not every business requirement can be solved using clicks and drag-and-drop tools alone. Some complex business logic requires programming.

Salesforce provides Apex, a programming language used to build custom business logic and advanced automation inside the Salesforce platform.

Today I learned:
- What Apex is
- Why programming is needed in Salesforce
- Basic Apex syntax
- Difference between declarative and programmatic development
- How Apex connects to business logic

---

# What is Apex?

Apex is Salesforce’s programming language used to develop custom business logic and advanced automation.

It is similar to Java and is specially designed for the Salesforce platform.

Using Apex, developers can:
- Create custom logic
- Automate complex processes
- Validate data
- Integrate external systems
- Perform database operations
- Handle advanced business requirements

Apex runs on Salesforce servers and works securely within the Salesforce environment.

---

# Why Salesforce Needs Programming

Salesforce provides many no-code tools like:
- Flow Builder
- Validation Rules
- Formula Fields
- Reports
- Process Automation

These tools are useful for simple business requirements.

However, some real-world business processes become too complex for declarative tools alone.

In such situations, Apex programming becomes necessary.

---

# Example of Complex Business Logic

## Scenario

A college management system wants:
- Different fee calculations for different student categories
- Scholarship eligibility checks
- Attendance-based warning systems
- Automatic approval processes
- Integration with external payment systems

These requirements involve:
- Multiple conditions
- Complex calculations
- Advanced validations
- External integrations

Such logic becomes difficult using only clicks and flows.

Apex helps developers implement these advanced requirements efficiently.

---

# What is Declarative Development?

Declarative development means building applications using clicks, configuration, and no-code tools without writing code.

Salesforce declarative tools include:
- Flow Builder
- Validation Rules
- Formula Fields
- Reports
- Process Builder

---

## Advantages of Declarative Development

- Faster development
- Easy to maintain
- No coding knowledge required
- Suitable for simple automation
- Business users can configure processes easily

---

## Example

Automatically sending a welcome email when a student record is created using Record-Triggered Flow.

This can be done without programming.

---

# What is Programmatic Development?

Programmatic development means writing code to build custom functionality.

In Salesforce, Apex is used for programmatic development.

It is mainly used when:
- Business logic becomes complex
- Advanced automation is needed
- External integrations are required
- Custom processing is necessary

---

## Advantages of Programmatic Development

- Handles complex business logic
- Provides more flexibility
- Supports advanced customization
- Gives better control over processes
- Enables external system integration

---

# Declarative vs Programmatic Development

| Declarative Development | Programmatic Development |
|---|---|
| Uses clicks and configuration | Uses coding |
| Easier for beginners | Requires programming knowledge |
| Faster for simple tasks | Better for complex tasks |
| Limited customization | Highly customizable |
| Uses Flows and Rules | Uses Apex and Triggers |

Both approaches are important in Salesforce projects.

---

# Basic Apex Syntax

Today I learned some basic Apex programming syntax.

---

## Simple Apex Program

```apex
public class HelloWorld {
    public static void displayMessage() {
        System.debug('Hello Salesforce');
    }
}
