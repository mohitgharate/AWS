# EC2 (Elastic compute cloud)
***

Elastic Compute Cloud, or EC2, is the central part of Amazon Cloud Services, a cloud computing platform that allows users to rent virtual servers on which they can run their own applications.

 ![Image](server.svg)

Traditionally, to set up a server for your company, you would be responsible for :

```
> Cost of the server
> Configuration of the server
> Distribution of traffic
> Allocation of resources
> Privacy and security
```

When you use EC2, Amazon provides you with its service based on the “cloud computing model”. You can borrow a chunk of your desired size from their data centers on a “pay as you go” basis.




## How to create instance EC2 in AWS :-
***

EC2 is a remote machine i.e. virtual machine and in EC2 we can create it as per our requirement.

*so lets see the steps ->*

**1) Step-1 :** 

Here choose the OS for an EC2 instance as per the requirement 


![Image](step1.png)

**2) Step-2 :**

Here you select the type of instance as per the requirement (CPU, RAM)

![Image](step2.png)

**3) Step-3 :**

Configure the instance to suit your requirements. You can launch multiple instances from the same AMI.


![Image](step3.png)

**4) Step-4** :

Here you can attach additional EBS volume/instance volume to your instance.
In AWS storage is refered as *VOLUME*.


![Image](step4.png)

**5) Step-5 :**

A tag consists of a case-sensitive key-value pair. A copy of a tag can be applied to volumes, instances or both.


![Image](step5.png)

**6) Step-6 :** 

Here you can add security group to allow specific traffic to reach your instance.


![Image](step6.png)

**7) Step-7 :**

Please review your instance launch details. You can go back to edit changes for each section.


![Image](step7.png)

After that click on ***Launch*** and now you are ready with your instance. You get the interface of launched instance. 

## Advantages of EC2 :-
***

```
1. You don’t have to go through the hassle of managing your server(s).
2. Scalability i.e.You can shrink and expand the capacity of your instance whenever you want.
3. You can commit as many EC2 instances as you require.
4. Amazon provides you with flexible cloud hosting services like choosing the OS, memory and CPU configuration.
5. reliable and secure.
```

