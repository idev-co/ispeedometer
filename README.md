# iSpeedometer
Hologram Speed Script edited for RP server (fuel ui and fixed problems with ui)

⚠️This is not a Seatbelt System, only a "Vehicle HUD"

Modification of <a href="https://github.com/kasuganosoras/hologramspeed">HologramSpeed</a>, code was rewriting mainly by <a href="https://github.com/s1nyx">Sinyx</a> and <a href="https://github.com/TheSpaceGamerV2">Space V</a> due to
bugs where the nui was disappearing and added an NUI for fuel (it's adapted for LegacyFuel but can be change easily in the config.)

How to adapt your seatbelt script to iSpeedometer
```lua
     TriggerEvent("hologramspeed:seatbeltUpdate", true) -- put seatbelt to ON (in HUD)
     TriggerEvent("hologramspeed:seatbeltUpdate", false) -- put seatbelt to OFF (in HUD)
```
You can use the <a href ="https://github.com/idev-co/iSpeedometer/releases/tag/seatbelt">release /example</a> if you don't know what are you doing

You can have support on our <a href="https://discord.gg/8ecXhFXqR4">Discord</a> (FR/ENG)


![Capture d’écran 2022-04-26 222512](https://user-images.githubusercontent.com/40030799/165386454-b5a423b9-eaa4-44de-a692-dc3ae52db71d.png)


Dependency 
 - <a href="https://github.com/InZidiuZ/LegacyFuel">LegacyFuel</a> (can be change easily from the config)
