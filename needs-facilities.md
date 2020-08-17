# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given
  When
  Then

Scenario: Alert when seating capacity is full

  Given with the proper functioning of hospital servers and total visitors count
  When the visitors count equals the seating capacity 
  and there is option to "alert security"
  Then alert meassge is sent to the security department 
  so that they can block new visitors
