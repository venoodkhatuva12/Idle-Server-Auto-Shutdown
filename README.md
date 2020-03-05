# Idle-Server-Auto-Shutdown

AWS Server should be cost effective , lets say you are running a demo or tutorial servers and you forgot to stop it.
Here is a script which will stop the server automatically if it checks there is no activity in the server for 30 min.
No Activity in server it ll shutdown automatically most used in AWS.

# Follow the Steps.

Add Cron Job like below.
```
*/10 * * * * sh -x /boot/idle.sh &>/tmp/idle.out ```
