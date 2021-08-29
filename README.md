# mule-Secure-Properties-Tool
Secure properties tool for mule
Use the Secure Properties Tool to encrypt or decrypt text strings, values inside a properties file, or all the contents of a properties file.
Downloaded from https://docs.mulesoft.com/downloads/mule-runtime/4.2/secure-properties-tool.jar

Usage:
java -cp secure-properties-tool.jar com.mulesoft.tools.SecurePropertiesTool \\
<method> \\
<operation> \\
<algorithm> \\
<mode> \\
<key> \\
<value> \\ --use-random-iv [optional]
  
For example, if you run:

java -cp secure-properties-tool.jar com.mulesoft.tools.SecurePropertiesTool \\
string \\
encrypt \\
Blowfish \\
CBC \\
mulesoft \\
"some value to encrypt"

The tool returns:

8q5e1+jy0cND2iV2WPThahmz6XsDwB6Z
