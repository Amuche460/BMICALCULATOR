# BMICALCULATOR
PROJECT TITLE 

BMI CALCULATOR

DESCRIPTION

The BMI Calculator is a GUI program to calculate the user's Body Mass based on their weight and height. The program is written in python programming language 3.9 and it is in no way to replace the one seen online. This can be used on the Desktop but more features will be added later.

USAGE

STEP 1: When the application loads, you will see the Graphical User Interface (GUI) as shown below:
![BMIINTERFACE](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/ef17b3be-de97-4cd4-b39a-b35d1a8ab72c)

STEP 2: Input your Feet, Height, and Weight in each field's respective textbox (See Figure 1 above)

STEP 3: Click the Calculate BMI button to show the caculation and remark (Figure 2)
![BMICALC](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/79c509fe-34e3-4b81-b725-647a16988366)


ERROR CORRECTION

As with any good program, each input is checked first before calculating the BMI and generating the remark.
![BMI](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/dabceda0-d4ce-4321-8aa2-4f90cea9e6a9)


VERSION UPDATE

The version is BMIC Ver 1 and any update will be shown here.  

DEPLOYMENT

To run this file, make sure that python is installed (Using Python 3.9 or more) and press F5 using IDLE IDE. But any IDE like Visual Studio Code or any IDE will do.
To convert to an executable (.exe), you have two options: 

STEP 1: First install pyinstaller via the command line or terminal by typing...pip install pyinstaller

STEP 2: Type the following in the command line
pyinstaller --onefile --windowed --add-data "xi.icon;" BMI.py

STEP 3: Allow pyinstaller to compile the file and add all the resources and dependencies needed to create the executable.

STEP 4: Check the folder and run the exe in another computer. It will successfully run

Alternatively (and even better option), you can use auto-py-to-exe to generate the executable. This normally opens a GUI for compiling your programs. First install auto-py-to-exe by typing the following in the commandline: pip install auto-py-to-exe and then follow the steps as shown below:

![i](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/e3bb4d21-942d-4202-8695-e1ed9c870d0c)



Notice that python39.dll was added. This will help run the program in older versions of Windows eg Windows 7, 8, 8.1 (probably they have not been updated for a long time. This will avoid generating errors such as the one shown in issues section). 

ISSUES

Please note that your Windows Defender Antivirus (and some other antimalware programs) may block the application from running. This is a false positive error message. Kindly pause the protection for a while and run again

The dependency python39 must be added to avoid errors such as the one shown below:

![python39 error](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/f82bf579-5e94-42bc-ac71-a86baa0b810d)

![Failed Message DLL](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/99205021-2112-442d-95d6-e03ebb31a78a)



The python39 is saved in the AppData folder. As shown in the image below:

![python39](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/52d20e77-dfcd-42d2-b4cd-8cfed835c4f8)

![i](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/f89571b9-024e-40e0-b7d8-29434fa7bb18)

