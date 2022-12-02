history 
why docker 
- image : read only templete, shared with other by register.
- existing image  as a base image
-** creatinh image : from dockerfile and  using docker commit command
- distrubting images : using default docker hub registry, you can create public or private
--> you can acrhieve (tar it ) 
#-------------------------------------------------------------------
layers : 
writable layers avaiable in contaier but not in image
- writes all modification on it, 
-multiple container can access the same uderlying image and no access the data state
