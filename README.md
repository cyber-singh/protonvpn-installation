<p align="center">
<img src="https://i.pcmag.com/imagery/reviews/066pfhdQmzHcmyEMaZtToWq-103.fit_scale.size_1028x578.v1691430001.png" alt="ProtonVPN logo"/>
</p>

<p>
<h2>ProtonVPN - Implementation and Installation: Safeguarding Your Online Privacy in Azure</h2>

In an increasingly connected world, safeguarding your online privacy and security are paramount.Whether you're a business professional, remote worker, or simply a privacy-conscious individual, this tutorial will walk you through the process of installing and implementing ProtonVPN on your Azure Virtual Machine. By the end, you'll have the knowledge and tools needed to ensure your internet connection remains private and protected while working within the Azure cloud.
</p>

****

<p>
<h2>Why ProtonVPN?</h2>

ProtonVPN is a trusted choice for many, offering robust encryption and a host of features designed to keep your online activities shielded from prying eyes. From enhanced security to seamless remote access and the ability to bypass geo-restrictions, ProtonVPN empowers you to take control of your online privacy.  

<br>

***_Uses of VPN (Virtual Private Network)_***  


1. **Enhanced Security**: VPNs encrypt data, providing a secure way to transmit sensitive information over public networks.

2. **Remote Access**: Employees can securely access corporate networks and resources from anywhere, fostering remote work.

3. **Geo-Spoofing**: VPNs allow users to bypass geo-restrictions and access content from different regions.

4. **Anonymity and Privacy**: VPNs mask the user's IP address, enhancing online privacy and anonymity.

5. **Cost Savings**: Corporations can reduce costs by using VPNs to establish secure connections over the internet instead of dedicated lines.

6. **Data Protection**: VPNs safeguard sensitive corporate data, ensuring it remains confidential during transmission.
</p>

****


<h2>Prerequisites:</h2>

**A Microsoft Azure account:** Before you proceed, make sure you have an active Microsoft Azure account. If you don't have one, you can sign up at **[AZURE PORTAL](https://azure.microsoft.com/).**

</br>

<h2>Environments and Technologies Used</h2>

 - **Microsoft Azure (Virtual Machines/Compute)**
 - **Remote Desktop**
 - **Proton VPN**

</br>

<h2>Operating Systems Used </h2>

- **Windows 10 (21H2)**

****
</br>

<h2>Installation Steps</h2>

<h3>Step 1: Create the Virtual Machine within Microsoft Azure</h3>  

- Create a resource group called **"DumbleDore"** (You can name it Anything).
- Create a Virtual Machine (VM) called **"Hagrid"**.
- Use **Windows 10 Pro**, version 22H2 and Standard_D4s_v3 - 2cpus, 16 GiB memory.
- Make sure to choose a **Region** you don't live in while creating your **Resource Group**.
- Keep track of **Username (HarryPotter)** and **Password (Anything)** you're creating for your VM Windows 10.
  
</p>

</br>

<p>

  -  **_Establishing a resource group and specifying your preferred region_**

     <img width="812" alt="Screenshot 2023-09-21 174042" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/b78cd0e3-abe4-4a6c-ac2c-c99427b2a904"></p>

</br>

 - **_Here are the recommended settings for creating your VM. Ensure to choose the same region as your resource group.._**

   <img width="812" alt="Screenshot 2023-09-21 174042" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/f3e10aa5-2615-4bf4-8ca6-e2435ee7ffbf"></p>
   

   <img width="691" alt="Screenshot 2023-09-21 174453" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/5fda8833-a7e9-44ef-a945-d6af0e2be6c9"></p>
   
 - **_Ensure that you tick the checkbox at the bottom related to licensing to avoid encountering any complications.._**
</p>

****

<p>

<h3>Step 2: Find current IP Address</h3>  

</br>

- **_Take not of the Public IPv4 Address of your actual Computer @ [whatismyipaddress.com](https://whatismyipaddress.com/)_**

  <img width="835" alt="Screenshot 2023-09-21 175422" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/86569dfc-bc47-4b4b-9b80-82166603c3f2">  
  
- **_This is one way to find your current IP Address._**

  </p>

****

<p>
 <h3>Step 3: Log into the VM via Window Remote Connection</h3>  

- Copy the Public **IP Address** from the VM (Virutal Machines > **"Hagrid"** > copy Public IP address).
- Then open **Window Remote Connection** from your Computer and paste the copied IP address and click **Connect**.
- Log in, using your VMs Windows 10 **Username(HarryPotter)** and **password(Anything)**.
  </p>
  
<br/>

<p>
 <img width="835" alt="Screenshot 2023-09-21 180022" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/d27dd362-08e5-484a-8348-ff57c1197e5f">  
 </p>

<p>
 <img width="778" alt="Screenshot 2023-09-21 180601" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/91c32d49-d126-476b-9dab-7117cdb77ad9">  
 </p>

<p>
 <img width="835" alt="Screenshot 2023-09-21 180022" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/5fbf3e65-c939-4481-9e57-9e33e401a4d5">  
 </p>
 

- **_If you see another user in user's section click More choices and then choose to Use a different account.._**

****

<br/>

<h3>Step 4: Find IP Address of the Virtual Machine</h3>  

- Open a web broswer inside your VM and check your **IP adress** @ **[whatismyipaddress.com](https://whatismyipaddress.com/)**
- You should see an IP Address somewhere from **France** as we select our region France for our VM.

**_NOTE: If you search anything on your VM browser it will gave you result as you are actually in France within a Local language._**
  
<br/>

<p>
 <img width="797" alt="Screenshot 2023-09-21 181005" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/11933a42-884b-4a23-9c61-e427a2e08f8e">
 </p>

<p>
  <img width="797" alt="Screenshot 2023-09-21 181005" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/61484e6d-a333-4552-8e42-2a89d6da267f">  
  </p>
  
****

<br/>

<h3>Step 5: Install Proton VPN</h3>  

- Create a new account within **Proton VPN** at your actual computer @ **[FREE PROTON VPN](https://protonvpn.com/free-vpn/download)**
- Now copy the URL link and paste it inside your **VM (Virtual Machine)**.
- **Download** and **install** Proton VPN for Windows inside your VM.

**_Note: Inside your VM you are going to get results in French, So that's why you are creating account on actual computer and then downloading VPN inside VM._**

<br/>

<p>
<img width="935" alt="Screenshot 2023-09-21 181534" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/36a6a204-c278-48ff-b03d-647bbb8daee1">
</p>

 - **_When you're installing Proton VPN, you'll need to accept all of their terms._**

****

<br/>

<h3>Step 6: Connect to Proton VPN</h3>  

- Log In with your **Account Credentials**.
- Once inside of Proton VPN make sure to click **"Quick Connect"** or check under for **"free connections"**.
- After successful connection you should have another new **IP address** assigned.
- Again check your IP address @ **[whatismyipaddress.com](https://whatismyipaddress.com/)**.

<br/>

<p>
 <img width="500" alt="Screenshot 2023-09-21 182419" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/cd8d6b0b-1378-4d92-8ea3-3f89e0b15deb">
 </p>

<p>
 <img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/a9381358-bbd3-4c71-8fe4-d983f9131684">
 </p>


 - **_Voila! You're now connected to Japan's Server_** (Try to play with change server option shown in pic. above)

<br/>

<p>

 - **_Now Check your IP adress to confirm the connection_**

   <img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/e7634fd2-5bce-4699-a0aa-1c7ae7610c16">

</p>

<br/>

<p>

 - **_Google something to see VPN's magical work_**.

   <img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/b4dcdf9a-c4c4-4fb7-b6c5-79b11548951b">
</p>


<br/>


<p>

****

**_NOTE: You already setup your Proton VPN and Established your connection, these step are for further exploration_** 

</br>

 - **_Now hit that change server option I mentioned earlier_**.

   <img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/1656adaf-511a-43bd-8294-a4e9964a2e38">
 
 - **_There you go now you're in Netherland (country could be different for you)_**
 </p>
 
<br/>

<p>
 
 - **_Check your IP address once again for confirmation_**
  
   <img width="500" alt="Screenshot 2023-09-21 182640" src="https://github.com/cyber-singh/protonvpn-installation/assets/149118027/b29fd35f-8284-432e-8407-8c856eb68bf6">
   </p>

<br/>

****

<p>
 
 - **Conclusion: Safeguarding Your Online Privacy with ProtonVPN**

   In this tutorial, you've embarked on a journey to enhance your online privacy and security by implementing ProtonVPN on your Azure Virtual Machine. As our world becomes increasingly connected, the 
   need for robust privacy measures grows more critical by the day. Here, we've explored why ProtonVPN is an excellent choice, how to set it up, and the benefits it offers.
</p>

</br>

<p>
 
 - **_The Significance:_**

   Online privacy and security are essential in today's interconnected world. By mastering ProtonVPN implementation within an Azure environment, you've gained a valuable skill that allows you to:

 - Safeguard sensitive data during transmission.
 - Protect your online activities from prying eyes.
 - Access content from around the world.
 - Enjoy the benefits of remote work with confidence.

</p>

****

<h3>WOW! You make  it to the End, YET!</h3>

<p>


 - **You got any quention? Ping me on [LinkedIn](https://www.linkedin.com/in/cybersingh)**
  
 </p>

****







