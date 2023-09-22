---
title: "WeShare: A carpooling mobile application (StartUp)"
colab: "StartUp"
description: "WeShare is a unique carpooling start up that Provides sustainable and convinient daily commute transportation for a marginal fee. Key features include pre-scheduled rides, Pre-defined stops locations, and in-app communication."
pubDate: "Sep 12 2022"
heroImage: "/WeShare.svg"
badge: "Demo badge"
tags: ["Product Design", "Usability Research", "Flutter", "Software Engineering"]
---

## Problem Statement

Global warming has become a critical issue in today's world, with the accumulation of CO2 and air pollutants in the atmosphere being a significant contributor. Traditional commuting methods involving individual car usage contribute to high CO2 emissions. WeShare aims to address this issue by promoting carpooling, reducing the number of cars on the road, and thus lowering carbon emissions.

## Solution

WeShare is a carpooling mobile application designed to facilitate easy ride-sharing among users in Malaysia, primarily targeting university students and working professionals. By connecting riders and drivers, WeShare aims to create a more sustainable and eco-friendly transportation ecosystem while promoting community bonding.

## Environmental Impact

WeShare's mission aligns with the United Nations Sustainable Development Goals (SDGs) of "sustainable cities and communities" (Goal 11) and "climate action" (Goal 13). Through efficient carpooling, WeShare contributes to a better and more sustainable future by reducing individual carbon footprints, promoting green transportation, and decreasing traffic congestion in urban areas.

## Economic Sustainability

In addition to its environmental goals, WeShare also focuses on economic sustainability. Rides are provided for a marginal fee, which will be split between the company and the drivers. This fee serves a dual purpose:

- Driver Expense Coverage: It helps subsidize or even cover drivers' vehicle expenses, making carpooling an economically viable option for them.

- Platform Growth: A portion of the fee goes to the company, enabling further development and expansion of the WeShare platform, thus benefiting both drivers and riders. English languages.

### Keywords
Product Design, User Experience, Carpooling, Eco-friendly transportation, Community bonding, Ride-sharing, Pre-scheduled rides, In-app communication

### Current Status
The high-fidelity design phase is complete, and the website is actively being developed on Webflow. The website is currently in the beta testing phase, incorporating user feedback for further refinement.

### Design Tools

Figma (Design), Webflow (Development)

### Team and Collaborations

- Ahmed Kamal Eldin: Design, Business development, Product development (Front-end, Maps API)
- Abdelrahman Alobaidi: Technology, Product development (Back-end, Cloud, Data)
- Loai Alsharee: Marketing, Relations, Project management, Product development (Back-end, Front-end)

### Live Site

[edumize.com](http://edumize.com)


## Application Overview

WeShare is a unique carpooling start up that Provides sustainable and convinient daily commute transportation for a marginal fee. Key features include pre-scheduled rides, Pre-defined stops locations, and in-app communication. Here's how it works for both riders and drivers:

### For Riders

- *Pre-scheduled Rides*: Riders can choose from a list of pre-scheduled rides posted by drivers. This allows users to plan rides ahead of time, even days or weeks in advance.

- *Filtering Options*: Users can apply filters such as time, car size, and location to find the most suitable rides. There is also a special option for female riders who prefer riding with female drivers.

- *Pick-up and Drop-off Points*: Users can select from predetermined pick-up and drop-off points at hotspot locations, ensuring clarity and convenience.

- *In-App Group Chat*: After selecting a ride, riders are added to an in-app group chat that includes the driver and fellow riders. This feature promotes communication among ride members and helps build a sense of community.

- *Safety Sharing*: Riders can share ride details with friends and family for added safety.

- *Carbon Footprint Tracker*: WeShare includes a carbon footprint calculator in user profiles, allowing riders to track their carbon footprint reduction over time.


### For Drivers

- *Verified Drivers*: Drivers are verified before posting rides, ensuring the safety of all users.

- *Ride Posting*: Drivers can post rides with details such as time, date, locations, and available seats in their cars. They can plan multiple rides in advance, making it convenient for both drivers and riders.

- *Predetermined Locations*: To enhance user experience, only predetermined location points are available for drivers to select as pick-up and drop-off points.

- *In-App Group Chat*: When a rider joins a driver's ride, an in-app group chat is created for easy communication among all ride members.

- *Carbon Footprint Counter*: The application updates a driver's carbon footprint counter in their profile after each trip, allowing them to track their environmental impact.


## Software Requirements Specification

### Front-end Components

- *Camera*: Utilized for user profile photos and in-app chats.
- *Local Storage*: Implement caching and store chat data and media.
Back-end Components:

### API Services

- *Google Maps API*: Used for displaying pickup and drop-off locations and tracking ride locations in real-time.

- *Push Notifications*:
*Chats*: Notify users when they receive a message from their driver.
*Ride Status*: Send notifications regarding the driver's waiting status and ride completion.
Authentication:

- *Firebase Authentication*: To identify users, manage sessions, and handle the login page and user profiles, integrating seamlessly with other Firebase services.
Database:

- *Cloud Firestore*: Store user data and ride history, enabling efficient data management and retrieval.


### Process

#### a. Research and Conceptualization

Research on global warming and its impacts.
Study of sustainable development goals.
Identifying target user demographics.
Analyzing existing carpooling platforms.
Conceptualizing the WeShare application.

#### b. User Experience Design

Wireframing the user interface for riders and drivers.
Designing the user flow for ride selection and posting.
Creating mockups for the in-app chat feature.
Implementing safety sharing features.

#### c. Front-end and Back-end Development

Developing the front-end of the application using Flutter.
Integrating Google Maps API for location services.
Implementing Firebase Authentication for user management.
Designing and deploying the Cloud Firestore database.

#### d. Testing and Optimization

Conducting rigorous testing for usability and functionality.
Gathering user feedback for improvements.
Optimizing performance and security.

#### e. Launch and Marketing

Launching the WeShare app in the Malaysian market.
Marketing campaigns targeting university students and working professionals.
Building partnerships with universities and organizations.


### Feedback Incorporation

Insights from initial MVP users and Investors during business pitches were incorporated in the 

## Conclusion

WeShare was not just a carpooling app; it was a movement toward a more sustainable and connected future. By providing an eco-friendly and economically viable alternative to traditional commuting, WeShare aimed to significantly reduce carbon emissions while enhancing the daily commute experience for its users. With a robust design process, strong environmental focus, and economic sustainability, WeShare was poised to make a meaningful impact on both the environment and the lives of its users.


