# PROG101_Assignment1_Imran_Sahr_Lebbie_905006512
This is assignment 1 for Progamming Logic and Design about a Waste Management System in S/L
Project: Waste Management 
Student: Imran Sahr Lebbie 
Student ID: 905006512
Course: PROG101 — Principles of Programming Logic and Design
Institution: Limkokwing University of Creative Technology, Sierra Leone
Examiner: Amadu Kamara

## Problem Description

Waste management is an important environmental and public health concern in Sierra Leone. In some communities, the collection and disposal of household waste can be inconsistent, resulting in waste accumulating along roadsides, in open spaces, and around residential areas. Poor waste management can contribute to environmental pollution, unpleasant surroundings, blocked drainage systems, and increased health risks.
One challenge is the difficulty residents may experience when reporting uncollected waste and obtaining information about collection requests. Without an organized reporting and tracking process, waste collection officers may struggle to prioritize requests, monitor outstanding complaints, and keep residents informed.
The proposed Waste Collection Management System aims to address this problem by providing a simple, structured way to register waste collection requests, record relevant information, monitor request statuses, and support the organization of waste collection activities.

## Community Impact

The proposed system could provide several benefits to residents and waste collection officers.
First, it would give residents a structured method of submitting waste collection requests. Each request could contain details such as the resident's name, location, type of waste, and date of submission.
Second, the system would help collection officers organize and monitor reported requests. By maintaining request records and updating their statuses, officers could identify requests that are pending, in progress, or completed.
Third, an organized record of requests could support better planning and help officers identify locations where waste collection services are frequently needed. Improved coordination could contribute to cleaner surroundings and greater community awareness of proper waste management.
However, the system would not automatically remove waste or guarantee that every request would be addressed immediately. Its effectiveness would depend on the availability of collection workers, transport, equipment, and appropriate waste disposal facilities.

## Sustainable Development Goal (SDG) Alignment

The proposed Waste Collection Management System supports Sustainable Development Goal 11 (SDG 11): Sustainable Cities and Communities. This goal includes making human settlements more inclusive, safe, resilient, and sustainable. Organizing waste collection requests can contribute to cleaner communities and better coordination of local waste management activities.
The project is also relevant to SDG 12: Responsible Consumption and Production, particularly the broader objective of improving waste management and reducing environmental impacts. By making collection requests easier to record and monitor, the proposed system could support more responsible waste handling.
The system would contribute to these goals indirectly. Its actual impact would depend on whether the information recorded leads to effective waste collection, appropriate disposal, and sustained participation by residents and responsible authorities.

## Pseudocode Of The Waste Management System

Pseudocode is a simple way of explaining the steps a system follows to solve a problem. It uses plain English and basic programming instructions without following the rules of a specific programming language.
In this project, pseudocode explains how the Waste Collection Management System registers waste collection requests, checks request status, and updates collection information.

Main Program

BEGIN
    DISPLAY "WASTE COLLECTION MANAGEMENT SYSTEM"

     DECLARE wasteType : STRING
     DECLARE wasteWeight : REAL
     DECLARE  wasteCategory : STRING
     DECLARE recyclable : BOOLEAN 

    DISPLAY "1. Register Waste Request"
    DISPLAY "2. Check Request Status"
    DISPLAY "3. Exit"
    INPUT Choice
    IF Choice = 1 THEN
        CALL Register Request
    ELSE IF Choice = 2 THEN
        CALL Check Request Status

    ELSE IF Choice = 3 THEN
        DISPLAY "Thank you for using the system"
    ELSE
        DISPLAY "Invalid choice"

    END IF
END

BEGIN
"Register Waste Request"
   
    INPUT Resident Name
    INPUT Contact Number
    INPUT Waste Location
    INPUT Waste Description
    IF any information is missing THEN
        DISPLAY "Please enter all required information"
    ELSE
        SAVE the request
        ASSIGN a Request ID
        SET Status = "Pending"
        DISPLAY "Request registered successfully"
        DISPLAY Request ID
        DISPLAY "Status: Pending"
    END IF
END

BEGIN
"Check Request Status"

    INPUT Request ID
    SEARCH for the Request ID
    IF Request ID is found THEN
        DISPLAY Request Details
        DISPLAY Request Status
    ELSE
        DISPLAY "Request not found"
    END IF
END

BEGIN
"Update Request Status"
   
    INPUT Request ID
    SEARCH for the Request ID
    IF Request ID is found THEN
        DISPLAY "1. In Progress"
        DISPLAY "2. Completed"
        INPUT New Status
        IF New Status = 1 THEN
            SET Status = "In Progress"
        ELSE IF New Status = 2 THEN
            SET Status = "Completed"
        ELSE
            DISPLAY "Invalid status choice"
        END IF

    ELSE
        DISPLAY "Request not found"
    END IF
END

## Structure of the Flowchart

<img width="827" height="1169" alt="Flowchart 1 Main_Program" src="https://github.com/user-attachments/assets/ca822633-540c-4738-8b34-05735349e482" />
<img width="827" height="1169" alt="Flowchart 2 Register_Waste_Request" src="https://github.com/user-attachments/assets/acf30bd9-3b32-49f9-8fee-0f5b199ba6bf" />
