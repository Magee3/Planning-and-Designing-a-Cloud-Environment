# Planning and Designing a Cloud-Environment

## Objective

We figure out how you will estimate cloud virtual machine operations expenses for an organization. We will be using
online price calculators from Microsoft Azure, Amazon AWS and Google Cloud Platform. This is a key business requirement as
well as it contributes to capacity planning.

### Stage 1: Azure Virtual Machine Pricing Calculator

We will first work with Microsoft Azure's cloud services. The pricing calculator is below.

[https://azure](https://azure.microsoft.com/en-us/pricing/calculator/)

![1](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/1ebc6829-9924-4176-8626-f3228dd83b2a)

Next select virtual machines, this is what we will be using for our cloud service.

![2](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/014cf978-1497-47c9-93e8-76c3aed9e2ec)

If you scroll down you can see the default package is $137.24 well at the time that I post this write up.

![1 5](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/b20d4b14-b54f-4664-9fa2-df59a3247504)

In Azure there are two operating systems you can use and that is Windows or Linux.

![4](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/531cd5b6-56de-45d3-8a03-69296ff96560)

With that there are various types of the operating system you can choose from.
![5](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/2a2cd4ad-09b5-49bf-aa6b-e508b832f856)

![6](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/e3728c72-ef3e-4ad2-a275-7cb4a2b5db8d)

Now we will select what type of Instance our machine will have. A instance is the portion of the computer we our renting out so to say. We are inputing how powerful and how much memory the virtual machine
will have. We selected a Linux Machine running RHEL using an A2 Instance.

![7](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/962dd5ad-69d6-4a39-a548-dab10773fc76)

The price comes down to $101.47 a month for this Virtual Machine. It is cheaped than the Windows default VM because Linux is an Open Source operating system, so it's free!

![8](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/e771a231-65a3-4bb8-a42e-182096422bc7)

Sadly this is not the final price for the VM, Azure requires you to purchase a support package. 

![9](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/acf49a45-c48d-4782-b2cd-c6a5cf2933bb)

We will try standard. As you can see an extra $100 dollars a month has been added to this package. Leaving it to $237.24 a month or $2,846.88/yr for one machine. A lot more expensive then building your own
but, if your goal is to move into cloud, paperless, always has access type of business model then be my guest. 
![10](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/5cecefad-328e-4cbc-a779-6cbc8ea4d146)

![11](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/c74ea5c3-70d3-4980-bc36-beec3802c692)

Lastly you can save your quote for later by clicking the Export button below.
![12](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/b7b08e5c-a365-40e2-992d-9c2eec5693ac)


### Stage 2: AWS Virtual Machine Pricing Calculator

In your browser head to the AWS website and click "Create estimate"

https://calculator.aws/#/

![13](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/5396b478-cc6e-4b6a-ad73-688765c51a66)

Under Find Service type "EC2" and below click "Configure" under te Amazon EC2 tab. EC2 is your genral virtual machine option.

![14](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/4160e2e3-e27a-4f57-a6a3-1c79d7eb136b)

Under Desciption I wrote "VM-estimate" but you can write whatever you want. Pay attention below is the default monthly cost for this barebones EC2.

![15](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/3786928b-3fea-4e2a-a4c9-0038d4c54215)

I added an instance type "m6g.large" and left storage settings to default.

![16](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/5b67914a-e7ba-4f43-b6ef-f82458df7542)

When you are done changing what you need in AWS scroll down and click save and add service. 

![17](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/08ad6626-6ba2-4012-8821-e26190acfc99)

Click on "My Estimate"

![18](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/10978e13-c120-4f24-bcc5-b8aa3d7ee5e1)

And hit "Export" to save the quote

![19](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/cbc8da5a-9325-4a38-bf97-7958d9ad2ca5)

![20](https://github.com/Magee3/Planning-and-Designing-a-Cloud-Environment/assets/134301259/594018ae-8fa9-44b7-84ca-ff6ed954717b)


### Stage 3: GCP Virtual Machine Pricing
