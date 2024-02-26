# Contoso CareScape 

## Chatbot Demo

For details about using this service, 5630 notes in Canvas

1. Login to Azure VM
   
   `ssh azureuser@IP_ADDRESS`
   
3. Create a subdirectoy under home
   
   `mkdir YOUR_NAME`
   `cd YOUR_NAME`
   
5. Clone this repo:

   `git clone repo`
   
7. Navigate to new folder
   
   `cd 5720-bot`
   
9. Update Makefile with PORT given in class
    
   `vi Makefile`



## Building and Publishing

**Note:** if you build your own chatbot update index.html with your chatbot URL.


```
make build
make run
make stop
```
