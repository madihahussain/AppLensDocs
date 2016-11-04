## Possible Solutions
* If problem is only on one instance, try restarting the worker process on that instance
* Scale up to a larger instance size
* Run DaaS to diagnose the problem in your application
*  In cases where you see that the memory pressure is consistently high and the App Service Plan is hosting multiple Web Apps, you can try to move some of the apps to the a different App Service plan to relieve the memory pressure.
* If the memory spikes are intermittent, then you may want to check with the customer if there are any resource intensive operations that are being triggered thru the application. 

