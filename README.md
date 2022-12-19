## this script takes input from wfuzz wordlists of vulnerable paths, reads line by line and inputs into httpx.
# inside the loop, we cat all the subdomains pass it as an argument and append each directory path from our fuzz list into httpx through burp proxy.
## this helps find valid directories and much easier to discover paths, we can use any directory fuzzing list in this, just replace wfuzz with any other fuzz list.
