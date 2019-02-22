
Simple SOAP Web Service Using Java

## How to use

- Download this project
- Download and install Apache Tomcat
- Download and install SOAPUI
- Open Eclipse and import this project
- Right click on this project and choose export WAR and choose the destination folder
- Copy the WAR file to [Apache Tomcat's directory]/webapp
- Run Apache Tomcat
- Open this link http://localhost:8080/ProductCatalogSOAPService/services/ProductCatalogServiceImpl?wsdl in the web browser to check if the web service running or not 
- Open SOAPUI
- File->New SOAP Project
- Project Name : ProductCatalogSOAPServiceTest, Initial WSDL : http://localhost:8080/ProductCatalogSOAPService/services/ProductCatalogServiceImpl?wsdl
- Check the "Create sample requests for all operations?" checkbox and click OK
- Double click on each Request 1 (try one by one) in the projects tree
- Hit the green play button to try the SOAP requests, SOAP response will showed in the right window if succeed

