# Spark

Git Hub Link:
	git clone https://codeload.github.com/spark-mooc/mooc-setup

Vagrant Commands:
	C:\edxspark> vagrant box add sparkmooc/base // Downloads VM from https://vagrantcloud.com/
	C:\edxspark> #vagrant box add sparkmooc/base --insecure // For SSL issues
	C:\edxspark> #vagrant box remove sparkmooc/base // Only incase the download gets corrupt
	C:\edxspark> vagrant init sparkmooc/base
		-> Replace Vagrantfile with the one provided in mooc-setup
	C:\edxspark> vagrant up --provider virtualbox
	C:\edxspark> vagrant halt
	C:\edxspark> #vagrant destroy // End of the course