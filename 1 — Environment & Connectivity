# WEEK 1: ENVIRONMENT & CONNECTIVITY
 
import sys
import platform
import socket
 
print("===== WEEK 1: ENVIRONMENT & CONNECTIVITY =====")
 
print("Python Version:", sys.version)
print("Operating System:", platform.system())
print("Computer Name:", socket.gethostname())
 
try:
    socket.create_connection(("www.google.com", 80), timeout=5)
    print("Internet Connection: Connected")
except OSError:
    print("Internet Connection: Not Connected")
 
print("Environment & Connectivity Check Completed Successfully!"
