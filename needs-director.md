Scenario: Show patient visits during working days and holidays
 Given with the permission to  hospital computers
  When a patient visits the hospital he is given with appointment Forum which has a serial number on it
  Then looking into the numbers you can conclude number of patient visits 


Scenario: Compute parking slots to reserve for visiting specialists
  Given with the permission to hospital security monitors
  When I see the parking slots alloted to visiting specialists
  Then I can display the result
