What triggers this workflow to run? (Look at the on: section)
on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

What are the four main steps this workflow performs? (List each step name)
# Step 1: Get the code from the repository

# Step 2: Validate HTML files
 
# Step 3: Check for broken links
    
# Step 4: Upload the built site for deployment

What does the "Checkout code" step do and why is it necessary?
It gets the code from the repository and is needed to process any later steps

What is the purpose of the environment configuration?
to separate external settings from core source code so that software applications can run securely, flexibly, and reliably across different stages

How does this automated deployment improve reliability compared to manual deployment?
 It improves reliability by replacing human errors with standardized, repeatable scripts

What would happen if you pushed code to a different branch (not main)?
code goes live only on that specific branch and Automated tests may trigger