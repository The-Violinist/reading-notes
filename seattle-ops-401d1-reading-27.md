David Armstrong 11-10-2020

Once one has decided to use Splunk to monitor a network, the next task is to get the required 
data going to the Splunk Server. One of the tools that is used is Splunk’s Universal Forwarder. 
This is a very thorough means of creating a data stream, especially when it comes to Windows 
endpoints. According to the documentation, as compared to the Windows Management Instrumentation, 
the Universal Forwarder provides the most sources of data and the simplest configuration.

One point that is made, and one that I came across in the lab, is that full configuration should 
be performed at the time of installation. This is particularly helpful to know, especially in 
light of the fact that there is no GUI for the Forwarder. It appears that there is a limited 
degree of configuration that can be done either in the .conf files or through the CLI. In addition 
to the Windows-side Forwarder, there is a Windows Add-on which can be attached to the Splunk Server 
to provide additional benefits such as monitoring Active Directory and Microsoft DNS.
