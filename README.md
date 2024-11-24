# Online-voting-systemOnline Voting System

Online Voting System
An efficient and secure voting application for students, featuring ID-based validation and a straightforward voting interface.

🚀 Features
Preloaded Student IDs: Validates voters using a list of IDs loaded from a file.
User Authentication: Ensures only registered students can vote.
Personalized Experience: Displays the voter's name upon successful login.
Secure Voting: Allows one vote per student.
Results Compilation: Tracks and stores voting results for review.
🛠️ Technologies Used
Language: C++
File Handling: Used for managing student IDs and saving votes.
Optional GUI: Can be enhanced using Qt for graphical user interaction.
📋 Setup Instructions
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/online-voting-system.git
cd online-voting-system
Prepare the Environment

Install a C++ compiler (e.g., g++).
Place a students.txt file with preloaded student IDs in the working directory. The format is:
Copy code
ID,Name
101,John Doe
102,Jane Smith
Compile and Run

bash
Copy code
g++ -o OnlineVotingSystem main.cpp
./OnlineVotingSystem
Voting Process

Run the program.
Enter a valid student ID.
After ID validation, select your preferred candidate.
📂 File Structure
less
Copy code
online-voting-system/
├── main.cpp         // Main program logic
├── students.txt     // Preloaded student IDs and names
├── votes.txt        // Stores voting results
├── README.md        // Documentation
💡 Future Enhancements
Build a user-friendly GUI using Qt.
Add features for real-time result visualization.
Introduce admin roles for managing the voting process.
