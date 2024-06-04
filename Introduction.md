<h1 align="middle">Introduction to Elastic Compute Cloud</h1>  

----
### What is an EC2 instance ?

<p> <i>Elastic Compute Cloud (EC2)</i> in AWS is like renting a computer in the cloud. Imagine you need a computer to run your software or website, but you don't want to buy one. With EC2, you can just "rent" one from Amazon's huge collection of computers. You can choose how powerful you want it to be, how much memory it has, and other stuff like that. Plus, you can easily change or cancel your rental whenever you need to. It's a flexible and convenient way to use computing power without owning physical hardware. </p>

### Components of an ec2 instance

1. <u>Instance Type</u>: This is like choosing the size and power of your rented computer. You can pick from various options based on your needs, like how much CPU, memory, and storage you require.
<br>
2. <u>AMI (Amazon Machine Image)</u>: It's like choosing the operating system and software that you want pre-installed on your rented computer. You can select from a variety of pre-configured images provided by AWS or create your own.
<br>
3. <u>Instance Storage (EBS or Instance Store) </u>: This is where your data is stored. You can choose between EBS (Elastic Block Store), which is like a regular hard drive that persists even if your instance is turned off, or Instance Store, which is temporary storage that disappears when your instance is stopped or terminated.
<br>
4. <u>Security Groups</u>: These are like virtual firewalls that control the traffic to and from your EC2 instance. You can specify which protocols, ports, and IP ranges are allowed to communicate with your instance.
<br>
5. <u>Key Pairs</u>: When you launch an EC2 instance, you need to specify a key pair, which consists of a public key and a private key. This allows you to securely connect to your instance using SSH (for Linux instances) or RDP (for Windows instances).
