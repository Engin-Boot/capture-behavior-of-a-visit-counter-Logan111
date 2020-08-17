# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given
  When
  Then

Scenario: Alert when seating capacity is full

  Given with the proper functioning of hospital servers and total visitors count
  When visitors count equals with seating capacity and choose to "alert security"
  Then alert is sent to the security department so they can block new visitors
