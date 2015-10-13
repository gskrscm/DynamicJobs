# DynamicJobs
Dynamically spin up Jenkins jobs

Version: 1.0 

- Find diff's between two config.xml files and create template. (Mainly now: Artificat, Workspace, Node name) - Manual step
- Create new job from template (involves creating a dir & copy new config.xml file)
- Replace new job (config.xml)with right values from json file. 
- Reload Jenkins disk  http://stackoverflow.com/questions/5216552/does-anyone-know-how-to-reload-hudson-configuration-without-restarting 

Version 2.0 

- Changes to template have propagate to all existing jobs. 