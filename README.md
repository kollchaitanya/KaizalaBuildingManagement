# Kaizala Building Management
## Prerequisite to start this solution
- Two mobile numbers (1 as admin, 1 as resident).
- Create an account https://manage.kaiza.la/, Ensure that the kaizala pro is enabled.
- Activate the https://flows.microsoft.com with same login.
- Take one office 365 user license.
Request to activate the kaizala pro to customize the solutions, an organization account is created. 

Developing a building management solution using Kaizala platform.
- Demos https://kaizalademo.office.com/
- Kaizala Pro: https://docs.microsoft.com/en-us/office365/kaizala/enable-disable-kaizala
- Groups: https://docs.microsoft.com/en-us/office365/kaizala/groups
- Public Groups: https://docs.microsoft.com/en-us/office365/kaizala/public-groups

There are four persona
- Management 
- Security  
- Residents 
- Association members 
## Groups to be created
Login in to the web application and create below groups and add different persona members
- Operations 
    - Create group
    - Add management & association members
    - Deactivate all default actions
    ![restrict actions](Media/RestrictActions.jpg)
    Click on Admin, Member checkbox and click on "Save".
- Security
    - Create group
    - Add security members
- BMS 
    - Create group
    - Add management members
- Residents
    - Create a Public Groups
    - Add all the members as subscribers

## Management team responsibilities
- House keeping    
    Responsible to ensure that building premises is clean.
- Technical team   
    Different variety of technical issues needs to be handled by this team eg: Electrical, Plumbing, Carpenter, Water Treatment Plant, Sewage Treatment Plant.

Q1) How to ensure that every equipment is working?
A1) it is possible by checking it every day, but this needs to be recorded digitally so that the association team can verify through reports. So the solution is creating the Daily / Monthly / Quarterly check lists. 

- Daily checklists
  - LT panel
  - Transformer
  - Diesel generator
  - Lifts
  - Water treatment plant 
  - Sewage treatment verification
- Monthly check lists
  - Fire extinguisher
  - CCTV Cameras
 - Quarterly check lists
  - Gym equipments
  - Swimming pool water pumps

Q2) How to create a custom checklist?

A2) [Custom Checklist](CustomChecklist.md)

