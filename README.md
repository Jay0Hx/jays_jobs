# jays_miner
A simple (Work in progress) miner script for ESX

DO NOT DOWNLOAD NOT COMPLETED - WAIT FOR RELEASE

<h1 align="center">What is 'jays_jobs'?</a></h1>


***Features***:
>1. Remove/add peds, blips, 3DText to custom coords, where ever you want!
>2. Add function to each 3DText position with ease!

***Changes***:
>No release to change yet :/

***How to use***:
>This is **not** aimed towards people with 0 expierence in working with LUA, this is not a 'simple' drag and drop resource and does require some tinkering if you want to customise it! It will work out of the box in the latest release but if you want to create your own jobs you will need to have some knowledge with regards to registering events, triggering them and what you want to put inside these events.

***Support***:
>https://discord.gg/WHHsDjm73Y

<h1 align="center">Creating Functions</a></h1>  

>Head to 'client' then 'job_functions'  
>Open the file that you created for the job that you want to create a function for.'
>Paste the following text into that file
   
   ```lua
RegisterNetEvent('jj_FUNCTIONNAME')
AddEventHandler('jj_FUNCTIONNAME', function()
   -- YOUR FUNCTION HERE
end)
   ``` 
   
>Remove 'YOUR FUNCTION HERE' and input what you want that function to do.
>Finally add this function to the config where you need it to trigger.

<h1 align="center">Example of how everything works</a></h1> 
