# remove-leading-zeros-from-an-ip-address.py

import re
ip = "216.08.094.196"
string = re.sub('\.[0]*', '.', ip)
print(string)

Output:
216.8.94.196
