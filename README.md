# Online-voting-systemOnline Voting System


An efficient and secure application that allows students to cast their votes using a pre-loaded list of IDs. The system ensures proper validation and provides a smooth voting experience.

Features
Preloaded Student IDs: Only valid IDs can access the voting system.
ID Validation: Ensures authenticity and security.
Name Display: Shows the voter's name upon successful login.
Voting Interface: Allows students to cast their votes securely.
One Vote Per User: Prevents multiple votes from the same ID.
Result Compilation: Tracks and saves voting results.
Technologies Used
Programming Language: C++
File Handling: To load student IDs and save votes.
Optional GUI: Can be expanded with Qt for a graphical interface.
Setup Instructions
Environment Setup

Install a C++ compiler (e.g., g++ or an IDE like Code::Blocks or Visual Studio Code).
Ensure the students.txt file (containing student IDs and names) is placed in the working directory.
Running the Program

Compile the program:
bash
Copy code
g++ -o OnlineVotingSystem main.cpp
Run the program:
bash
Copy code
./OnlineVotingSystem
Voting Process

Enter a valid student ID when prompted.
The system will display the student's name.
Select your preferred candidate from the options.
Admin Access (Optional)

If implemented, the admin interface allows viewing all results and vote details.
File Structure
less
Copy code
OnlineVotingSystem/
├── main.cpp         // Core program logic
├── students.txt     // List of student IDs and names
├── votes.txt        // File where voting results are stored
├── README.md        // Project documentation
Future Enhancements
Develop a graphical user interface using Qt for an enhanced user experience.
Add features like real-time vote counting and visualization.
Enable multi-level access controls for admins.

