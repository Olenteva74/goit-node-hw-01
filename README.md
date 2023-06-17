# Create Command-Line-Interface - CLI

1. Receive and display the entire list of contacts in the form of a table (console.table)  
``` javascript
node index.js --action="list"
```  
![screenshoot](https://monosnap.com/file/fP7al1pIms6rU95txhuaQwuvEuIFpI)

2. Get the contact by id and output the contact object to the console or null, if there is no contact with such an id  
```javascript
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
```  
![screenshoot](https://monosnap.com/file/5o3FnwEjtLMbkblr2L8APQbXAlBDCF)

3. Add a contact and display the object of the newly created contact in the console 
```javascript 
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
```  
![screenshoot](https://monosnap.com/file/9eoYQL81M78LR8ffTHweC3LhfWmgqE)  

4. Delete the contact and output to the console the object of the deleted contact or null, if the contact with such an id does not exist  
```javascript
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
```  
![screenshoot](https://monosnap.com/file/CpqKqsyLRvHCfbUdXoqFdm6zs02LUa)