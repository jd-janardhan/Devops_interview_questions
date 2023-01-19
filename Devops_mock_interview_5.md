Git
------
1. what is the importance .git directory?
Ans: The .git directory holds the information about the repository and objects that are commited into 
the repository. when we issue git init inside the empty directory, the git creates the .git directory 
initializing the empty repository with the below directory structure inside it.
.git (directory)
|-hooks
|-info
|-objects
|-logs
|-refs
--------
|-config
|-index
|-HEAD


2. what are the branches, diff between remote and local branches?
Ans:
In Git, a branch is a way to move development forward by creating a copy of the entire project and working on that copy. This allows multiple people to work on different features or bug fixes at the same time, without affecting the main branch of the project.
A local branch is a branch that exists only on your local machine. You can create, delete and modify local branches as you wish. You can also push local branches to a remote repository, where they can be shared with other people.

A remote branch is a branch that exists on a remote repository, such as GitHub. Remote branches are typically created by other people, and you can't make changes to them directly. However, you can create a local copy (known as a remote-tracking branch) and make changes to it, then push those changes back to the remote repository.
3. what Branching strategy that you are familier with? 


7. What PR (Pull request) is? whats the importance of PR?

Unix & Shell scripting 
-----------
5. what is command for checking the running process? how to get PID of process?
6. Command to get whether certain port is listing or not?
7. How to indentify the number of params that has been sent to shell script?
8. command to delete empty line in a file?

Helm
---
9. what is the need for helm charts?
10. what version helm your using? what difference between helm 2 & helm3?

Kubernetes
-----
11. What is Pod?
12. Creation of cluster for k8s, can we have multi master and multi nodes cluster?
13. On what basis the pod will be deployed on a specific node?
14. Can we deploy pod on master node?
15. What are steps that you might take to make one node into maintance?
16. In the kubeadm setup the control plane components are created as pods, where the defination those pods will be defined?

Docker
-----
17. How to configure docker private registry?
18. Types of network in docker? if you dont specify network to deploy on which network the conatiner will be created?
19. Explain a sample dockerfile that you have used in your project?
20. Can we launch linux conatiners windows and viceversa?

Maven
----
21. what is multi module project?
22. what is the importance of dependency managment?
23. what are the settings that you need to do for mvn deploy ( to push artifcats to repository )?
24. mvn version that you have used?

Jenkin
---
25. what is the need of CICD tools?
26. What type of Jenkinsfile you have worked on?
27. In master slave setup if I want run job on specific node is is possible?
28. what is the importance of Jenkins secrets?

Monitoring
----
29. If given a chance to setup monitoring solution for project what are tools that you use?
