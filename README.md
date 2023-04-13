# JMeterSample

Jmeter functions -> https://jmeter.apache.org/usermanual/functions.html

Samplers

HTTP Samplers
Beanshell Samplers
Debug Sampler
JSR223 Sampler
Different other samplers
JDBC Request
SMTP request
FTP Requests
LDAP Requests
Access Log Requests

Pre-Processors
Beanshell
JSR223 

Post-Processor
Beanshell
JSR223

Logic Controllers
Loop Controller: This controller allows you to run a set of requests multiple times in a loop, either a fixed number of times or until a condition is met.

If Controller: This controller executes a set of requests only if a certain condition is met. The condition is defined using a JMeter function or variable.

While Controller: This controller executes a set of requests repeatedly while a certain condition is true. The condition is defined using a JMeter function or variable.

Switch Controller: This controller allows you to execute one of several sets of requests based on a variable or function value.

ForEach Controller: This controller executes a set of requests for each element in a list or array.

Interleave Controller: This controller runs requests in parallel, one request at a time from each child controller.

Random Controller: This controller selects a random child controller to execute requests from.

Once Only Controller: This controller ensures that a set of requests is executed only once, regardless of the number of iterations or threads.


https://www.vinsguru.com/download/87/


${__time} - This variable returns the current timestamp in milliseconds. It is useful for creating unique values for each virtual user.

${__threadNum} - This variable returns the current thread number. It can be used to create unique values for each thread.

${__P(propertyName,defaultValue)} - This variable allows you to access the value of a JMeter property. The default value is used if the property is not set.

${__V(variableName)} - This variable allows you to access the value of a JMeter variable. It is useful for passing values between different thread groups.

${__RandomString(length,chars)} - This variable generates a random string of the specified length and characters.

${__UUID()} - This variable generates a unique identifier.

${__CSVRead(filename,index)} - This variable reads a value from a CSV file at the specified index.

${__FileToString(filename)} - This variable reads the contents of a file and returns it as a string.

${__property(propertyName)} - This variable allows you to access the value of a JMeter property.

${__groovy(expression)} - This variable allows you to execute a Groovy expression and return the result.

