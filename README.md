# burst

This repo works to build the instances as specified.

This one thing does not work:

At the end of the apply, Terraform should print out the IPs of the instances and any
information needed to log into server1 or server2.

I tried to get splat interpolation to work and tried a lot of things, but never could get it to work.

You can get the instance IP addresses via this command:

aws ec2 describe-instances|grep PublicIpAddress

This is pretty unfortunate, it is probably a super simple miss, but I can't figure it out and have run out of time /shrug

Marc Richardson
