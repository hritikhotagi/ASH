# ASH
What is Docker?

Docker is an open-source containerization platform. It enables developers to package
applications into containers—standardized executable components combining application
source code with the operating system (OS) libraries and dependencies required to run
that code in any environment.

Docker is an OS virtualized software platform that allows IT organizations to easily create,
deploy, and run applications in Docker containers, which have all the dependencies within
them.

Features of Dockers:
1. Faster and Eaasier configuration
2. Increase in productivity
3. Application isolation
4. Swarm : Is a clustering and scheduling tool for Docker containers.It uses Docker API at Frontend which helps us to use various tools to control it. It is self organizing group of engines that enables pluggable backends. 
5. Services : Services is a list of tasks that specifies the state of a container inside a cluster.
6. Routing Mesh : It routes the incoming requests for published ports on available nodes to an active container.

Why we need Docker:
1. Portability
2. Performance
3. Scalable and Cost effective

What is Virtualization
Virtualization is the technique of importing a guest OS on top of a host OS. This was a revelation at the beginning because it allowed developers to run multiple OS in different virtual machines all running on the same host. This eliminated the need for extra hardware resource.
Advantages of Virtual Machines or Virtualization are:
1. Multiple OS can run on the same machine.
2. Maintenance and Recovery were easy in case of failure condition.
3. Total cost of ownership was also less due to the reduced need for infrastructure.

Disadvantages of virtualization:
Running multiple VM leads to unstable performance.
Hypervisors are not efficient as host systems.
Boot up process is long and takes time.
Drawbacks leads to Containerization.

What is Containerization?
Containerization is the technique of bringing virtualization to the OS level.While virtualization brings abstraction to the hardware, containerization brings abstraction to the OS. Similar to virtualization.

Advantages Containerization:
1.Containers on the same OS kernel are lighter and smaller.
2.Better resource utilization compared to VMs.
3.Boot up process is short and takes few seconds.

Difference b/w Virtualization and Containerization
Virtualization:
1. Virtualizes hardware resources
2. Takes more time for Booting.
3. Each VM runs in its own OS.
4. Requires more Memory.
5. Requires complete OS installation for every VM
6. It is not portable.

Containerization:
1. Virtualizes only OS resources.
2. Takes less time for booting.
3. All containers share the host OS.
4. requires less memory.
5. Installs the containert only on a host OS.
6. It is very portable. We can build, ship and run anywhere.

Docker Architecture:

