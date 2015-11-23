# Sms Class
 _**\[This is preliminary documentation and is subject to change.\]**_

SMS client class with methods to send and read SMSs.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Eclo.NetMF.SIM800H.Sms<br />
**Namespace:**&nbsp;<a href="N_Eclo_NetMF_SIM800H">Eclo.NetMF.SIM800H</a><br />**Assembly:**&nbsp;Eclo.NetMF.SIM800H (in Eclo.NetMF.SIM800H.dll) Version: 1.1.57.0 (1.1.57.0)

## Syntax

**C#**<br />
``` C#
public class Sms : IDisposable
```

The Sms type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Eclo_NetMF_SIM800H_Sms_DeleteMessage">DeleteMessage</a></td><td>
Delete a text message</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Eclo_NetMF_SIM800H_Sms_DeleteMessages">DeleteMessages</a></td><td>
Deletes text messages according to delete option</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Eclo_NetMF_SIM800H_Sms_Dispose">Dispose</a></td><td>
Releases all resources used by the Sms</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Eclo_NetMF_SIM800H_Sms_ReadMessage">ReadMessage</a></td><td>
Requests to read the text message in the specified position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Eclo_NetMF_SIM800H_Sms_ReadMessagesListAsync">ReadMessagesListAsync</a></td><td>
Starts an asynchronous operation to get a list with message indexes</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Eclo_NetMF_SIM800H_Sms_SendMessageAsync">SendMessageAsync</a></td><td>
Starts an asynchronous operation to send a text message</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#sms-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Eclo_NetMF_SIM800H_Sms_SMSReceived">SMSReceived</a></td><td>
Event raised when the module receives a new SMS message.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Eclo_NetMF_SIM800H_Sms_SMSStatusReceived">SMSStatusReceived</a></td><td>
Event raised when the module receives a new SMS message.</td></tr></table>&nbsp;
<a href="#sms-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Eclo_NetMF_SIM800H">Eclo.NetMF.SIM800H Namespace</a><br />