## Product Overview

A system to assign tricycle(keke) to different places in the school environment.

## Problem Statement

The school is quite a large environment so getting from one place to another can take quite a lot of time and enery and because of this there are tricycles to help aid movement. The tricycles don't stay in one place and are always mostly on the move and this makes them difficult to come buy sometimes in the school environment. When tricycles are come across sometimes because you're the only one going to a particular side they want you to pay the full amount for all the seats before they agree to take you to your destination and sometimes they wont carry you because they are not going to that side of the school

## Proposed solution

There should be a system that makes the tricycles stay in strategic places to ease boarding them from one place to another on the campus to make the process of finding tricycles easier and less time consuming.

## Target Users

- The tricycle drivers
- Students
- Staffs
- The school tricycle management officials

## Stakeholders

- The tricycle drivers because the system will affect how they get passengers and how much they earn
- Students because they are the main ones that need the tricycles to move around the campus
- The school tricycle management officials because they will be the ones managing the system and the drivers
- The school management because they have to approve the system and the sides the school is divided into
- The school security because they need to know how the tricycles are moving around the school
- The student union because they speak for the students
- Parents because they also want to be sure that their children are moving around the school safely

## Goals

- The main goal is to make it easier and less time consuming for students to find a tricycle going to where they want to go.
- Another goal is to stop drivers from refusing to carry students or asking them to pay for all the seats.

## Success Metrics

- We will know the system is working if students wait for less time before getting a tricycle
- If there are not many cases of drivers refusing or asking for full amount again
- If most of the drivers are making use of the system
- If students say it is easier to get a tricycle than before.

## Scope

- Dividing the school into sides
- Drivers joining a line for the side they are going to
- Students seeing which sides have tricycles available
- Management officials managing the drivers and the sides.

## Functional Requirements

The system should be able to:

- Help the management officials divide the campus into zones or areas
- Help drivers check in and find their assigned zone for the day
- Allow driver pick the side of the school they are going and join the line for that side
- Arrange the tricycles in each side in the order they came so it is fair to every driver
- Show the fixed fare for each seat set by the management so a student is not forced to pay for all the seats
- The system should remove a driver from the line when he picks passengers or leaves the side
- Let students report a driver that refused to carry them or charged more than the fixed fare
- Show the management officials how busy each side is

## Non Functional Requirements

- **Easy to use:** a driver should be able to join without any stress
- **Fast:** any change in the line should show to everyone in a very short time window
- **Available:** it should work well during busy hours like break
- **Secure:** only drivers approved by the management can join a line and the personal details of drivers and students should be properly protected
- **Scablity:** it should be able to handle more tricycles, more students and more sides later
- **Fair:** a driver should not be able to cheat the line or jump ahead of others

## Acceptance Criteria

- **Joining a line:** given that a driver is logged in, when he picks a side, then he shows at the end of the line for that side and the line updates instantly.
- **Fair order:** if two drivers joined the line for the same side, then the one that joined first should alwayss show first.
- **Leaving the line:** given that a driver has picked passengers, then he is removed from the line and the number of tricycles available is reduced by one.
- **Reporting:** given that a student has reported a driver, then the management officials can see the report with the date and time.

## MVP

The MVP is the first small version of the system that solves the main problem without all the extra things. The main problem here is that students can not find tricycles going to where they want to go and drivers sometimes refuse them or ask them to pay for all the seats.

### What will be in the MVP:

- fixed sides of the school
- Drivers registering and joining the line for a side
- The line arranged in the order they came
- The fixed fare shown to students
- The management officials adding or removing drivers and sides

### What will not be in the MVP for now:

- Live tracking of tricycles on the campus map
- Ratings for drivers
- Requests for students requesting a tricycle to pick them up

### How we will test it:

- Try it on one or two sides of the school with a small number of drivers for about a week or two
- We check if students are waiting for less time
- If there are fewer refusals
- If the drivers like using it

## Future Improvements

- Addition of notifications for drivers and students,
- Students requesting for a tricycle
- Ratings for drivers and reports for the management officials
- Live tracking on the campus map

## Risks

- Drivers may not want to wait in one place because they think they will lose money. To reduce this we should involve the drivers early and show them that the line will bring them more passengers consistently.
- Drivers may try to cheat the line. To reduce this a person at the stop can confirm the order.
- The school management may not support the system. To reduce this we should involve them early.

## Assumptions

- We assume that drivers will agree to stay on one side if it helps them get passengers faster and earn more
- We assume that the school management will approve the sides and the fixed fare
- The project has limited time and money since it is a school project

## Open Questions

- Who will decide the fixed fare for each seat?
- How many sides will the school be divided into?
- Does the school already have a list of registered tricycle drivers?
- What when there are very few students?
