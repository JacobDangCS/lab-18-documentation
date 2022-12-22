# Lab 18 Documentation


## Data & Program Flow
Flow can be seen in UML. In my perspective I was able to understand, witness, and predict the flow of data that persisted throughout importing the zipped files, creating the methods, testing the functionality, as well as formulating communications that track how and where data is going. Progress logs below document progression in lab as well.

### What is the root URL to your API?
- Unable to configure root URL, here's images from progress:
[GET&CREATE](./assets/image1.png)
[PUT&DELETE](./assets/image2.png)
- Update: [ROOTURL](https://k8ooxf2jge.execute-api.us-west-2.amazonaws.com/Production)

### What are the routes?
- Routes include: 
    - /people this functionality is useful for READ & CREATE
    - /people/id this functionality is useful for PUT & DELETE

### What inputs do they require?
- The inputs required include the route as well as navigating functions of CRUD

### What output do they return?
- The output should be schemas related to the CRUD function used

## Progress Logs
- Log 1: Was able to create respective functions, tables, and roles
- Log 2: Was able to send a zipped file containing required info of Read into Lambda & able to get a response using scan method
- Log 3: Was able to follow demo and create a handle Read & handleCreate 
- Log 4: Was able to create a basic handler for Delete & Update using the procedure of zipped files, role assignment, and linking the Lambda function to method


## UML
[UML](./assets/Lab18.png)
