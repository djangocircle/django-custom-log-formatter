# Django Logging Formatter

Here is step by step explanation on <a href="https://djangocircle.com/how-to-create-different-custom-logs-formatter-for-info-warning-and-error-logs-in-django-web-application/"> How to create different custom logs formatter for Info, Warning and Error logs in Django web application? </a> 

If you wish to implement the logs with your own choice of default information in it. It is implemented in this project.

For example:
1)Info Log Format:
```
  <Log Level>: <Message> - <File Location>:<Line No>
 ```
2)Warning Log Format: 
```
  <Log Level>: <Message>
```
3)Error Log Format:
```
  <Log Level>: <Datetime> <Filename> <Http Method> <Message> <File Location> <Line No.>
```  
