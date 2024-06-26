### Team Name:

21479 Group 3

### Team Members:

Harrison Goldstein: https://github.com/harrisongold1210 <br>
Fiza Bhayani: https://github.com/fizab2329 <br>
Ethan Denbrok: https://github.com/EvanDebruyne <br>
Luke Lambert: https://github.com/lhl88422 <br>
Raul Fernandez: https://github.com/rjf02

### Problem Description:
As consultants hired by the tennis club, our task is to develop a comprehensive database that efficiently manages various aspects of club operations and member engagement. This database will serve as a centralized platform for storing and organizing member information, preferences, feedback, and participation in club activities. It will include modules for event planning, scheduling coaching sessions, managing league activities, and tracking facility upkeep. Additionally, the database will integrate features for inventory management of equipment essential for games and training sessions. It will also facilitate the creation of a vibrant community environment by enabling the scheduling and promotion of league games, tournaments, and other social events. Moreover, the database will support talent development initiatives by allowing the tracking of member progress, skill levels, and participation in customized coaching sessions conducted by qualified instructors. Our goal is to create a user-friendly and efficient database solution that empowers the tennis club to better serve its members and enhance their overall experience within the club community.

### Data Model: 

<img width="623" alt="Screenshot 2024-04-04 at 3 23 29 PM" src="https://github.com/lhl88422/lhl88422/assets/150093821/80387ee1-d93d-4166-a051-ae22b07556c9">

### Explanation of data model:
This data model encapsulates a robust system designed to efficiently manage operations within a tennis club, encompassing various facets ranging from member administration to court reservations, event coordination, payments, feedback collection, coaching, and league management.

Fundamentally, the model captures comprehensive member profiles, including personal particulars, membership status, and their engagement within the club such as court reservations, event participation, payments, and feedback. This enables personalized interactions and streamlined monitoring of member activities, ensuring a tailored experience for each individual within the tennis club community.

Moreover, the model accommodates staff roles pivotal in court management, event organization, coaching sessions, and overall club oversight. Staff members are allocated specific responsibilities, facilitating tasks like court maintenance, event planning, and scheduling coaching sessions, thereby ensuring the smooth functioning of day-to-day operations.

Furthermore, the model facilitates the management of tennis courts, equipment, and leagues within the club. Members can easily reserve courts for practice or matches, with coaching sessions led by certified instructors. Leagues are structured with teams formed by club members, fostering a spirit of competition and community. Additionally, events hosted by the club can be seamlessly integrated with tournaments through a one-to-one recursive relationship, enhancing the club's versatility and providing opportunities for competitive play within the tennis community.

### Data Dictionary: 
<img width="671" alt="table 1" src="https://github.com/lhl88422/lhl88422/assets/150093821/ea3f2185-2052-43c0-a9f5-aab180d04070">

<img width="685" alt="table 2" src="https://github.com/lhl88422/lhl88422/assets/150093821/9677a1d3-7622-418d-9c98-d761b87b4a62">

<img width="710" alt="table 3" src="https://github.com/lhl88422/lhl88422/assets/150093821/a4cccf5c-6643-4a37-888f-3d6f174051f7">

<img width="689" alt="table 4" src="https://github.com/lhl88422/lhl88422/assets/150093821/344d9da2-71bc-4bf5-a924-e3190eafae0e">

<img width="502" alt="table 5" src="https://github.com/lhl88422/lhl88422/assets/150093821/16eab923-2425-4434-bd69-328dc94397b7"> <br>

<img width="498" alt="table 6" src="https://github.com/lhl88422/lhl88422/assets/150093821/25d3584d-44e5-48f6-9e77-f5b94bf8ee38">

<img width="527" alt="table 7" src="https://github.com/lhl88422/lhl88422/assets/150093821/49f42553-5dd4-425d-8639-3479f7fcc8ea">

<img width="518" alt="table 8" src="https://github.com/lhl88422/lhl88422/assets/150093821/d4ed4110-f70d-43d7-bd79-79bde31ef62c">

<img width="512" alt="table 9" src="https://github.com/lhl88422/lhl88422/assets/150093821/9ccc3bde-3168-469d-bca9-c21c062b301b">

<img width="533" alt="table 10" src="https://github.com/lhl88422/lhl88422/assets/150093821/655f0f33-ae43-49f1-97de-30ad323b4a41">

<img width="515" alt="table 11" src="https://github.com/lhl88422/lhl88422/assets/150093821/481f808d-78f0-4d45-ab7d-34825108d967">

<img width="528" alt="table 12" src="https://github.com/lhl88422/lhl88422/assets/150093821/75edfb47-bb8c-46f2-a0fe-c80ad9c2dab2">



### Queries: 
Query 1:<br>
Find the number of staff members at each individual facility.<br>
<img width="680" alt="1" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/c1788473-73ff-4904-bae4-f9ffb8835c18"> <br>

Justification: This is helpful information for the facilities to have for resource allocation and to ensure that they are appropriately have enough employees at each facility. <br>


Query 2:<br>
Find the average rating for all feedback provided <br>
<img width="617" alt="2" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/9028add2-a088-4937-a9e4-b7c66c083517"> <br>

Justification: This information is helpful as it can be used for quality assessments for every facility and can be helpful when conducting performance evaluations in order to ensure customer satisfaction. <br>

Query 3:<br>
Find the sum of the payment amount submitted by each member <br>
<img width="559" alt="3" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/e1ea12c6-e989-48d9-b6a7-4c7c3110c98b"> <br>

Justification: This is useful information that can be used for financial tracking as well potential reward/recognition of committed members to the facilities. <br>


Query 4:<br>
List the quantity and the name of all the equipment needed in each training session <br>
<img width="899" alt="4" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/573424ad-619b-489f-9c8a-8bc3d26c742a"> <br>

Justification: This can be useful information for session planning on the coach/staff members end as well as resource allocation within their own facility as well as across all facilities. This information is also useful in equipment management and ensuring all of the equipment purchased is accounted for. <br>

Query 5:<br>
Retrieve the team name, member ID, first name, and last name for all team members belonging to teams with names starting with 'S', while also including members whose first or last name contains the letter 's'. <br>
<img width="1009" alt="5" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/eede0b02-fabc-47d5-83f5-1437c561be9d"> <br>

Justification: This query exclusively retrieves team names containing the letter 'S'. By focusing solely on team names, it offers a broader scope of data retrieval, potentially enabling analyses or actions targeting teams with specific naming characteristics.<br>

Query 6:<br>
Retrieve all members who have not made any reservation <br>
<img width="744" alt="6" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/96cbe6eb-59e0-4a60-847e-c9842a7668f6"> <br>

Justification: This information allows the facilities to send targeted communication strategies to ensure all members have access/ability to create a reservation to ease their time at our facilities. <br>

Query 7:<br>
Calculate the total number of training sessions led by each coach <br>
<img width="991" alt="7" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/40cd9f04-a8ff-42fa-b3a4-c4b0284449e1"> <br>

Justification: This query is useful for assessing the workload and effectiveness of individual coaches by determining the total number of training sessions they have led and their average session duration.  <br>

Query 8:<br>
List the name of the member who made a reservation, where the reservation is, and start and end time of the reservation <br>
<img width="1092" alt="8" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/4d210cf0-41ee-4f59-bc05-55ccb31faebc"> <br>

Justification: This information is useful in order for scheduling purposes of staff and coaches as well as resource management. This information is also useful to track member engagement. <br>

Query 9:<br>
List the members who have made reservations for facilities, including their first and last names, along with the facility name, start time, and end time of their reservations, but only for those members who have made payments exceeding $10. <br>
<img width="982" alt="9" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/1f582582-e26a-43fe-b6c4-8a021ffb5c5b"> <br>

Justification: This information can be used for revenue maximization, resource allocation, customer retention and optimizing the company's competitive advantage and assessing it’s operational efficiency. <br>

Query 10:<br>
Find the tournaments where the average salary of staff members working in that tournament is more than $10,000 <br>
<img width="887" alt="10" src="https://github.com/lhl88422/MIST4610-Project-1/assets/150093821/96b2cf5e-499c-44b8-a9c2-6f219a39da9c"> <br>

Justification: This information allows us to understand which tournaments have a more rigorous work schedule as staff salary is based on work completion.<br>

### Query Matrix:
<img width="459" alt="Screenshot 2024-04-04 at 5 33 06 PM" src="https://github.com/lhl88422/lhl88422/assets/150093821/cf9d2aa9-312d-4848-9e5d-008fc77f6887">

### Database Information:
Name of the database: al_Group_21479_G3 <br>
