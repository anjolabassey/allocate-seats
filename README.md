# allocate-seats

Reservation System

In a reservation system, an algorithm is utilized to prioritize the seat allocation to people. This allocation process starts with collect the applications from each candidate for the seat. Each application should capture Name, Age, and Gender. After collecting all the applications, below prioritization rules will be applied.

The reservation system has 2 compartments.
Senior
b. General
2. All Senior people (Age > 60) should be allotted into Senior compartment on first come first serve basis
3. If any seats in Senior are left out, they should be filled with rest of the applicants 
a. All Female passengers take priority
b. Rest of the passengers should be allotted in first come first serve basis
4. General compartment allocation will be strictly based on first come first serve basis

Write a JavaScript program to allocate seats for 3 Senior, 5 Male and 3 Female members into 2 compartments of 5 seats each. 
