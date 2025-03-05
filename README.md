# Systems Documentation Repository

This repository contains documentation for all systems used within our organization.

## Purpose

This is a central location for storing and maintaining documentation for all our internal systems. Each system has its own dedicated folder containing documentation.

## How to Use

1. Clone this repository:
   ```
   git clone https://github.com/icpac-igad/Systems_documentation.git
   ```

2. Navigate to the system you're interested in:
   ```
   cd Systems_documentation/system-name
   ```

3. View the documentation

## How to Contribute

1. Clone the repository:
   ```
   git clone https://github.com/icpac-igad/Systems_documentation.git
   ```

2. Check if a folder for your system already exists. If not, create one:
   ```
   cd Systems_documentation
   
   # Check if folder exists
   ls
   
   # Create folder if it doesn't exist
   mkdir system-name
   ```

3. Add your markdown documentation files inside that folder:
   ```
   cd system-name
   create or upload documentation for your system (.docx,.pdf,.md)
   ```

4. Commit and push your changes:
   ```
   git add .
   git commit -m "Add documentation for system-name"
   git push origin main
   ```

5. Create a pull request for review.

## Adding Documentation for an Existing System

If you need to add documentation for a system that already has a folder:

1. Navigate to the system folder:
   ```
   cd Systems_documentation/existing-system-name
   ```


## Repository Structure

```
Systems_documentation/
├── system-a/
│   ├── documentation.md
├── system-b/
│   └── documentation.md
└── README.md (this file)
```

Each system folder should contain a file (.docx,.pdf,.md) files with appropriate documentation.