# Smart India Hackathon Workshop
# Date:
## Register Number:
## Name:
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea
Hybrid Navigation Engine Using  GPS and routing API
Platform Phase: Switches to an indoor positioning system (IPS) using a combination of Wi-Fi and Sensor Fusion (Pedestrian Dead Reckoning - PDR).
## Proposed Solution / Architecture Diagram
**1**  Outdoor Phase: Uses traditional GPS and standard routing APIs to guide the user from their current location to the correct railway station entrance.

**2**  Platform Phase: Switches to an indoor positioning system (IPS) using a combination of Wi-Fi and Sensor Fusion (Pedestrian Dead Reckoning - PDR).

**3**  Dynamic Guidance Engine: Maps out the exact multi-floor path (e.g., ground floor ticket counter $\rightarrow$ escalator $\rightarrow$ foot overbridge $\rightarrow$ Platform 3) paired with real-time voice guidance synchronized with live Indian Railways train arrival/delay data.


## Use Cases

**1**   **Inter-Modal Navigation to Exact Platforms:**

The app calculates the route, factoring in current security queue wait times, directs them through the nearest gate, up the elevator to the correct Foot Overbridge (FOB), and guides them straight to Platform

**2**   **Real-time Platform Change Alerts:**

The app receives live feed updates via NTES (National Train Enquiry System) or station display scraping, instantly alters the indoor route mid-journey, and updates the voice prompt

## Technology Stack

he app receives live feed updates via NTES (National Train Enquiry System) or station display scraping, instantly alters the indoor route mid-journey, and updates the voice prompt

## Dependencies
