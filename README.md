# GO TO </br>
# launchSettings.json and edit</br>
# make sure you got proper application name in my case WebApplication1 </br>
# IN SHORT </br>
# in profiles -> WebApplication1 set "applicationUrl": "http://localhost:57570", instead of "applicationUrl": "https://localhost:5001;http://localhost:5000",</br>
</br>
{</br>
  "iisSettings": {</br>
    "windowsAuthentication": false,</br>
    "anonymousAuthentication": true,</br>
    "iisExpress": {</br>
      "applicationUrl": "http://localhost:11368",</br>
      "sslPort": 44318</br>
    }</br>
  },</br>
  "profiles": {</br>
    "IIS Express": {</br>
      "commandName": "IISExpress",</br>
      "launchBrowser": true,</br>
      "environmentVariables": {</br>
        "ASPNETCORE_ENVIRONMENT": "Development"</br>
      },</br>
      "inspectUri": "{wsProtocol}://{url.hostname}:{url.port}/_framework/debug/ws-proxy?browser={browserInspectUri}"</br>
    },</br>
    "WebApplication1": {</br>
      "commandName": "Project",</br>
      "launchBrowser": true,</br>
      "environmentVariables": {</br>
        "ASPNETCORE_ENVIRONMENT": "Development"</br>
      },</br>
      "dotnetRunMessages": "true",</br>
      "applicationUrl": "http://localhost:57570", // DISABLED SSL, DEBUGGING WORKING </br>
      //"applicationUrl": "https://localhost:5001;http://localhost:5000", // ENABLE SSL, DEBUGGING NOT WORKING!!! </br>
      "inspectUri": "{wsProtocol}://{url.hostname}:{url.port}/_framework/debug/ws-proxy?browser={browserInspectUri}"</br>
    }</br>
  }</br>
}</br>
</br>
