# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given with the proper functioning of hospital servers, visitor cards count
  Given with the count of visitor cards
  When the card is issued once, the daily in and out is not monitored 
  Then the count of visitor cards is enough to say number of visitors a week

Scenario: Alert when seating capacity is full

  Given with the proper functioning of hospital servers and total visitors count
  When visitors count equals with seating capacity and choose to "alert security"
  Then this alerts the security department so they can block the new visitors
