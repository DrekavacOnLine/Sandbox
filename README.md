# Sandbox
Both Sandbox.postman_environment.json and MODULE-Sandbox.postman_collection.json files need to be imported in postman. As result, collection "MODULE: Sandbox" and environment "Sandbox"will be created. To run all created tests automatically one must open Postman Runner, chose collection, environment and data dile as shown below and execute it:

![Collection Runner](https://github.com/DrekavacOnLine/Sandbox/blob/master/Collection%20Runner.png)

![Collection Runner Results](https://github.com/DrekavacOnLine/Sandbox/blob/master/Collection%20Runner%20Results.png)

In addition, if ![Newman](https://www.npmjs.com/package/newman) is installed on the system, it can be used to generate rich HTML report (see command line in file ![package.json](https://github.com/DrekavacOnLine/Sandbox/blob/master/package.json)). Final step will be to automate tests execution via automation server, like [Jenkins](https://jenkins.io/): 

![Jenkins stage view](https://github.com/DrekavacOnLine/Sandbox/blob/master/JenkinsStageView.png)

![Jenkins console output](https://github.com/DrekavacOnLine/Sandbox/blob/master/JenkinsConsoleOutput.png)

Example of HTML report generated via Jenkins run can be found [here](https://htmlpreview.github.io/?https://github.com/DrekavacOnLine/Sandbox/blob/master/Postman_API_Tests.html).
