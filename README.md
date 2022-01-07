# Print Shop Manager

Customer and Project Management for Large Format Print Shops

## Tech Stack

- Server: Node, Express
- Database: GraphQL
- Front-end: React/Next, Bootstrap

## User Stories

- I need to create, edit, delete and track customer orders
- I need jobs to move between different workflow locations
- I need to collect large orders in Projects
- I want to see my workflow and order locations visualized
- I want to assign individual orders to other users
- I want to create my own workflow locations

## MVP

- User can CRUD customers
- User can CRUD jobs (individual items)
- User can CRUD projects (collections and jobs)
- Jobs and projects show in a workflow and can be moved freely
- Completed jobs can be archived 

## Project Stretch Goals

- User can CRUD medias and machines
- User can CRUD locations
- Job math
- Data tracking
- Deeper job details

### After Graduation Stretch

- Invoice tracking
- Cost Analysis

## ERD

Models: User, Customer, Project, Job

Users have many projects and jobs
Customers have many projects and jobs
Projects have one user, one customer, and many jobs
Jobs have one user, one customer, one project 

![ERD](https://i.imgur.com/JW37Ziz.png)

## Wireframes

![Landing](https://i.imgur.com/9jQZ5dV.png)
![Dashboard](https://i.imgur.com/Nj6AjgS.png)
![Workflow](https://i.imgur.com/s8kQduy.png)
