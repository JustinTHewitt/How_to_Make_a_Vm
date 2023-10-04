# How to make a Vm/w Azure 

There are many ways to make a Virtual machine and many different softwares we could use. I will be using Azure. Azure is cloud computing and lets us do a lot of things. Some examples are: Making a Vm, Managing teams, File transfers, Running tasks, Computing backend calculations, and much more. If you would like to know what a Virtual machine is, [Google actual has a great article about it.](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjXuYHIkdmBAxUknokEHdAuCW0QFnoECBwQAQ&url=https%3A%2F%2Fazure.microsoft.com%2Fen-us%2Fresources%2Fcloud-computing-dictionary%2Fwhat-is-a-virtual-machine&usg=AOvVaw08SeczljyrIzAOlpuWZ-Lr&opi=89978449)

What you will need: A microsoft account and a Credit/Debit card. (if you are doing the free trial it will not charge unless you use 200 credits or 30 days has pass)

1. To get started We are going to go to Their main website.(https://azure.microsoft.com/en-us/)
![Screenshot 2023-10-02 231822](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/6f099b54-1435-44fb-aca2-83b5d6b31ad9)
2. After we had to their main website we will hit get started. 
![Screenshot 2023-10-02 2318222](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/15e73726-9a2e-4b52-86d8-dcb8d17f2fb0)
That will bring us to Pay as you go.
![opera_NBF3f2t5es](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/bd05fb06-1cac-4ed1-81c1-5450fb6026b6)
Pay as you go is pretty forward, it means you will pay for as much as you use. Before you do anything it will let you know how much it would be by hour.
We do need to be careful when using as we could be charged when we are done with projects because we did not delete everything when we were done.
There is an option for a free trial that will give us 200 credits for 30 days so whichever comes first. 

3. Now we will hit get started, again. 
![S5gx6ApjiZ](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/5fab6846-e684-4642-9b9f-dfaab23e8046)
4. That will bring us to a Sign up/Sign.
![kWCU57Zuc3](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/5ea31ab8-d6c9-47a7-9e20-2988370e30e5)
5. After signing up/loging in with a micrsoft account it should bring you to this page. You will select start free trail.
![lfyaNqG1lW](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/badf250f-26fe-4318-aaaa-77335597ce6e)
6. It will bring you to a new page were you will need to select start free. (In some cases you will need to log in agian.)
![lAKUgksaPG](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/0052ab05-c162-4f5d-b8df-ae1a8abe6441)
7. When you are done you can head back to the mian Azure page. (https://portal.azure.com/#home)
![opera_veiUYVV8ry](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/b58c1397-5445-4fcd-9a47-19129efef087)
8. When you are at the main page you can either select Virtual machines or type Vm/ VIrtual machines into the search bar.
   THere are other ways we could do this, like making a resource group before hand but I perfer it this way. 
![E7CENPqooV](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/1edef8d8-ed83-427e-88b0-56a528b89e9d)
9. When you select or type Virtual machines it will bring you to this page. 
![opera_5fWk4CxuTy](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/268d9424-33d1-4159-b025-0ae507de3cf9)
10. you will select create there are two creates, but it is okay as along as you slect "Azure Virtual Machine"
![I8iEmbgmMf](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/27e66d22-4630-4041-ba0c-863b17e2537c)
![BbChRJh8Z7](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/45cd0bb1-5604-494a-93cb-ff75520d12d9)
11. After selecting "Azure Virtual Machine" it will bring you to this screen.
![opera_5fWk4CxuTy](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/32be8236-ebe5-45a7-bd88-40e7df79fc03)
12. Hit create. I know this can look like alot so we will take this one at a time. you will see "Azure subscription 1" we wont be messing with this right now,
   but this can be usefull when dealing with diffrent teams and budgets. We will see "Resource group" we will hit create new and type in a name,
   for this i will be using "Testing" you can use anything you would like to.
![OZGqnGfw9l](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/74367527-e11e-4d21-a303-a9bcf4b0a128)
13. Then you will select testing and it will appear as "(New) Testing".
![opera_VB0BzZVgNq](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/633596af-3d5b-40f5-b4f0-7b01a52a28c1)
14.  Now we will focus on "Instance Details", this will be naming the device, what region you want, Availability options, and Availability zones.
    Naming the Device is simple, it is just what we want to call it and what other devices will see us as. Region is also an easy one, this is important if we need it somewhere specific or only contracted to work in one region, 
    and if a customer needs it somewhere specific. Availability options help if you want your resources shared at different locations in case something was to go down i.e Fires, blackouts. Availability zones are optional if you want to specify
    what availability zone to deploy your Virtual Machine.
    I will be naming my Vm "Test"
![amUwJ79SKV](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/6e20c5cb-9d12-4c74-afaf-0c1d3bafa1f5)![opera_VB0BzZVgNq] 
![tioO29zQt6](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/2b3e5ebc-9678-40f5-a5f2-4b9a02f4c471)
15. Now you will see security types you can mess with if you would like standard, trusted launch, or confidential, I will be using trusted launch.
    Next is choosing our OS or operating system. They have a lot of options and different versions like:Windows10 pro/ Windows 11 pro/ ubuntu/Windows servers. I will be selecting windows 11 pro.
    Next is Vm architecture which we will not have to mess with now but is useful when using certain programs. Eviction type and policy we will not mess with right now. 
  ![udg0ElOPcg](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/671d214d-b631-4f84-8746-60e409bdfa4d)
![opera_IyL0TOg3uT](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/d709a395-c711-4ca9-a06f-89cba86dd499)
16. Next we will see "Size" This just means how fast it will be. For desktop work I don't see going over 2 vcpu and 16 gbs being needed. ( If you are on the free trail you have a limit of how much you can use,
     you can double check in azure but i believe it is 8 vcpus and 32gb of ram. I view this as two vms 4 vcpus and 16gbs ram) I will be using 2vcpus and 16 ram.
     Next is naming the Admin account I am naming mine Testt (you can name yours anything) and enter a password 
   ![vnTThtMNLD](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/dcdd22ad-997b-4eaa-a167-1f1a4c7702f9)
17. We will be sure to "allow selected ports" and "RDP (3389). We will also select saying we confirm we have a windows 10/11 License with multi tenant hosting. We can change Disk,Networking,Management,Monitoring,Advanced,
    and Tags but we do not need to mess with thtses right now. I will select Review and Create.
![4ps2sO5Dw8](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/8d09dc00-2dad-447a-8289-dbd9960bc46b)
18. Here we can see how much it is an hour and when we scroll down it will show us our settings and what we selected. Now hit "Create"
  ![opera_gZQzsSHKyu](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/c88d0909-3c3c-4e82-8cac-d64e25d40e79)![BiizVgBoeD](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/202eb857-2dd7-4cf5-acf7-78272c642e7e)
19. It will now start to Deploy, It may take it a bit but when it is done head back to Virtual machine in Azure. (by typing Vm in the search bar.)
    Y0u should now be able to see it, it might still be saying it is creating but you can hit the name of your Vm. (it should be blue and mine is called test so i will select it.)
    ![opera_UUMIme5FMs](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/aa3bc0d6-1889-46e4-bfaa-28dd3f3b9bb4)
20. This is what you will see it will show us everything from ip, where it is and everything between our next step is to Remote into it.(Note: This is for Windows not MacOs)
    We will open "Remote Desktop Connection". Hit your start button and search "Remote Desktop Connection".
   ![opera_wfxlwa763o](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/9202ba67-adea-422a-bd06-b8e29b8d63b9)

22. When you open "Remote Desktop Connection" It will look like this.
    
  ![mstsc_ZBdrP4CU8H](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/1d554d86-7120-44de-aead-5cd0fe28c30d)
    
23. Now all you need is the Puplic IP from your Vm and enter it into "Remote Desktop Connection". After that you will need to log into the Admin you made.
    ![opera_KUBeg1COlk](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/3f0a0dca-b3fa-45da-a6be-83278f5c20e1)![1dVd6ya4cq](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/a0165a69-c888-45f5-abd5-d32b761b1dd0)
24. Enter your Credentials
        
    ![CredentialUIBroker_gtyCCTSX8S](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/66438062-0eef-4a08-8be2-ed95855aefc0)![CredentialUIBroker_pnJb0kh2ei](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/a5bbba37-9571-4515-b083-c9864c70d028)
25. Hit yes
    
   ![8onf5n8zNs](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/c62dc059-3af3-4624-b305-d04f03b39220)
26. Select Next or change anything you want to, you do not need to say yest to any of thses settings.

![mstsc_mnIOd017HF](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/82df4b27-9dd9-4c60-9e5a-17f9b2d4f12d)

27. Congrats you are now in your Vm and can do anything you would like to. 

    ![mstsc_KBuQeuGYc4](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/f5b8b54f-d549-46f7-aa50-b6b0c860575d)

    Thank you for following this guide and let me know if you are having issues or need help. 
