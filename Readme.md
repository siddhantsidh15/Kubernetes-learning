Learning Kubernetes

---

There is a file called /etc/hosts on your local machine that is used to resolve domain names to IP addresses. We can add entries to that file to resolve our domains to the Gateway load balancer.

Open /etc/hosts in your favorite text editor and add the following lines:

127.0.0.1 synchat.internal
127.0.0.1 synchatapi.internal

On mac use - sudo code /etc/hosts
