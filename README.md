# smartPopUp
This feature opens a modal that host a form for costumers optin on mouse scroll.  
In order to do not make it invasive the modal opens only once a day and once the user
submits her information the modal wont open again in the future.  
This feature stores logic information in the client via HTML localStorage.


## Links
You can see this widget in action [here](https://masonbottle.com)  
If you want to see the PopUp again, open the console and execute:  
`localStorage.removeItem('showModal_tenOff')`


## Dependencies
* FancyBox v3.1.12
* HTML localStorage

## To Do:
* This feature can benefit from a refactoring effort.
