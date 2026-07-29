# Yatra Automation Solution

A Selenium-based Java automation script that interacts with Yatra's flight booking calendar to select months, extract prices, and compare fares to find the cheaper travel date.

## What It Does

- Selects a target month in the calendar widget
- Reads the price shown for a given date
- Compares prices between two months and prints the cheaper one

## Tech Stack

- Java
- Selenium WebDriver
- Maven

## Project Structure

```
YatraCalendarAutomation/
├── src/
│   ├── main/java/com/yatra/automation/
│   │   └── YatraAutomationScript.java
│   ├── main/resources/
│   └── test/
├── pom.xml
└── README.md
```

## Setup

```bash
git clone https://github.com/pavithrashankar22/Yatra_Automation_Solution.git
cd Yatra_Automation_Solution
mvn clean install
```

## Run

```bash
mvn test
```
