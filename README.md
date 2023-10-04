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
![kWCU57Zuc3](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/30f75e75-b611-4e23-9b48-16dd2d7d5c8f)
5. After signing up/loging in with a micrsoft account it should bring you to this page.
![opera_QDewBXjUAj](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/042ec436-a97b-48c6-8787-5f49e57832ff)
6. You will select start free trail.
![lAKUgksaPG](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/afdf3850-63bf-45fd-b933-c2052c5eca7a)
7. It will bring you to a new page were you will need to select start free. (In some cases you will need to log in agian.)
![lfyaNqG1lW](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/6c364875-b9a6-4bdc-b94f-399dcfb59a28)
8. When you are done you can head back to the mian Azure page. (https://portal.azure.com/#home)
![opera_veiUYVV8ry](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/14d11677-23d0-4d0e-adc6-8308a363a36c)
9. When you are at the main page you can either select Virtual machines or type Vm/ VIrtual machines into the search bar.
   THere are other ways we could do this, like making a resource group before hand but I perfer it this way. 
![E7CENPqooV](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/c0bffa06-79a5-46f8-94b1-51696939d8dd)
10. When you select or type Virtual machines it will bring you to this page. 
![opera_5fWk4CxuTy](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/5c4ac83e-bf6a-41f5-b063-0bb96e73b978)
11. you will select create there are two creates, but it is okay as along as you slect "Azure Virtual Machine"
![BbChRJh8Z7](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/8827cd3b-e3af-4a3b-a559-d83207eb86f1)   
![I8iEmbgmMf](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/6c514024-79e8-4996-afd6-9a6f23fdedc9)
12. After selecting "Azure Virtual Machine" it will bring you to this screen.
![opera_byfimC3dns](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/1dff0952-86dd-4e33-aec1-24fe7825e36e)
13. I know this can look like alot so we will take this one at a time. you will see "Azure subscription 1" we wont be messing with this right now,
   but this can be usefull when dealing with diffrent teams and budgets. We will see "Resource group" we will hit create new and type in a name,
   for this i will be using "Testing" you can use anything you would like to.
![OZGqnGfw9l](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/555253cf-fa2b-4cfa-9a57-fcc8d4d981dc)
13. Then you will select testing and it will appear as "(New) Testing".
![opera_VB0BzZVgNq](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/bbc0583e-4bd7-4026-9f67-ad5b07693a55)
14.  Now we will focus on "Instance Details", this will be naming the device, what region you want, Availability options, and Availability zones.
    Naming the Device is simple, it is just what we want to call it and what other devices will see us as. Region is also an easy one, this is important if we need it somewhere specific or only contracted to work in one region, 
    and if a customer needs it somewhere specific. Availability options help if you want your resources shared at different locations in case something was to go down i.e Fires, blackouts. Availability zones are optional if you want to specify
    what availability zone to deploy your Virtual Machine.
    I will be naming my Vm "Test"
![amUwJ79SKV](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/adadce75-4802-4ccd-bf25-654a3165bc54) ![tioO29zQt6](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/41af45a9-b070-46f4-acd3-10920100604e)
15. Now you will see security types you can mess with if you would like standard, trusted launch, or confidential, I will be using trusted launch.
    Next is choosing our OS or operating system. They have a lot of options and different versions like:Windows10 pro/ Windows 11 pro/ ubuntu/Windows servers. I will be selecting windows 11 pro.
    Next is Vm architecture which we will not have to mess with now but is useful when using certain programs. Eviction type and policy we will not mess with right now. 
    ![udg0ElOPcg](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/1f63ac70-7f25-4cb7-8bf8-307d7c3b46a7)![opera_IyL0TOg3uT](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/c41d09f6-39c5-4ffc-b565-497fe2fde23d)
16. Next we will see "Size" This just means how fast it will be. For desktop work I don't see going over 2 vcpu and 16 gbs being needed. ( If you are on the free trail you have a limit of how much you can use,
     you can double check in azure but i believe it is 8 vcpus and 32gb of ram. I view this as two vms 4 vcpus and 16gbs ram) I will be using 2vcpus and 16 ram.
     Next is naming the Admin account I am naming mine Testt (you can name yours anything) and enter a password 
    ![vnTThtMNLD](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/cf888429-bb8f-4745-a9f6-f54372eb542d)
17. We will be sure to "allow selected ports" and "RDP (3389). We will also select saying we confirm we have a windows 10/11 License with multi tenant hosting. We can change Disk,Networking,Management,Monitoring,Advanced,
    and Tags but we do not need to mess with thtses right now. I will select Review and Create.
![4ps2sO5Dw8](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/ac777f39-861b-4e2e-91c8-a21b78669d67)
18. Here we can see how much it is an hour and when we scroll down it will show us our settings and what we selected. Now hit "Create"
   ![opera_gZQzsSHKyu](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/a58c968a-a3d7-4e83-a6db-77070bde758c)  ![BiizVgBoeD](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/1b9127a9-9ca9-4d0b-ba26-3b7c71bc2149)
19. It will now start to Deploy, It may take it a bit but when it is done head back to Virtual machine in Azure. (by typing Vm in the search bar.)
    Y0u should now be able to see it, it might still be saying it is creating but you can hit the name of your Vm. (it should be blue and mine is called test so i will select it.)
    ![49KFVhTeac](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/0bd7683a-30da-4de8-a5e4-45a76d635ecd)
20. This is what you will see it will show us everything from ip, where it is and everything between our next step is to Remote into it.(Note: This is for Windows not MacOs)
    We will open "Remote Desktop Connection". Hit your start button and search "Remote Desktop Connection".
    ![opera_wfxlwa763o](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/c9cc66dd-4360-4397-8599-7c3ed19c2633)
22. When you open "Remote Desktop Connection" It will look like this.
    
    ![mstsc_KBKe34TGhe](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/40d12c91-2953-4992-9293-9900f33c5803)
    
23. Now all you need is the Puplic IP from your Vm and enter it into "Remote Desktop Connection". After that you will need to log into the Admin you made.
    ![SISJxtY6n3](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/e4a3ed96-cb1c-454f-b45b-f4f55cc6cda7) ![n5x0F1w95l](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/22214d3f-95a3-43b5-a95f-99698c57f2a7)
24. Enter your Credentials
        
    ![1dVd6ya4cq](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/28b4b8a5-d5c5-4c32-96ea-4ed119deeec2) ![lUHKQeHpH9](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/48fff35e-2622-49f2-9a27-bf74ae6d35f3)
25. Hit yes
    
    ![8onf5n8zNs](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/6fb453a8-c7b2-44fe-98ae-65c6db16086a)
26. Select Next or change anything you want to, you do not need to say yest to any of thses settings.

![hrh6pCFbxp](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/82ee1661-b42d-4b30-97f3-7f3c7be65fad)

27. Congrats you are now in your Vm and can do anything you would like to. 
    ![mstsc_KBuQeuGYc4](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/79ee733f-feb2-4123-be9b-31ed7051da39)

    Thank you for following this guide and let me know if you are having issues or need help. 
