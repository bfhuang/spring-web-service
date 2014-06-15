This is a small demo of spring web service, which contains three modules. The jaxb module is used to
generate the source code from xsd files. The person service module is use to provide the service to
get person info. The person client module is to call the person service by webServiceTemplate

How to use this project

1.Clone this project
2.Go to the root project, and run 'gradle idea'
3.Run 'gradle :jaxb:generateSource' to generate java source code from xsd files
4.Run 'gradle :personService:jettyRun' to start the service
5.Run the main method in the personClient module to call the person service by webServiceTemplat