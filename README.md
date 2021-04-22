#To run the code aka "e J 0 |3" portal follow the commands

1. cd frontend
1. npm install
1. cd ..
1. cd backend
1. npm install
1. npm run dev

## Which of the Bonus parts are implemented
1. Fuzzy Search
1. When a recruiter accepts an applicant, he gets an email from the portal
1. An attempt was made to implement the upload image for applicant, the code for that is commented in the code.

## For the rating of the applicant, recruiter and jobs
I have followed a different convention i believe. What i am doing is lets say an applicant is accepted into a job then the applicant can rate the recuiter and once he rates him the overall recruiter rating will be calculated by the average of all the ratings he recieved till date. So here we will get two ratings for the recruiter, one for that particular job and the other one is the overall rating. Now when a recruiter employees someone then the recruiter can rate the employee, following which i will again get two ratings for the applicant one is the rating specific to that job and the other one is the cumulative average of all the ratings he received till date. The ratings are editable.

## For the register part
For registering both the applicants and recruiters i am only making the name, email and the password compulsory. Other details need not be entered while registering because as in lets cosnider linkedin it allows me to browse everything even if i dont enter my details like my education. So to enter the details of education and skills(for applicant) and contact number and bio(for recruiter), one has to navigate to profile page then to edit profile where the user can add the respective fields.
