# Step 1: Create a new directory for your repository and navigate to it
mkdir student_repository
cd student_repository

# Step 2: Initialize a Git repository
git init

# Step 3: Create a data file (e.g., students.csv) and add student information
echo "Name,Admission Number,Fee,Class,Teacher,Timing,Duration" > students.csv
echo "John Doe,12345,5000,Grade 8,Mr. Smith,9:00 AM - 10:30 AM,1 hour 30 minutes" >> students.csv
echo "Jane Smith,67890,5500,Grade 9,Mrs. Johnson,11:00 AM - 12:30 PM,1 hour 30 minutes" >> students.csv

# Step 4: Add and commit the data file to Git
git add students.csv
git commit -m "Add student information"

# Optional Step 5: Set up a remote repository (e.g., GitHub) and push your code
# Follow the instructions provided by your remote hosting service
