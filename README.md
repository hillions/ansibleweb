A basic ansible playbook to configure Apache webservers and HTTPS proxy in front. 
* Update ``hosts`` with SSH targets.
* Update ``ansible.cfg`` with SSH private key.
* Requires x509 certificate pairs.

Example sites behind single proxy host:
* [web01.hillions.net](https://web01.hillions.net)
* [web02.hillions.net](https://web02.hillions.net)
* [web03.hillions.net](https://web03.hillions.net)
