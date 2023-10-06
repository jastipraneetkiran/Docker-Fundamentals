# What is a Containers?
Container are nothing more than a process or A group of processes running in isolation.


 * A group of processes run in isolation
   - All process Must be able to run on the shared kernel


these process are running in the shared kernel and the isolation is provided by a kernel feature called linux "namespaces".
So linux namespaces give group of running processes an isolated view of resources of that kernel.
Ex - the PID give the isolated view of namespaces , the USER namespace give the isolated view of user and group ID's


 * Each Container has its ows set of "namespaces" (isolated view)
   - PID : process IDs
   - USER : user and group IDs
   - UTS : hostname and domain name
   - NS : mount points
   - NET : Network devices, stacks,ports
   - IPC : inter-process communication,message queues

Another feture of the kernel control groups limit and moniter resources of the containers 
 * cgroups : controls limits and monitoring of resources

## VM vs Contaniner
![image](https://github.com/jastipraneetkiran/Docker-Fundamentals/assets/40835644/8a4845f2-880e-40c7-817c-b9f606d6f4fa)


