# How to make a Vm/w Azure 

There are many ways to make a Virtural machine and many diffrent softwares we could use. I will be using Azure, Azure is a cloud computing and lets us do alot of things
some examples are: Makeing a Vm, Managing teams, File transfers, Running tasks, Computing backend calculations, and much more.
If you would like to know what a Virtual machine is, [Google actual has a great article about it.](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjXuYHIkdmBAxUknokEHdAuCW0QFnoECBwQAQ&url=https%3A%2F%2Fazure.microsoft.com%2Fen-us%2Fresources%2Fcloud-computing-dictionary%2Fwhat-is-a-virtual-machine&usg=AOvVaw08SeczljyrIzAOlpuWZ-Lr&opi=89978449)

What you will need: A microsoft account and a Credit/Debit card. (if you are doing the free trail it will not charge unless you use 200 credits or 30 days has pass)

1. To get started We are going to go to Their main website.(https://azure.microsoft.com/en-us/)
![Screenshot 2023-10-02 231822](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/a892f6fc-4957-43ae-8c7c-5c91fffb139a)
2. After we had to their main website we will hit get started. 
![Screenshot 2023-10-02 2318222](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/027db126-bc0e-4abc-a816-7e1bfdd67d4f)
That will bring us to Pay as you go.
![opera_NBF3f2t5es](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/20d11388-10a7-46fe-844c-da5ffafdf8b1)
Pay as you go is pretty forward, it means you will pay for as much as you use. Before you do anything it will let you know how much it would be by hour.
We do need to be careful when using as we could be charged when we are done with projects because we did not delete everything when we were done.
There is an option for a free trial that will give us 200 credits for 30 days so whichever comes first. 

3. Now we will hit get started, again. 
![S5gx6ApjiZ](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/45c3581c-f8db-44b4-8d2f-41f408b25c48)
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
15. Now you will see security type you can mess with these if you would like standrard, trusted launch, or confidentional, I will be using trusted launch.
    Next is choosing our os or operating system they have alot of options and diffrent versions like:Windows10 pro/ Windows 11 pro/ ubuntu/Windows servers. I will be selecting windows 11 pro.
    Next is Vm architecture wich we will not have to mess with now but is usefull when using certian porgrams. Eviction type and policy we will not mess with right now. 
    ![udg0ElOPcg](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/1f63ac70-7f25-4cb7-8bf8-307d7c3b46a7)![opera_IyL0TOg3uT](https://github.com/JustinTHewitt/How_to_Make_a_Vm/assets/146316539/c41d09f6-39c5-4ffc-b565-497fe2fde23d)
    


    

