A basic ansible playbook to create CentOS webservers and an HTTPS proxy in front. Requires a 'hosts' file with:

``[webservers]``

``public_ip_1 host_name=host1.name.com private_ip=private_ip_1``

``public_ip_2 host_name=host2.name.com private_ip=private_ip_2``

``public_ip_3 host_name=host1.name.com private_ip=private_ip_3``

``[loadbalancers]``

``public_ip_1 host_name=lb1.name.com private_ip=private_ip_1``
``

[web01.hillions.net](https://web01.hillions.net)

[web02.hillions.net](https://web02.hillions.net)

[web03.hillions.net](https://web03.hillions.net)
