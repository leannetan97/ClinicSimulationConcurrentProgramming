# Clinic Simulation Concurrent Programming<br>(Concurrent Programming Assignment WIF3003)

This is a Clinic Simulation in Java. In this project, the reader class, each patient and doctors will be run as a thread.
There are severals

## Case Description
A hospital has 10 clinics, each run by a doctor. The doctors will see walk-in patients in the morning from 8.00a.m. to 12.00p.m.Monday to Friday.
On average, there are 120 to 150 patients visit the hospital daily. Each doctor will spend 10 to 25 minutes (consultation time) to see a patient.
A patient will arrive at the hospital every 1 to 3 minutes, up to 3 patients may arrive at the hospital at once. Occasionally, 1 to 2 doctors may be on annual, medical or emergency leaves.
<br><br>
<b>The hospital adopts a policy that in a day:</b>
1. Doctors should see the same number of patients as much as possible.
2. The number of patients seen by a doctor should not differ by 3 or more with another doctor.
3. When a patient arrives at the hospital, he/she will be assigned to a doctor who has seen or is seeing the least number of patients.
4. At one particular time, there must not have more than 3 patients waiting to be seen by a doctor.
5. If all the doctors have 3 patients in their waiting list while a patient walks in, the patient will be placed in a common waiting list, waiting for the next available doctor.<br>
6. After seeing 8 patients, a doctor will take a 15 minutes break, during which the doctor will not accept any new patients. 
7. After all the clinics have closed, the system will generate a performance report showing data such as:
   * Number of patient visits<br>
   * Number of patients seen by each doctor<br>
   * Average time spent (consultation time) with a patient by each doctor and all doctors overall
   * Average waiting time per patient by each doctor and all doctors overall
    
## Deliverables 
Simulate:
1. Best Case
2. Normal Case
3. Worst Case

## Contributors :
1. Heng Xin Ting&nbsp;&nbsp;WIF160008
2. Tan Lay Yan     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;WIF160058
3. Lee Chia Jee    &nbsp;&nbsp;&nbsp;&nbsp;WIF160011
4. Wong Zi Ying  &nbsp;&nbsp;WIF160065
