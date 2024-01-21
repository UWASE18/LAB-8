### Software Architecture

The software follows a modular architecture to ensure scalability and adaptability to evolving educational needs.

## Software Design and Model

### UML Diagrams

#### Figure 1: Sequence Diagram - Student Login

The UML sequence diagram illustrates the interaction between the Student and AttendanceTracker classes during the login process. The sequence begins as the Student initiates a login request, prompting the AttendanceTracker to authenticate the provided credentials. The AttendanceTracker interfaces with the authentication module, validating the student's details. Upon successful authentication, the AttendanceTracker grants access to the Student, allowing them to log in. This concise representation encapsulates the key steps and interactions involved in the student login process within the software system.

![Student Login](.vs/LAB-8/Log%20in.png)

#### Figure 2: Sequence Diagram - Fetch Attendance Data

The UML sequence diagram portrays the interaction between the Student and AttendanceTracker in the context of fetching attendance data. The sequence unfolds as the Student initiates a request, triggering the AttendanceTracker to process the inquiry. The AttendanceTracker, in turn, interacts with the data source to retrieve the attendance records. Once the data is obtained, the AttendanceTracker provides the fetched attendance information back to the Student. This succinct representation encapsulates the key steps and interactions involved in the process of fetching attendance data within the software system.

![Fetch Attendance Data](.vs/LAB-8/Fetch.png)

#### Figure 3: Sequence Diagram - Mark Attendance as Present

The UML sequence diagram depicts the interaction between the AttendanceTracker and UpdateAttendanceData classes when marking attendance as "present." The sequence commences with the AttendanceTracker initiating a request to update attendance data. The UpdateAttendanceData class processes the request, interacting with the data source to record the student's presence. Upon successful updating of attendance, the UpdateAttendanceData class communicates the status back to the AttendanceTracker. This succinct representation encapsulates the crucial interactions and event flow associated with marking attendance as "present" within the software system.

![Mark Attendance as Present](.vs/LAB-8/Present.png)

#### Figure 4: Sequence Diagram - Mark Attendance as Absent

The UML sequence diagram illustrates the collaboration between the AttendanceTracker and UpdateAttendanceData classes during the process of marking attendance as absent. The sequence initiates when the AttendanceTracker sends a request to update the attendance data, triggering the UpdateAttendanceData class. Subsequently, the UpdateAttendanceData class interacts with the data source to record the student's absence. Once the attendance is successfully updated, the UpdateAttendanceData class communicates the status back to the AttendanceTracker. This concise representation encapsulates the essential interactions and flow of events involved in marking attendance as absent within the software system.

![Mark Attendance as Absent](.vs/LAB-8/Absent.png)
