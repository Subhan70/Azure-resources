https://learn.microsoft.com/en-us/azure/private-link/private-link-service-overview


Private end points are to connect the services internally with private Ip's 
like App service or domain is exposed to outer world, which runs on VM or Azure app services, these needs to connect to DB or storage or keyvaluts,
for this scenario we use end points 
we will one private endpoint for one service : 
 eg: VM -> PE -> Storage 
     VM -> PE -> DB 
<img width="1210" height="453" alt="image" src="https://github.com/user-attachments/assets/666bcafb-e95d-4646-a2e3-faed71cf5e15" />
if we want to connect to one service then we need to create private end points for each 
Private Endpoint(PE) and private links are differnet. 
PE is we created and Private link is managed by PE (we doesnt require to create a private link)
