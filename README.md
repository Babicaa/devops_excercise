# VM Provisioning Interface

Build a web-based interface plus a Python REST API to create, edit, list and delete “provisioned” virtual machines. Spend no more than 3 h on the task.

## Requirements

- List, edit and delete existing virtual machines  
- Create new virtual machines  

## Virtual machine parameters

- Basic machine attributes (CPU, RAM, Disk etc.)  
- Network (office, machine, test)  
- Users (normal and sudoers from AD)  
- Installed packages (list of RPMs from repo)  

## Instructions

You are free to choose any Python web framework and any JavaScript framework or plain JS for the frontend. The backend should expose a REST API for all VM operations; all dependencies (datastore, virtualization layer, external services) must be mocked or stubbed—no real VMs need to be provisioned. Store data in memory or in simple files. The frontend must communicate with your API to display a list of VMs, and allow creating, editing and deleting entries via UI elements that include all VM parameters, with dynamic controls for adding/removing users and package entries. Package and structure the code however you prefer.

## Deliverables

- Git repo with runnable source code  
- README  
  - Install and run steps  
  - Design notes  

## Evaluation criteria

- REST-ful API design  
- Code structure and organization  
- UI functionality and usability  
- Mocked interfaces  
- Ease of setup and use  

The goal is to have a demonstration of design and coding decisions on a small, self-contained problem and a concrete codebase to discuss in the next interview stage. The exact libraries and solutions you choose do not directly matter, but we will explore the reasoning behind your decisions.
