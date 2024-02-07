# Monitoring_Scripts
Powershell scripts
# Created by arifmuradli, please give credit to my github account when you copy. 
With this scrips, I can remotely monitor and get notifications for Expiration Dates, connections between remote computers, browser links are opened or not, port availability, etc.
01. Expiration Date Check - can be used to monitor how many days remaining until the end of timespan, for example, license expirations.
  Script is designed to be run in PRTG, however can be edited to send mail alerts as well
02. Monitor Browser session in remote computers - This script is especially useful if you want to remotely monitor dashboards, that must be running with specific links opened.This script only checks if the page is open in browser or not. If you close the browser, or browser crushes, it will return value as notconncted, even if remote port is open.
I put plenty of efforts to compose and test these scripts please give credit to my arifmuradli github account when you copy. 
03. Check Network Connection between two hosts - This script is handy especially if there is site to site tunnel and you want to monitor whether remote side is up and accepts connection. This script does not provide information about established connection but rather, it check if connection is possible or not, remote port is open or not. DestinationIP - is not necessarily has to be IP address, it may be a hostname as well and $RemotePC also can be IP address.
