## Splunk Java Modular Inputs v1.0.1  

# Derivation Notes :  

This project is a fork of Damien Dallimore's original work available at <a href="https://github.com/damiendallimore/SplunkModularInputsJavaFramework/tree/master/kafka">https://github.com/damiendallimore/SplunkModularInputsJavaFramework/tree/master/kafka</a>.  This fork updates the Kafka libraries to support <em>Kafka 8.2.2</em> with <em>Scala 2.10</em> and <em>Java 1.8</em>.  

The build.xml and properties are updated to build only the Kafka modular input, as that is all that I need.  Other than this, the only changes are the jar files for Kafka and the Splunk JDK.  

# IMPORTANT NOTE :

Although this framework is fully functional and stable, since it was released Splunk have now created their own Java Modular Inputs librarys.
So I recommend that you use the formally Splunk developed and supported offering that can be found here : http://dev.splunk.com/view/java-sdk/SP-CAAAER2

## Overview

This is a framework for building <a href="http://docs.splunk.com/Documentation/Splunk/latest/AdvancedDev/ModInputsIntro">Splunk Modular Inputs</a> in Java

It contains several example Modular Inputs that you can use as a practical reference to follow.


## Contact

This project was initiated by Damien Dallimore
<table>

<tr>
<td><em>Email</em></td>
<td>ddallimore@splunk.com</td>
</tr>

<tr>
<td><em>Twitter</em>
<td>@damiendallimore</td>
</tr>


</table>
