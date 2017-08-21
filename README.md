A couple of scripts for building a bleeding edge AMI image for OmniOS.

Broadly we:

* Start with an earlier image
* Run 'build-latest'
* Reboot
* Run 'pre-ami-clean'
* Poweroff and make the AMI

Note that ec2-drives-as-swap is under suspicion at the moment...
