DO NOT DOWNLOAD NOT COMPLETED - WAIT FOR RELEASE

<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://github.com/othneildrew/Best-README-Template/blob/master/images/logo.png?raw=true" alt="Logo" width="80" height="80">
    
    <!--ts-->
   * [Installation](#installation)
   * [Usage](#usage)
      * [STDIN](#stdin)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
      * [Auto insert and update TOC](#auto-insert-and-update-toc)
      * [GitHub token](#github-token)
      * [TOC generation with Github Actions](#toc-generation-with-github-actions)
   * [Tests](#tests)
   * [Dependency](#dependency)
   * [Docker](#docker)
     * [Local](#local)
     * [Public](#public)
<!--te-->
  </a>


<h1 align="center">What is 'jays_jobs'?</a></h1>  
jays_jobs is my take on a replacement for esx_jobs, personally I feel that esx_jobs is not very well optimised and lacks some features such as easy customisation due to the way that its built etc... Anyway, in creating jays_jobs I wanted to add the ability to easily toggle peds, blips and 3DText at a set of coords, to do this I have used tables and almost everything is handled client side in less than 100 lines of code. I have put an example in the config for 'miner' job, you can remove this or keep it however use this as a base for making a new job. Look at 'Adding a job to config' for tips on how to get this perfect!

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
