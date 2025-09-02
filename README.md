# CS-REPOSITORY-
Martinez, Eizel Faye C & Romero, Samantha B.

Project Proposal

Project Title

FamiLynk: Keeping Families in sync

Problem Statement

Many Filipino households struggle to manage daily tasks, schedules, and responsibilities. This often results in missed bill payments, forgotten chores, wasted food, and disorganized routines. With family members juggling school, work, and personal activities, it becomes difficult to maintain coordination and accountability. There is a need for a centralized, user-friendly tool that can help families stay organized, connected, and efficient.

Project Objectives

The project aims to:

1. Provide a shared calendar to help families coordinate schedules and complete at least 80% of tasks on time.


2. Reduce wasted food and missed maintenance by at least 80% through pantry tracking, expiration monitoring, and repair reminders.

3. Create a single platform that combines features of existing apps while tailoring them to the needs of Filipino families.



Planned Features

Shared Family Calendar – synchronize events, deadlines, and appointments.

Synced Grocery List – real-time updating for collaborative shopping.

Bill Tracker with Reminders – avoid missed or late payments.

Pet Care Scheduling – reminders for feeding, grooming, and veterinary care.

Pantry Tracking & Expiration Monitoring – prevent food waste.

Chore & Repair Reminders – assign and track household responsibilities.


Planned Inputs and Outputs

Inputs:

User logins and family member profiles.

Calendar entries (events, tasks, deadlines).

Grocery list items, pantry stock, and expiration dates.

Bill information (due dates, amounts, categories).

Outputs:

Notifications and reminders (bills, chores, tasks, expiration alerts).

Organized calendar with completed/unfinished task reports.

Summaries of household activities and responsibilities.



Logic Plan

The system flow will follow this sequence:

1. User Login → Select Family Group


2. Input Data (events, chores, bills, groceries, etc.)


3. System Processes inputs → syncs across family devices.


4. System Generates Outputs (reminders, recipe suggestions, task updates).


5. Users Receive Notifications/Updates → complete tasks → progress tracked.



PSEUDOCODE 
START

DISPLAY "Welcome to FamiLynk"
USER logs in or creates account

IF login successful THEN
    LOAD family group data
ELSE
    PROMPT user to register or retry login
END IF

LOOP
    DISPLAY Main Menu:
        1. Manage Calendar
        2. Manage Grocery List
        3. Track Bills
        4. Pantry & Expiration
        5. Chores & Repairs
        6. Pet Care
        7. Exit

    GET user choice

    CASE user choice OF
        1: 
            INPUT event/task details
            SAVE to shared calendar
            SEND notification to family members
        2: 
            INPUT grocery item
            UPDATE synced grocery list
            DISPLAY updated list
        3:
            INPUT bill details (due date, amount)
            SAVE to bill tracker
            SET reminder notification
        4: 
            INPUT pantry item + expiration date
            STORE data
            IF item nearing expiration THEN
                NOTIFY user
            END IF
        5:
            INPUT chore or repair task
            ASSIGN to family member
            SET reminder notification
        6:
            INPUT pet care schedule
            SET reminders (feeding, grooming, vet visits)
        
        7:
            DISPLAY "Thank you for using FamiLynk"
            EXIT program
    END CASE
END LOOP

END