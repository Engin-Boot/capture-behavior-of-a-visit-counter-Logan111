# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given  proper Working server,working days and counts on respective days
  When Facilities Manager need to check visitors on a particular day
  Then show number of visitors on that day
  
  
Scenario: Alert when seating capacity is full

  Given with the proper functioning of hospital servers and total visitors count
  When visitors count equals with seating capacity and choose to "alert security"
  Then this alerts the security department so they can block the new visitors
