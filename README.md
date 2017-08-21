A couple of scripts for building a bleeding edge AMI image for OmniOS.

Broadly we:

* Start with an ami-ae5742cd and log in
* Run 'curl -s https://raw.githubusercontent.com/RantyDave/omnios-tools/master/binary-update-to-ami | sh'
* Poweroff and make the AMI

Note that ec2-drives-as-swap needs you to explicitly attach the instance drives to the instance when you create it.
