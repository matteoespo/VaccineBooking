# Vaccine Booking
Software Engineering Project 2020/2021

## Project assignment

The goal is to design an information system to manage the booking service for vaccination campaigns run by a Local Health Authority (ASL). The booking system is managed by ASL staff, who can enter each vaccination campaign as needed (influenza, Covid-19, SARS, and so on).

From time to time, staff activate vaccine administration availability by specifying:
- the specific vaccine,
- the available days and time slots,
- the clinics/medical offices available,
- and the eligible citizen categories for each vaccination campaign.

Availability is defined according to vaccine stock levels for the different campaigns.

Citizens who join a given vaccination campaign can access the booking system after registering. During registration, they must provide first name, last name, and tax code (*codice fiscale*), and they will be informed of their specific eligibility category (e.g., "over 80", "age 70–79", "oncology patient", "hypertensive patient", "at-risk patient", and so on), which is already known by the system.

If the citizen is not found in the registry available to the system, the system will notify the citizen of this issue and provide an email address where they can send any requests for clarification.

Once registered, citizens can log in and see the vaccination campaigns they are eligible for. For each campaign, the citizen can view the available times and locations day by day and select their preferred appointment time at the clinic of their choice.

The system must of course support multiple simultaneous registrations and bookings by different citizens.

The system also shows the citizen the time window for which availability has been defined based on stock levels, and clearly highlights the periods for which ASL staff have not yet entered availability. In this way, the citizen can distinguish between:
- booked slots,
- available slots,
- and slots that are not yet managed/defined.

The system notifies a citizen—if they requested it through the system—when a given time period becomes available for booking for a specific vaccination campaign.

ASL staff associate each vaccination campaign with the citizen categories that are entitled to receive vaccinations with a specific vaccine.

The system stores essential demographic data for each citizen:
- tax code (*codice fiscale*),
- health insurance card number,
- last name and first name,
- place and date of birth,
- eligibility categories (oncology patient, hypertensive patient, at-risk patient, etc.),

and it verifies that the data provided during individual citizens' registrations is correct with respect to the registry available to the system.
