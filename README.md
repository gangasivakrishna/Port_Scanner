# Port_Scanner
Requirements to run this program:
      1 Socket
      2 Datetime 
      3 Sys 
      4 Time
      
STEP 1:
from socket import * - From the socket module, import everything

import sys, time - Import the sys module, Import the time module ( We can import as many modules as we want so far as we put a comma in between them )
from datetime import datetime - From the datetime module, import function datetime and leave the rest

STEP 2: DECLARING PROGRAM SETTINGS

Initializing host and port number(min,max)

STEP 3: INITIATING PROGRAM

Lets ask the user for the target host address, This could be a url address of the host or the direct numberic ip address.

STEP 4: GETHOSTBYNAME

This function simply returns the ip numberic values of a host address or url.

STEP 5: SCANNING

Scanning ports from range 1 to 5000

STEP 6:

Displaying results
