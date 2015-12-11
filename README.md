# VBoxManageWrapper

Wrapper script for VBoxManage to deal with the missing --syntcpu option not being supported on MacOS X VirtualBox.

I ran into this problem with Terraform and the [virtualbox provider](https://github.com/ccll/terraform-provider-virtualbox).

Adding this script at the start of your PATH will remove the option and the system will work then.
