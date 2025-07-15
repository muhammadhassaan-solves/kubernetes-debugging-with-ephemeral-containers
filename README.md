<h1>Kubernetes Debugging with Ephemeral Containers</h1>


<h2>Description</h2>
This project demonstrates advanced Kubernetes debugging using ephemeral containers. It covers live Pod troubleshooting with kubectl debug, process inspection, and environment analysis. The goal is to perform safe, in-place debugging without restarting or modifying running containers.
<br />


<h2>Tools & Technologies Used</h2>

- Kubernetes
- kubectl
- Ephemeral Containers
- YAML Configuration
- Debugging Images (Ubuntu, BusyBox, Netshoot)
- Linux Utilities (ps, htop, curl, strace, netstat)



<h2>Project Walk-through</h2>

<p align="center">
Deployed Broken and Working Pods <br />
<img src="https://i.postimg.cc/wjNbfN8R/2.jpg"/>
<br />
<br />
Inspected Broken Container with kubectl exec <br/>
<img src="https://i.postimg.cc/FsdPzSKC/3.jpg"/>
<br />
<br />
Introduced Ephemeral Container <br/>
<img src="https://i.postimg.cc/T39G7BXD/6.jpg" />
<br />
<br />
Performed live network troubleshooting using a netshoot ephemeral container  <br/>
<img src="https://i.postimg.cc/htPPBKsr/7.jpg"/>
<br />

</p>

