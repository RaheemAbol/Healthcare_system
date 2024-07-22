# Healthcare_system





### Ticket Breakdown



1. **Ticket 1: Create `Patient` Class**
   - **Description:** Implement a `Patient` class with the following attributes and methods:
     - **Attributes:**
       - `patientID` (int)
       - `name` (String)
       - `medicalHistory` (List of `MedicalRecord`)
     - **Constructor:**
       - A constructor to initialize `patientID`, `name`, and `medicalHistory`.
     - **Methods:**
       - Getters/setters for `patientID`, `name`, and `medicalHistory`.
       - Method `addMedicalRecord(MedicalRecord record)` to add a record to `medicalHistory`.
       - Method `updateMedicalRecord(int index, MedicalRecord newRecord)` to update a record in `medicalHistory`.
       - Method `getMedicalRecord(int index)` to get a specific medical record.
   - **Tasks:**
     - Create the `Patient` class.
     - Define the specified attributes.
     - Implement the constructor.
     - Generate getter/setter methods.
     - Implement `addMedicalRecord`, `updateMedicalRecord`, and `getMedicalRecord` methods.
     - Ensure the class adheres to Java coding standards.

2. **Ticket 2: Create `Inpatient` Class Extending `Patient`**
   - **Description:** Implement an `Inpatient` class that extends `Patient` with additional attributes and methods:
     - **Attributes:**
       - `admissionDate` (String)
       - `roomNumber` (String)
     - **Constructor:**
       - A constructor to initialize `patientID`, `name`, `admissionDate`, and `roomNumber`.
     - **Methods:**
       - Getters/setters for `admissionDate` and `roomNumber`.
       - Override `toString()` method.
   - **Tasks:**
     - Create the `Inpatient` class extending `Patient`.
     - Define the additional attributes.
     - Implement the constructor.
     - Generate Getters/setters methods.
     - Override the `toString` method.
     - Ensure the class adheres to Java coding standards.

#### **Developer 2:**

3. **Ticket 3: Create `Outpatient` Class Extending `Patient`**
   - **Description:** Implement an `Outpatient` class that extends `Patient` with additional attributes and methods:
     - **Attributes:**
       - `appointmentDate` (String)
       - `doctorName` (String)
     - **Constructor:**
       - A constructor to initialize `patientID`, `name`, `appointmentDate`, and `doctorName`.
     - **Methods:**
       - Getters/setters for `appointmentDate` and `doctorName`.
       - Override `toString()` method.
   - **Tasks:**
     - Create the `Outpatient` class extending `Patient`.
     - Define the additional attributes.
     - Implement the constructor.
     - Generate Getters/setters methods.
     - Override the `toString` method.
     - Ensure the class adheres to Java coding standards.

4. **Ticket 4: Create `MedicalRecord` Class**
   - **Description:** Implement a `MedicalRecord` class with the following attributes and methods:
     - **Attributes:**
       - `date` (String)
       - `description` (String)
     - **Constructor:**
       - A constructor to initialize `date` and `description`.
     - **Methods:**
       - Getters/setters for `date` and `description`.
       - Override `toString()` method.
   - **Tasks:**
     - Create the `MedicalRecord` class.
     - Define the specified attributes.
     - Implement the constructor.
     - Generate Getters/setters methods.
     - Override the `toString` method.
     - Ensure the class adheres to Java coding standards.

#### **Developer 3:**

5. **Ticket 5: Create `Hospital` Class**
   - **Description:** Implement a `Hospital` class with the following attributes and methods:
     - **Attributes:**
       - `patients` (List of `T extends Patient`)
     - **Constructor:**
       - Default constructor.
     - **Methods:**
       - `addPatient(T patient)` to add a patient to the list.
       - `getPatient(int patientID)` to retrieve a patient by ID.
   - **Tasks:**
     - Create the `Hospital` class.
     - Define the specified attributes.
     - Implement the default constructor.
     - Implement `addPatient` and `getPatient` methods.
     - Ensure the class adheres to Java coding standards.

6. **Ticket 6: Implement `MedRunner` Class**
   - **Description:** Implement a `MedRunner` class with a `main` method to demonstrate the functionality of all the other classes.
   - **Tasks:**
     - Create the `MedRunner` class.
     - In the `main` method, create instances of `Patient`, `Inpatient`, `Outpatient`, `MedicalRecord`, and `Hospital`.
     - Demonstrate the creation, modification, and retrieval of data.
     - Ensure the `main` method clearly shows the workflow of the hospital management system.

