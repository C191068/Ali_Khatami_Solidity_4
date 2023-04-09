
## Ali_Khatami_Solidity_4
### Creating our first wallet at Metamask
Metamask is a digital wallet that allows you to securely store, manage, and use cryptocurrencies like Ethereum, on your computer or mobile device. It is an extension for web browsers like Google Chrome or Mozilla Firefox that acts as a bridge between the internet and blockchain networks. Metamask makes it easy for users to interact with decentralized applications, also known as dApps, by providing a user-friendly interface for managing cryptocurrency transactions. With Metamask, users can send and receive cryptocurrency, access decentralized exchanges, and participate in blockchain-based applications without needing to have technical knowledge of blockchain technology.<br>

![bw1](https://user-images.githubusercontent.com/89090776/229453645-ec99c901-f57c-4a21-be9c-6eb9d8607b4e.jpg)
Figure1: We will click the above link

![bw2](https://user-images.githubusercontent.com/89090776/229454593-b1830afd-f8a9-41fa-a236-1c05a0db2350.jpg)
Figure2:Then we will click on ```Create a new Wallet``` button
![bw3](https://user-images.githubusercontent.com/89090776/229454846-b115ef17-c8c5-4b49-87d5-3e61e4a0ab22.jpg)
Figure3: Then we will click on ```I Agree``` button
![bw4](https://user-images.githubusercontent.com/89090776/229455313-a630407e-2ac5-498d-a38d-c39a8e2d0a52.jpg)
Figure4: The we will need create a password and click on ```Create new wallet``` button
![bw5](https://user-images.githubusercontent.com/89090776/229455931-7660dd94-21c8-4456-b1a4-a8cb7e2a11b6.jpg)
Figure5:Then we will click on ```Secure my wallet(recommended)``` button
![bw6](https://user-images.githubusercontent.com/89090776/229456374-feb28808-e1c6-4152-9b3d-3c3b3aba2337.jpg)
Figure6:Here in the above figure we will click on ```Reveal secret recovery phrase``` button and keep those 12 secret word safe to us and shall not reveal to anyone
![bw7](https://user-images.githubusercontent.com/89090776/229457301-2bc54fff-be45-41cf-886b-787e43f7807b.jpg)
Figure7:Here we are notified that our wallet is created successfully
![bw8](https://user-images.githubusercontent.com/89090776/229457967-29acda06-f9ef-4998-bd85-7cab8b9fea8a.jpg)
Figure8: here we can see that our wallert contains 0 ether
![bw9](https://user-images.githubusercontent.com/89090776/229462131-d5515ebe-52cb-4f4b-b64b-6297bd0d0de3.jpg)
Figure9: here we have to click ```Show/Hide test networks```
![bw10](https://user-images.githubusercontent.com/89090776/229462711-7fb9915c-cf4e-45ea-877a-7da2e61e2030.jpg)
Figure10:Then an ```Advanced``` section will appear and switch to ```On``` the ```Show test networks``` section
![bw11](https://user-images.githubusercontent.com/89090776/229463691-a0b6395e-48ba-45ae-9ead-2d21b955171c.jpg)
Figure11: then fake test networks will appear and we will select ```Sepolia test network```

<br><br>
### Deploying our First Contract
Here we will deploy our contract ```akrkSimplestorage``` to a real network.

![bl5](https://user-images.githubusercontent.com/89090776/227702198-845d3473-de44-4e26-b19a-0ea363ccec88.jpg)
Figure1:Here we gonna change the ```environment``` of the ```Deploy and Run transcation tab``` to ```Injected Provider-Metamask```<br>

![bl6](https://user-images.githubusercontent.com/89090776/227702229-ad7557e6-d41f-4807-8c97-88b39a94e488.jpg)
Figure2:Then we will pick up our metamask account and select ```Next```<br>
![bl7](https://user-images.githubusercontent.com/89090776/227702411-2a1e3a59-be41-4262-8608-0c9c64bcc414.jpg)
Figure3: Then we will click ```Connect``` button <br>
![bx1](https://user-images.githubusercontent.com/89090776/227889927-e99e9214-430c-4f8c-be36-b95ed407fed4.jpg)<br>
Figure4:  In the above figure you can see my account is running at ```sepolia test network```<br>
![bx2](https://user-images.githubusercontent.com/89090776/227892451-3f2e9bfd-ffc4-446b-a1e2-d121db18e2e6.jpg)
Figure5: Here in the above figure we can see when we click the ```Deploy``` button the ```metamask``` window pops up and ask us whethet we want to deploy this contract or not<br>
We can also all payment information for  transaction for deploying this contract but as we are on ```sepolia test network``` it is a fake ethereum
![bx3](https://user-images.githubusercontent.com/89090776/227894829-1d1c1623-e7d6-4481-9e6a-e04fea601f6a.jpg)
Figure6: here in the above figure we can see when we click the ```Data``` option of this window we see the massive ```HEX DATA``` which is actually the ```contract akrkSimplestorage``` we have created<br>

![bw13](https://user-images.githubusercontent.com/89090776/229464319-9008027b-ee8b-4009-865f-692303468a5c.jpg)
Figure18: As our wallet account do not have enough ```SepoliaETH``` to pay for transaction we need to request ```SepoliaETH``` from this link 
https://faucets.chain.link/

![bw14](https://user-images.githubusercontent.com/89090776/229464804-dee7350f-21e8-4a99-8988-c8db1ee5625b.jpg)
Figure19: From ```Connect your Wallet``` we will select ```Metamask``` in this way
![bw15](https://user-images.githubusercontent.com/89090776/229465126-383ab8d1-a084-44f7-b16c-dd44d4f52652.jpg)
Figure20: It will get connect with our Metamask wallet account
![bw18](https://user-images.githubusercontent.com/89090776/229466382-9362d06b-be89-40cb-9f8f-01a88f8a8dca.jpg)
figure21: here the priamry condition is to request test ether is ```Login via Twitter```  and click the ```Send Request``` button
![bw21](https://user-images.githubusercontent.com/89090776/229466953-c7ed29fd-d0cf-4011-bdf6-4636c6d557cc.jpg)
Figure22: here in the figure we can see that request have been completed successfully
![bw22](https://user-images.githubusercontent.com/89090776/229467543-a3810d9d-a8ab-43fe-b014-5124741475b0.jpg)
Figure23: here we have got ```0.1 SepoliaEth``` in our account
![bw23](https://user-images.githubusercontent.com/89090776/229468079-02bceece-5fb5-4319-a4be-3126cc64de83.jpg)
![bw24](https://user-images.githubusercontent.com/89090776/229468113-1ac8aee8-c3d4-4850-ad7f-85d6dfda3399.jpg)
![bw25](https://user-images.githubusercontent.com/89090776/229468161-d0591b5a-1d67-40ca-9c18-cae95ed81e1a.jpg)
![bw26](https://user-images.githubusercontent.com/89090776/229468205-2f07b095-1a02-419f-bc7e-865a38eab0d4.jpg)
![bw27](https://user-images.githubusercontent.com/89090776/229468247-f5da8813-b5c1-4d7c-9bc0-b3aa5f3e2d09.jpg)

![vs](https://user-images.githubusercontent.com/89090776/230765191-033fe89d-9eb9-42cd-aefa-9b5ce6689528.jpg)

















