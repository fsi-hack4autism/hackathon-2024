# 2024 Financial Services Autism Hackathon - Main Site

The main repository for the 2024 hackathon with all the information for the hackathon and pointers to all repositories. Hackathon informaton pertaining to 2024 specifically will remain in here. The individual repositories are made to span multiple years. This years hackathon will continue to focus on ensuring the growth for each use case. This means the repositories created this year will be use again in subsequent years provided these use cases are repeated again. We need to ensure these solutions will lead to real world outcomes.

## Mission Statement
Bring developers from the Financial Services industry together to demonstrate how innovative Microsoft technologies can transform autism services by tackling real world use cases provided by families and creating lasting open-source projects for the community.

![image](https://user-images.githubusercontent.com/4500512/212386856-50328c9e-3699-4aec-8c68-6d889e043c05.png)

## Dates and Location
The date of the event is April 3rd and 4th. The event will be hybrid. The in-person venue will be in NYC at the Microsoft Garage (300 Lafayette St) during World Autism Awareness Month (April).

## Use cases

### Use case 1: Therapy session co-pilot
#### Objective: Assist the RBT and BCBA during a session with the child
An RBT (Registered Behavioral Technician) implements a session designed by the BCBA and looks to acomplish the goals and targets set by the BCBA. Usually, they carry an IPAD or an IoT device to capture their observations. But this has two challenges - it splits the focus of the RBT between focusing on the child and capturing the observations; and it is a very one-dimnesional approach to capture the observations. This use case attempts to solve these challenges by providing  multi-sensory approach to data capture.
#### Scenario
The session will comprise of:
* Multi-modal data capture
  * A smartphone app used by RBT - similar to what some RBTs have today
  * Video camera to record the session - this will focus on capturing facial expressions, body language, fluency of tasks, etc.
  * Microphone - this will focus on capturing voice, tone, etc. to determine emotions
* Real-time identification of pre-designed triggers
  * This module will specifically look for pre-designed triggers - emotional (frustration, accomplishment, etc.), or physical (completion of task, eye contact, etc.)
  * The objective is to track progress along specific markers
* Post-session summarization
  * Summarize and generate notes - free form based on observations across all modes
  * Summarize progress on specific markers
#### Code repository
https://github.com/fsi-hack4autism/therapy-session-copilot
#### Stakeholders
* RBT, BCBA, parent, child
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Rishi Bhatnagar|Use Case Lead|Morgan Stanley|
||Subject Matter Expert|RBT/BCBA|
|Rob Reese|Tech Lead|Microsoft|
||Tech Lead|Accenture|
##### Ideas
[Project Florence -Vision Studio for Video/Image Analysis](https://portal.vision.cognitive.azure.com/gallery/featured)
#### Time to Market: 12-18 months

### Use case 2: Program development design co-pilot
#### Objective: Assist the BCBA design a program specifically tailored for each child
A BCBA (Board Certified Behavior Analyst) designs a program specifically for each child based on individualized treatment plan. It will center around the activitie the child enjoys and responds to. The objective is to have specific tasks for the child to complete with a certain level of fluency. This needs to take into account previous assessments, observations, and progress markers. 
#### Scenario
* The co-pilot will be able to ingest past program summaries in multi-modal form - videos, notes (digitized and undigitized), voide recordings, etc
* Based on these, the co-pilot will place the child in a cohort of other children with similar assessments and markers
* Based on past successes of children in the cohort, the co-pilot will suggest a recalibrated treatment and markers (if needed) to the BCBA
* It can generate a progress summary at any given point of time
#### Code Repository
https://github.com/fsi-hack4autism/program-development-copilot
#### Stakeholders
* RBT, BCBA, parent, child
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Rishi Bhatnagar|Use Case Lead|Morgan Stanley|
||Subject Matter Expert|BCBA|
| Devanshi Thacker |Tech Lead|Microsoft|
||Tech Lead|Accenture|
#### Time to Market: 12-18 months

### Use case 3: Patient on-boarding co-pilot
#### Objective: Help BCBA onboard a new patient quickly
Typically, a BCBA gets limited amount of time to onboard a new patient and this can be a very cumbersome task. It includes several types of information to intake:
* Patient demographics, medical history, past services, etc.
* Historical evaluations, IEPs, etc.
* Insurance, funding, billing information, etc.
* Previous and current treatments and their outcomes, progress reports, etc.
* Consent forms, contracts, letter of engagement, etc.
#### Scenario
* The co-pilot will be able to ingest historical documents
* It will allow parents, BCBAs, and RBTs to actively collaborate across sessions - such as allowing parents to provide inputs of progress outside of sessions
* It will allow tracking documents and provide a platform for storing consents, authorizations, etc.
* It can generate a summarization of the new patient for the BCBA to review
#### Code Repository
https://github.com/fsi-hack4autism/patient-onboarding-copilot
#### Stakeholders
* BCBA, parent, child
#### Leadership team
| Name | Role | Company |
|------|------|---------|
| Rishi Bhatnagar |Use Case Lead|EY|
|Leo Junquera|Subject Matter Expert|Parent|
| Alexis Joseph |Tech Lead|Microsoft|
||Tech Lead|Accenture|
#### Time to Market: 12-18 months

### Use case 4: Friendly neighborhood Mobile Networking App
#### Objective: Connect parents of children with ASD with helpful resources in the community - other parents, BCBAs, organizations, etc.
When parents move into a new neighborhood, they are not sure what local resources are available to help them or their child. They don't know which RBT, BCBA, or ABA therapist will be best suited for their child. Often times, parents don't even know what questions to ask or what benefits are available to them. This app attempts to start solving the problem.
#### Scenario
This mobile app will help connect parents and patients with other helpful members of the community - other parents, BCBAs, organizations, etc. It will work in three main phases
* Intake
  * Allow patients and parents to fill in their and thier child's profile
  * Offer a helpful "onbording survey" that will gather basic information about their child
* Discover
  * Use ChatGPT to allow parents and patients ask open ended questions and have a conversation
  * Prompt the right next actions for the parents 
  * Provide helpful information from credible sources
* Connect
  * Connect them with other parents in same situation
  * Connect them with credible resources and organizations that offer help in the specific area they are looking for
#### Code Repository
https://github.com/fsi-hack4autism/friendly-neighborhood
#### Stakeholders
* RBT, BCBA, parent, child, non-profit organization
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Dhruv Bhatnagar|Use Case Lead|Student|
|Crystal|Subject Matter Expert||
|Mike Richter|Tech Lead|Microsoft|
||Tech Lead|Accenture|
#### Time to Market: 12-18 months

### Theme 2: Ideas that are leverage innovative and exploratory technology and have a longer time to market

### Use case 5: Job skill training using Augmented Reality
#### Objective: Teach basic job skills to people with autism using Augmented Reality
This use case will focus on the use of Augmented Reality for teaching job skills to people with Autism, particularly those aging out of the supports provided in the school environment. Unemployment for those with Autism is significant and the supports in the work environment are limited. The use case will use Unity engine to build Augmented Reality solutions that can be used on platforms like HoloLens to help with basic job skills by presenting visual cues on how to complete task such as stocking shelves or preparing food. 
Additonally, the use case will make use of Gen AI, to manage, evaluate, and provide feedback to the student on how well the skill is being performed. It can also be used to generated the slight variants and increasingly complex scenarios to practice and introduce gamification.
This will also address the issue of scaability - moving away from 1:1 support to a 1:N as an a student becomes an adult.
#### Scenario
The skills th application will focus on can include one or more of the following:
* **Stacking shelves in a store** – e.g., making sure all the labels are facing outwards, etc.
* **Setting up a table in a restaurant** – making sure all the cutlery is there an arranged properly
* **Setting up a catering tray** – e.g., making sure all items are placed properly
#### Code repository
https://github.com/fsi-hack4autism/augmented-reality-skills-training
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Barry Cordie |Use Case Lead||
||Subject Matter Expert|BCBA|
| |Tech Lead|Microsoft|
||Tech Lead|Accenture|

### Use Case 6: Metaverse using Virtual Reality
#### Objective: Practice handling a variety of social situations through gamification
The world is filled with challenging social situations.  People facing new situations often struggle to find appropriate responses.  For those on the autism spectrum, this is exacerbated by difficulty reading standard social cues.  Having a safe and controlled environment to practice responding to common social situations, personality types, and social cues would allow users to face new situations with confidence.  Since creating such an environment would be difficult to scale, this app applies virtual reality to provide a unique social practice environment in an application.  Furthermore, since those with autism are often drawn to repetition, the app utilizes generative AI to ensure adequate variety across sessions.  Generative AI will also be used to evaluate the user’s performance.
#### Scenario
This virtual reality app will present users with a variety of interactive stories that include common social situations and personality types.  Users progress through the story by meeting a variety of characters with the goal of successfully completing the story.  Each story consists of the following components:
* **Story board** – Configuration of the story space and VR coordinates.  This section is designed in conjunction with VR designers.
* **Characters** – Configuration of the main characters and their general personality types.  The personality types are fed as prompts to generative AI to script the characters’ initial comments and subsequent responses to the user.
* **Scoring** – Analysis of the user’s handling of the situation is performed by feeding the entire conversation to generative AI for analysis of the user’s reactions.  Advancement in the game is based on the score.
#### Code repository
https://github.com/fsi-hack4autism/Metaverse-Social-Practice
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Stephen Goldbaum|Use Case Lead|Morgan Stanley|
||Subject Matter Expert|BCBA|
| Caroline Matthews |Tech Lead|Microsoft|
||Tech Lead|Accenture|


## Planning Team Roles
We often get asked "how can I participate" and have therefore outlined a list of roles and their responsiblities.

### Training Lead:
Curate resources and organize sessions in order to equip participants with the knowledge needed to prepare for the hackathon.
- Build technical training guide with learning geared towards each use case
- Put together contextual training guide focused on autism -  current state, challenges, and gaps
- Organize and distribute training schedule, including “ask me anything” and technical/contextual skilling sessions


### Use Case Manager:
Serve as the administrator of a use case. Ensure that both the tech leads and participants have what they need before and during the hackathon. 
- Support planning efforts and help in aligning 2-3 tech leads to use case
- Organize prep sessions leading up to the hackathon and ensure participants are connected with tech leads
- Oversee activity and logistics during the two-day hackathon
- Work with Tech Lead to capture summary/results


### Use Case Tech Lead:
Serve as technical point of contact for a use case, reviewing output from previous years and helping to unblock technical barriers against use case objectives. 
- Provide recommendations and help to finalize use case 
- Lead prep sessions for participants and be available for technical questions
- Manage sponsored subscriptions and set up for participants
- Lead and guide team(s) during the two-day hackathon
- Work with Use Case Lead to capture summary/results


### Marketing Lead:
Organize marketing material for the Hackathon and generate interest internally and externally. 
- Build a folder of references including: 
  - Word and PowerPoint branded templates
  - Brochure to be distributed to interested external organizations
  - One-pager highlighting the event


### Manager of Operations:
Ensure that everything is running smoothly across technical planning details of the Hackathon. 
- Partner with individuals building registration platform to oversee and manage registration, maintaining organized list
- Point of contact to navigate any external access issues
- Create Team that includes organize training content, use case details, and channels and assist with adding/managing members
- Responsible for day-of operations, overseeing schedule and making sure everyone knows where they are supposed to be


### Customer Engagement Lead:
Serve as the point person for a given customer organization, ensuring they have what they need to prepare their developers for the hackathon. 
- Identify customer “champion” lead who will be your primary liaison for the hackathon
- Work with Marketing Lead and Training Leads to get content and resources to share with your customer
- Keep your customer informed on a regular basis on registration timelines, training sessions, and other event logistics
