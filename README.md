# ssh_without_typing_password

1.Generate keygen
	ssh-keygen
	on local pc
2. Copy keygen into linux server
	open cmd on windows pc and paste the command below

	type $env:USERPROFILE\.ssh\id_rsa.pub | ssh 10.100.2.84 "cat >> .ssh/authorized_keys"
3.Test 
	ssh root@10.100.2.84
