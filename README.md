<p align="center">
<img src="https://i.pcmag.com/imagery/reviews/066pfhdQmzHcmyEMaZtToWq-103.fit_scale.size_1028x578.v1691430001.png" alt="ProtonVPN logo"/>
</p>

<h1>ProtonVPN - Implementation and Installation</h1>
This tutorial outlines the installation and use of a vpn known as Proton VPN.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
  

<h2>Installation Steps</h2>

<br/>  


**Step 1: Create the Virtual Machine within Microsoft Azure**
- Create a resource group called "DumbleDore" (You can name it Anything).
- Create a Virtual Machine (VM) called "Hagrid".
- Use Windows 10 Pro, version 22H2 and Standard_D4s_v3 - 2cpus, 16 GiB memory.
- Make sure to choose a region you don't live in while creating your Resource Group.
- Keep track of username (HarryPotter) and password (Anything) you're creating for you VM Windows 10.
### NOTE: If you Don't know how to create Virtual Machine click [HERE](https://www.youtube.com/@cyber_singh)

<br/>

<p>

  **_Creating rersource group and selecting your region_**
  
<img width="812" alt="Screenshot 2023-09-21 174042" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/b78cd0e3-abe4-4a6c-ac2c-c99427b2a904"></p>

<br/>

**_These are the settings you can use to create your VM. Using the same region as Resource group._**

<img width="812" alt="Screenshot 2023-09-21 174042" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/f3e10aa5-2615-4bf4-8ca6-e2435ee7ffbf"></p>


<p>
<img width="691" alt="Screenshot 2023-09-21 174453" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/5fda8833-a7e9-44ef-a945-d6af0e2be6c9"></p>

**_Make sure to checkmark the bottom part about licensing so you don't run into any issues._**

<br/>

****

<p></p>

<br/>


**Step 2: Find current IP Address**


- Take not of the Public IPv4 Address of your actual Computer @ [WhatIsMyIPAddress.com](https://whatismyipaddress.com/)

<br/>

<p>
<img width="835" alt="Screenshot 2023-09-21 175422" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/86569dfc-bc47-4b4b-9b80-82166603c3f2">

</p>

**_This is one way to find your current IP Address._**

<br/>

****
</p>

<br/>


**Step 3: Log into the VM via Window Remote Connection**
- Copy the Public IP Address from the VM (Virutal Machines > "Hagrid" > copy Public IP address).
- Then open Window Remote Connection from your Computer and paste the copied IP address and click connect.
- Log in, using your VMs Windows 10 username(HarryPotter) and password(Anything)

<br/>

<p>
<img width="835" alt="Screenshot 2023-09-21 180022" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/d27dd362-08e5-484a-8348-ff57c1197e5f">
</p>



<p>
<img width="778" alt="Screenshot 2023-09-21 180601" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/91c32d49-d126-476b-9dab-7117cdb77ad9">
</p>


<img width="835" alt="Screenshot 2023-09-21 180022" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/5fbf3e65-c939-4481-9e57-9e33e401a4d5">

<p>

**_If you see another user in user's section click More choices and then choose to Use a different account.._**

****
</p>

<br/>

**Step 4: Find IP Address of the Virtual Machine**
- Open a web broswer inside your VM and check your IP adress @ [WhatIsMyIPAddress.com](https://whatismyipaddress.com/).
- You should see an IP Address somewhere from France as we select our region France for our VM.

**_NOTE: If you search anything on your VM browser it will gave you result as you are actually in France within a Local language._**
  
<br/>

<p>
<img width="797" alt="Screenshot 2023-09-21 181005" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/11933a42-884b-4a23-9c61-e427a2e08f8e">
</p>

<img width="797" alt="Screenshot 2023-09-21 181005" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/61484e6d-a333-4552-8e42-2a89d6da267f">

****

<br/>

**Step 5: Install Proton VPN**
- Create a new account within Proton VPN at your actual computer @ [FREE PROTON VPN](https://protonvpn.com/free-vpn/download)
- Now copy the URL link and paste it inside your VM.
- Download and install Proton VPN for Windows inside your VM.

**_Note: Inside your VM you are going to get results in French, So that's why you are creating account on actual computer and then downloading VPN inside VM._**

<br/>

<p>
<img width="935" alt="Screenshot 2023-09-21 181534" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/36a6a204-c278-48ff-b03d-647bbb8daee1">
</p>

**_When you're installing Proton VPN, you'll need to accept all of their terms._**

****
</p>

<br/>


**Step 6: Connect to Proton VPN**
- Log In with your account credentials.
- Once inside of Proton VPN make sure to click "Quick Connect" or check under for "free connections".
- After successful connection you should have another new IP address assigned.
- Again check your IP address @ [WhatIsMyIPAddress.com](https://whatismyipaddress.com/).

<br/>

<p>
<img width="500" alt="Screenshot 2023-09-21 182419" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/cd8d6b0b-1378-4d92-8ea3-3f89e0b15deb">


</p>

<p>
<img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/a9381358-bbd3-4c71-8fe4-d983f9131684">

</p>


**_Voila! You're now connected to Japan's Server_** (Try to play with change server option shown in pic. above)

<br/>

<p>


**_Now Check your IP adress to confirm the connection_**

<img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/e7634fd2-5bce-4699-a0aa-1c7ae7610c16">

</p>



<br/>


<p>

**_Google something to see VPN's magical work_**.

<img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/b4dcdf9a-c4c4-4fb7-b6c5-79b11548951b">


</p>


<br/>


<p>

****

  
**_Now hit that change server option I mentioned earlier_**.

**_NOTE: You already setup your Proton VPN and Established your connection these step are for further exploration_**

<img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/1656adaf-511a-43bd-8294-a4e9964a2e38">

</p>


<p>

  
**_There you go now you're in Netherland (country could be different for you)_**

<br/>

</p>



<p>

**_Check your IP address once again for confirmation_**

  
<img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/b29fd35f-8284-432e-8407-8c856eb68bf6">

</p>


<br/>

****

<p>

***_Uses of VPN (Virtual Private Network)_***

<p>


1. **Enhanced Security**: VPNs encrypt data, providing a secure way to transmit sensitive information over public networks.

2. **Remote Access**: Employees can securely access corporate networks and resources from anywhere, fostering remote work.

3. **Geo-Spoofing**: VPNs allow users to bypass geo-restrictions and access content from different regions.

4. **Anonymity and Privacy**: VPNs mask the user's IP address, enhancing online privacy and anonymity.

5. **Cost Savings**: Corporations can reduce costs by using VPNs to establish secure connections over the internet instead of dedicated lines.

6. **Data Protection**: VPNs safeguard sensitive corporate data, ensuring it remains confidential during transmission.


</p>

</p>

****


<h1>WOW! We make to the End, YET!</h1>

<p>


**You got any quention? Ping me on [LinkedIn](https://www.linkedin.com/in/cybersingh)**
  
**You still confuse about VPNs see this [Video](https://www.youtube.com/@cyber_singh)**


</p>

****







