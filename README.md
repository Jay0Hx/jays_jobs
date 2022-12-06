<br />
<div align="center">
    <img src="https://github.com/othneildrew/Best-README-Template/blob/master/images/logo.png?raw=true" alt="Logo" width="80" height="80">  
    <p align="center">
    <a href="https://discord.gg/WHHsDjm73Y">Support</a>
  </p>
    
[Installation](#installation)  
[Creating a job](#creating-a-job)  
[Creating a function](#creating-a-function)  
[Config Explained](#config-explained)  
</div>

<details><summary>Does work</summary>
[hi](https://hello.ca)
</details>

<h1 align="center">Installation</a></h1>  

<h1 align="center">Creating a job</a></h1> 

<h1 align="center">Creating a function</a></h1>  

   ```lua
------------------------------------------------------ EXAMPLE ------------------------------------------------------
   
RegisterNetEvent('jj_FUNCTIONNAME')
AddEventHandler('jj_FUNCTIONNAME', function()
   -- YOUR FUNCTION HERE
end)
   ```  
   
<h1 align="center">Config Explained</a></h1> 

   ```lua
    [1] = { -- Purchase a Pickaxe!
    jj_blipName           = 'Buy A Pickaxe!',         - This is the blip name that will appear on the map.
    jj_blipType           = 68,                       - This is the blip type https://docs.fivem.net/docs/game-references/blips/
    jj_blipScale          = 0.8,                      - This is the scale of the blip.
    jj_blipColor          = 5,                        - This is the blip color that you want.
    jj_enableBlip         = false,                    - Set this to false if you do not want a blip on the map for this location!
    x                       = 2956.8997,              - X Coords
    y                       = 2743.3557,              - Y Coords
    z                       = 42.6568,                - Z Coords
    h                       = 278.7386,               - This is the heading (Only needed if you are using a PED model)
    jj_enablePed          = true,                     - Set this to false if you do not want a ped at this location!
    jj_enable3D           = true,                     - Set this to false if you do not want floating text on these coords.
    jj_promptText         = '~g~Press [E] to ',       - This is what the floating text says at the listed coords (If enabled).
    functionName            = 'nwrp_dutyToggle',      - This links to 'job_functions'-'NAME.lua'.
    },
   ```  
   
<h1 align="center">What is 'jays_jobs'?</a></h1>  
jays_jobs is my take on a replacement for esx_jobs, personally I feel that esx_jobs is not very well optimised and lacks some features such as easy customisation due to the way that its built etc... Anyway, in creating jays_jobs I wanted to add the ability to easily toggle peds, blips and 3DText at a set of coords, to do this I have used tables and almost everything is handled client side in less than 100 lines of code. I have put an example in the config for 'miner' job, you can remove this or keep it however use this as a base for making a new job. Look at 'Adding a job to config' for tips on how to get this perfect!
