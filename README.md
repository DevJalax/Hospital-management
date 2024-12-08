# Hospital-management

# Microservices 

1) Patient Registration:
Collect basic information (name, contact details, emergency contact).
Record medical history (allergies, previous illnesses, surgeries, etc.).
Assign a unique patient ID.

2) EHR Creation:
Create and maintain the patient's digital health record, including diagnoses, treatments, and medications.
Store medical imaging, lab results, and other diagnostic data.

3) Patient health forecast : Analyze patient history to predict future health risks or suggest preventive measures.

4) Appointment scheduler : Allow patients to book, reschedule, or cancel appointments with available doctors.
Display doctor availability based on their calendar. track Appointment History. If an appointment slot is filled, add patients to a waitlist and notify them when a slot becomes available.

5) Prescription Management :
a) Process electronic prescriptions from doctors and generate medication orders.
b) Ensure prescription validity (e.g., checking for drug interactions, dosage limits).
c) Track stock levels of medications, expiration dates, and reorder thresholds.
d) Enable pharmacists to add new drugs and update stock levels.
e) Generate dispensing records and track medications dispensed to each patient (based on patient id).

## ER diagram :

![DB_relation_diagram](hospital.png)
