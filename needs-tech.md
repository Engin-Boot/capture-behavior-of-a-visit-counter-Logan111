# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter
  Given with proper functioning server and storage
  When server goes off copy visitor count to storage
  and when server recovers copy from local to server
  Then the server count is maintained

Scenario: Reconcile counts if the sensor is offline for a while

  Given with proper functioning server, sensor and local storage
  When sensor goes off mark the count in local storage to zero
  Then after recovering server, update count from local storage
