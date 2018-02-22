# DNS server with python
# Didn't manage to get it to work, query isn't in the right format

Binds to port 53 and local host ip. Essentially tries to create a DNS query using the bytes recieved from the dig command, attempting to construct the tid, ttl, question/a, etc. Didn't manage to get the rest to work but the tid seems to work.

