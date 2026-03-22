# UI-UX---LAB-EX-6

# Hospital Appointment Booking App
## Solution Ideation:

### Step 1: Problem Breakdown
Users fail because:
- Too many steps
- No clarity on availability
- High urgency (health not equal casual task)

### Ideas

| Idea | Description            | Value                  | Risk                    |
|------|------------------------|------------------------|--------------------------|
| 1    | One-tap quick booking  | Fastest flow           | Wrong doctor selection   |
| 2    | Symptom-based search   | Reduces confusion      | Needs accuracy           |
| 3    | Voice booking          | Accessibility          | Tech complexity          |
| 4    | Real-time wait time    | Reduces uncertainty    | Data dependency          |
| 5    | Saved profiles         | Faster repeat booking  | Privacy concerns         |
| 6    | Smart recommendations  | Personalized           | Over-reliance            |
| 7    | Emergency mode         | Priority access        | Misuse risk              |
| 8    | Calendar slot view     | Visual clarity         | UI clutter               |

<img width="393" height="580" alt="image" src="https://github.com/user-attachments/assets/3d1936ed-98c5-45f4-9805-1a09e298abff" />

### Step 2 : Personas & Goals

### Persona 1: Ravi – Student
- **Age:** 20    
- **Goal:** Book appointments quickly with minimal steps  

### Persona 2: Priya – Caregiver
- **Age:** 35  
- **Role:** Manages healthcare for family  
- **Goal:** Easily manage and book appointments for multiple people  

---

##  User Stories

1. **(Ravi – Goal: Quick Booking)**  
   As a busy professional, I want to search for doctors by specialty, so that I can quickly find the right doctor without wasting time.

2. **(Ravi – Goal: Save Time)**  
   As a user, I want to see available time slots in real-time, so that I can book an appointment instantly without delays.

3. **(Ravi – Goal: Faster Repeat Booking)**  
   As a returning user, I want my details to be auto-filled, so that I can complete bookings in seconds.

4. **(Priya – Goal: Manage Family Health)**  
   As a caregiver, I want to book appointments for multiple family members, so that I can manage their healthcare easily.

5. **(Priya – Goal: Reliability)**  
   As a user, I want to receive appointment reminders, so that I don’t miss any scheduled visits.

<img width="470" height="583" alt="image" src="https://github.com/user-attachments/assets/de34c576-d599-4b13-9a44-5838fe7bf3a4" />


### Step 3: Task Flow: Booking Appointment 
1. User opens the hospital app
2. User selects “Book Appointment” or chooses a specialty
3. User searches or selects a doctor
4. User views doctor profile and available slots
5. User selects a preferred time slot
6. Decision: Slot available?
      a. No → Choose another slot/doctor → return to Step 3
      b. Yes → Continue
7. User enters or confirms patient details
8. User selects payment method (if required)
9. Decision: Payment successful?
      a.No → Retry/change payment → return to Step 8
      b.Yes → Appointment confirmed
10. User receives confirmation + reminder → End


### Information Architecture: Hospital Appointment App
1.Card Sorting
Method Used: 
a. Closed sorting - main categories predefined
b. Open sorting - users organize sub-items
### CARDS:
- Book Appointment
- Upcoming Appointments
- Cancel Appointment
- Doctor Search
- specialties
- Doctor Profile
- Ratings & Reviews
- Medical Reports
- Prescriptions
- Payment Methods
- Billing History
- User Profile
- Settings
- Help & Support
- Emergency Booking  

### Sitemap
<img width="908" height="613" alt="image" src="https://github.com/user-attachments/assets/247ee9ed-6007-477b-9b17-38b04c749039" />


## RESULT:
The hospital app is organized into simple sections like Appointments, Doctors, Records, Payments, and Profile was created.
