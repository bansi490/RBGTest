RBG Developer Test
================================

I have use the following tools to complete my test.

1.Java
2.Eclips IDE
3.Apache Tomcat


Unzip the RBGTestAPI zip file in your local directory. Import the project into editor. Configur the data file(Change the String path in MyServiceClass.java) and run the Application.

Then Open this project on localhost.
    http://localhost:8080/services - It will display all available service.
    http://localhost:8080/services?ServiceCode=CAR_PARK_CLEANSING - It will display only selected ServiceCode data
    http://localhost:8080/services?ServiceCode=ABC - if serviceCode not found return 404.
