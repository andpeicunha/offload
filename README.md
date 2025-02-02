# Offload Technical 

We're excited to have you here as you take on our technical challenge. Our goal is to create an experience that mirrors real-world scenarios, giving you a glimpse into the type of work we do every day.

Below, you'll find a detailed description of a customer request — similar to a ticket you might encounter on the job. Your task is to analyze the requirements, devise a solution, and deliver an outcome that meets the customer's needs.

Treat this as you would any real-world project: think critically, communicate clearly, and aim for a solution that's both functional and maintainable.

Good luck, and we look forward to seeing your unique approach to the challenge!

# Truck Status Challenge

Your task is to build a solution that determines the overall status of a project based on the status of its trucks.

### Project Overview

A project can consist of many trucks. Each truck is assigned one of the following statuses:

- Unscheduled
- Scheduled
- In-Transit
- Arrived-On-Time
- Delayed

The projects overall status is determined using the following logic:

### Overall Status Rules

1. Unplanned - All trucks are in the `Unscheduled` status.

2. In Process - At least one truck is `Scheduled` or `In-Transit` and none of the trucks have the `Delayed` status.

3. Completed On Time - All trucks have reached the `Arrived-On-Time` status.

4. DELAYED - If any of the trucks have the status `Delayed` the entire project is marked as `Delayed`. 

Your task is to build a solution that displays all the trucks and that allows the user to specifiy the status of each truck. Then in the space provided above the trucks determine the overall truck status. 

Use the trucks found in the `/src/data/trucks.ts` file to populate the trucks for this project page.

Bonus Points: Use css add a bit of styling to the project view.


# Get Up and Running

1. Fork this repository
2. Use npm install to install the dependencies
3. Run the application locally with `npm run dev`