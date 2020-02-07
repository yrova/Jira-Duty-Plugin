# Jira Other Duty Plugin

Jira Duty Plugin for Atlassian JIRA® Server

## Which problem does the plugin solve?

Glad you asked. Regular work duties are usually regulated and tracked but what about all the duties people forget about. Im talkin KITCHEN duty. Why is the dish-washer full of dirty dishes but not turned on? Why are there no clean dishes? With this plugin you can assign tasks and hold the office knave accountable for their transgressions. 

## Required functionality

### Upon new installation of the plugin  (DONE)
  * create a unique ID
  * persist it so that it can be used in other components
  * make an HTTP request to send it to an [external service](https://postman-echo.com)
  * erase persisted unique ID upon plugin uninstallation

### Webworkaction and HTML view
### User Search Rest Resource
### User Search JS Controller
### Duty planning REST Resource 
### Duty Planning JS Controller
### Story workshop
### Duty Overview Page
  
## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## References

* [atlassianjdk](https://developer.atlassian.com/server/framework/atlassian-sdk/set-up-the-atlassian-plugin-sdk-and-build-a-project/) - Hello World tutorial for a Jira plugin
* [SAL](
https://developer.atlassian.com/server/framework/atlassian-sdk/storing-plugin-settings/) - Shared Access Layer
* https://comsysto.github.io/kitchen-duty-plugin-for-atlassian-jira/tutorial/01-introduction/ - Good tutorial jira server plugins in general



