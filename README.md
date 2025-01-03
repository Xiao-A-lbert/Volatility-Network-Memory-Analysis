# Volatility: Network Memory Analysis# Volatility: Memory Analysis

<h2>Description</h2>
In this Digital Forensics task, I used volatility to run a netstat scan against a windows 10 memory dump to enrumerate a suspicious svchost network connection.   

<h2>Languages and Utilities Used</h2>

- <b>python3</b>
- <b>volatility</b>

<h2>Environments Used </h2>

- <b>Ubuntu</b> 

<br />
<br />
Running volatility windows.netstat against the win 10 memory dump. 

![1) vol netstat on win10 memdump](https://github.com/user-attachments/assets/410e71e2-5f16-4043-8a2f-70a820dd06a8)

<br />
<br />
Checking the smartscreen executable shows it is from Microsoft. 

![2) checking whois to make sure it is from microsoft](https://github.com/user-attachments/assets/f84460d8-f0b1-40e4-9c2f-e4109b0b081d)

<br />
<br />  
Noticing a suspicious foreign port for svchost outside of baseline 443/80. 

![3) suspicious svchost different form baseline port](https://github.com/user-attachments/assets/c3dbec25-7cea-4b2b-9d88-10c04b6e58f5)

<br />
<br />
