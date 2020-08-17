# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

   Given with the proper functioning of hospital servers and visitor cards count 
  When the visitor goes and comes out doesnt matter
  Then the count of visitor cards is enough to say number of visitors a week

Scenario: Alert when seating capacity is full

  Given with the proper functioning of hospital servers and total visitors count
  When visitors count equals with seating capacity and choose to "alert security"
  Then this alerts the security department so they can block the new visitors
