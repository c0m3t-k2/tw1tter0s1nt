# twosint - v 2.0.4 Release

![WhatsApp Image 2021-06-13 at 17 13 58](https://user-images.githubusercontent.com/83426553/121810787-d1007580-cc6a-11eb-9319-330e9a5e2068.jpeg)

# official blog post

-> https://falkensmaze.medium.com/how-to-conduct-a-twitter-osint-investigation-like-a-pro-d04831478f1a

# INTRODUCTION 

Hello everybody, I go by the name c0m3t-k2 or falkensmaze.

I have created this tool for beginners, to automate the process of twint.

- This python tool uses the twint library to automate the Twitter OSiNT Investigation steps.

- You just have to fill up the required information and select your chosen investigation and it's done!

- I will update this tool whenever new ideas pop in my head so let me know if you find any bugs or if you can help me improve the tool!

# UPDATE :
 
  - 'Till now the tool was very automated, you only needed to put in the username and select the option
  - Right now though, it is much more interesting. 
  - You can use the tool like a terminal cmd-line interface.
  - If you get stuck, type in 'help'
  - And for all of the script kiddies out there that want everything automated, don't worry , I re-coded an automation file "automation.py"

# twint INSTALLATION :

  - git clone --depth=1 https://github.com/twintproject/twint.git
  - cd twint
  - pip3 install . -r requirements.txt

# twosint INSTALLATION :
  - git clone https://github.com/c0m3t-k2/tw1tter0s1nt.git
  - cd tw1tter0s1nt
  - pip install -r requirements.txt / pip3 install -r requirements.txt
  - chmod +x twosint.py
  - python3 twosint.py
 
  Windows 
  - pip3 install --user --upgrade -e git+https://github.com/twintproject/twint.git@origin/master#egg=twint
  - git clone https://github.com/c0m3t-k2/tw1tter0s1nt.git
  - cd [tw1tter0s1nt directory]
  - python twosint.py / python3 twosint.py
If the requirements file doesn't work, type in : pip3 install twint

# windows support

- currently, me and the users of twosint have discorverd heavy bugs while using the framework on Windows
- because of that, I have currently ended Windows support, however I am still working on it.
- I will try to find a way to get it working on Windows but for now me and my friends have not found a way to get it working!
- we recommend either using a VM or a cloud console.
- Linux users, do not worry , Linux is 100% supported and it is the platform the framework is mainained on.
 
# WHO IS THIS TOOL FOR? : 
  - Penetration testers/Ethical hackers
  - IT students that are looking for something cool to search for.
  - OSiNT investigators (This tool is a MUST for you! It makes the job much more faster and efficient!)
  - Journalists who are looking for more information on a specific celebrity or person

 Some things to note:
 - You NEED the python library twint. Installation guide right here : https://github.com/twintproject/twint
 - The author of the tool is not responsible in any way for one's misactions using tw1tter0s1nt.
 - Please keep in mind that this is a tool made by only a person and so it is hard to keep up with all the bugs and issues.
 - Still, if you find any bugs, report them in the issues section!

# TESTED ENVIRONMENTS:
 - Kali Linux ==> Fully supported
 - Pop!_OS ==> Fully supported
 - Windows 10/11 ===> Support ended on 7/20/2021


# Automation Script Announcement
 - I put a lot of hard work into developing and maintaining the original twosint.py script . 
 - The automation script usually for script kiddies is a better copy of the old automated tw1tter0sn1t.py file
 - It is completely usable however , I wanted to announce this :
      - Maintenance updates will be applied once every month!
      - Module updates will be applied 2 weeks after the twosint.py BETA update
      - Aesthetic (if any) will be applied 4 weeks after twosint.py will be updated
      - Security updates will still be initiated right after I or someone else discovers a hole in the script (I want my users to have a secure OSiNT investigation)
 - What I am trying to do is create a Twitter OSiNT framework!
 - The tool will still automate a lot of subprocesses that you will have to go through if you would do it without the script.
 - Using the automation.py script is not wrong , however, in some time I will probably end its updates!
 - If the tool will get attention and if you want to contribute to it, you can absolutely implement the new features from the twosint-framework to the automation file.
 - The problem is that I do NOT have enough time to update the automation software fast.
# Basic usage:

![new_example](https://user-images.githubusercontent.com/83426553/122554126-412f4280-d041-11eb-91b3-09904ef21b6d.png)

Anyone can contribute to this tool , but don't steal code nerd!

CURRENT VERSION --> twosint 2.0.4

Thanks, c0m3t-k2!
