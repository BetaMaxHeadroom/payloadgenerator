# MSFvenom Paymaker
 
Paymaker is a tool to generate the most common Meterpreter payloads via msfvenom (part of the Metasploit framework).
 

# About
Paymaker is a wrapper around MSFvenom which gives the user a more friendly and simpler experience to generate multiple types of payloads, based on his/her choice. Our intent is to make the experience uncomplicated to produce their payload.
Instead of the user going through msfvenom manually looking for a specific payload our goal is to automate the process for them as well as customizing the payload generating experience ( or customize the payload for their needs.)  We will ask the user certain questions defining their target and then call msfvenom to generate a payload according to the answers that are given.
 
Required input from the user: 
* Platform: Windows, Linux, OSX
* Architecture: 64 bit or 32 bit
* Shell: Bind or reverse
* If it is a reverse shell: Your IP and the port you want to listen on
* If it is a bind shell: Target IP and port
* Meterpreter: y or n
* Type: Staged or Stageless
* Format: exe, raw, pl, rb, c, elf
* Name of your generated payload file
 
We also included Advanced Options:  
* Do you want to encode your payload ( to avoid anti-virus )
