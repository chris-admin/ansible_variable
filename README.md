## ansible_variable
 
Little test how to work with variables in ansible. For the write part it looks like throttle 1 is needed otherwise the file gets written multiple times simultaneously. The result was a lack of information. If you rerun the script it will not add another line. (Maybe the idempotency is the reason for that)

For better understanding this was the regular /etc/resolv.conf output:

nameserver 127.0.0.11 <br>options ndots:0
