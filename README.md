# Hospital_Appointment_Scheduler
"A Python-based Hospital Appointment System for managing patient bookings easily. Features include adding, viewing, filtering, and canceling appointments with conflict detection. Designed for beginners to learn list handling, functions, and basic console-based interfaces while keeping data organized."
<br>
A python_based console application for managing healthcare appointments efficiently.The system uses in-memory storage with a list-of-dictionaries structure to handle appointment data,providing full CRUD operations through an intuitive CLI interface.
<br>

CORE ARCHITECTURE<br>
1.Data Layer:Global appointments list storing dictionaries with patient,doctor,date,time and reason fields<br>
2.Business Logic:Four main functions handling appointment creation,listening,filtering by date,and cancellation<br>
3.Validation:Includes conflict detection preventing double-booking and input validation for user choices<br>
<br>
KEY FEATURES<br>
1.Add Appointments: Checks for doctor availibility conflicts using case-insensitive matching<br>
2.View Appointments:Display all entries or filter by specific date using list comprehension<br>
3.Cancel Appointments:Remove by index with bounds checking and error handling<br>
4.Menu System: Continuous loop with five options and clean exit pathway<br>
<br>
TECHNICAL SPECIFICATIONS<br>
1.Time Complexity:O(n) for conflict detection and date filtering <br>
2.Data Persistance:Volatile storage-data lost on program termination<br>
3.Input Handaling:Basic validation for integers and menu choices<br>
4.Error Mangaement:Comprehensive error checking with user-friendly messages<br>
