# esx_status
How to install:

Put the folder esx_ladderhud inside your resources folder and start it on your server.cfg!
Add TriggerEvent in (resources[esx]\esx_status\client\main.lua esx_status:load)
TriggerEvent('esx_ladderhud:updateBasics', GetStatusData(true))
to look like this

