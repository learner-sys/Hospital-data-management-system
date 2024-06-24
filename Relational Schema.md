# Relational Schema
Doctor(DID,FName,LName,Gender,Address,DType,Department_ID) </br>
NURSE(NID,FName,LName,Gender,Address,NType,Department_ID) </br>
RECEPTIONIST(RID,FName,LName,Gender,Address,RType,Department_ID) </br>
DEPARTMENT(Department_ID,Location,Type) </br>
ROOM(Room_ID,Type,Department_ID) </br>
PATIENT(Patient_ID,FName,LName,Age,DOB,Phone_Num,MR_Num) </br>
PHONE_NUM(Phone_ID,Patient_ID,Num) </br>
APPOINTMENT(Serial_Num,Time,Date,Room_ID,RID) </br>
MEDICAL_RECORD(Num,Description,Patient_ID,RID) </br>
DRUG(Code,Name,Type,DID,PID) </br>
D_CONSULT_P(DID,Patient_ID,Time,Date) </br>
N_Governs_R(NID,Room_ID,Time,Date) </br>
D_FILL_MR(DID,MR_Num,MR_Type) </br>

#Mapping

![schema](https://github.com/learner-sys/Hospital-data-management-system/assets/143533864/0955f26c-97f0-4a48-b4c8-10bf110d10b7)
