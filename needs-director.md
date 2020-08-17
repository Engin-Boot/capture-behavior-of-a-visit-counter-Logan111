# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given with proper functioning of hospital servers
  When there is a option of "show patient visits during working days"
  And an option as "show patient visits during holidays"
  Then there pops the "data" as requested

Scenario: Compute parking slots to reserve for visiting specialists

  Given with proper functioning of hospital servers
  When the parking slots are empty
  And an option as "show patient visits during holidays"
  And there is a option to "reserve for visiting specialists" 
  Then the slot would be reserved
