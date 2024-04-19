Setup instructions :
Server setup :
Build the windows service project present in the path "master/SocketServerWinService"
Install the windows service by following instructions in the file path "master/SocketServerWinService/ServiceInstructionsReadme.txt"
Create a firebase account for authentication service, and store the WebapiKey under the machine environment variable "ChatServerFirebaseApiKey"
Additional router settings for use of chat application over internet :
Port forwarding must be enabled on your router, follow similar steps as presented in the path "master/AdditionalConfigsProcesses/HathwayRouterSetup" in the server router.
Client setup :
Change the appSetting "ServerIP" to the server IP address, present in the file "master/ClientDesktopUI/App.config"
Build the project "master/ClientDesktopUI"
Build the installer project "master/ClientDesktopUISetup" (Requires Visual studio installer projects extension to be installed)
Run the setup and install the chat application on all the client computers
