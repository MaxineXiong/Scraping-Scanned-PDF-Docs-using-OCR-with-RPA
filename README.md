### UiPath RPA Robot
# Extracting Text from Scanned PDF Documents using Optical Character Recognition (OCR)

[![GitHub](https://badgen.net/badge/icon/GitHub?icon=github&color=black&label)](https://github.com/MaxineXiong)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform - UiPath RPA](https://img.shields.io/badge/Platform-UiPath_RPA-fa4616)](https://www.uipath.com)

<br/>

This repository houses efficient automation solutions designed for extracting text from a series of **scanned PDF documents** sharing identical layouts and formats. Leveraging the built-in *Tesseract OCR engine*, the UiPath RPA robot achieves nearly 90% accuracy in text recognition (and with other paid OCR services such as [*Microsoft Azure Computer Vision OCR engine*](https://azure.microsoft.com/) and [*Google Cloud Vision OCR engine*](https://cloud.google.com/), the accuracy can reach up to 98%!). It **adeptly extracts relevant information from each scanned document and consolidates it into a single text file**, as demonstrated by the output text files located in the *Outputs* folder. Offering a swift automation solution, this RPA robot significantly reduces the time-consuming manual effort required for the such tasks.


This repository includes solutions created using both **Classic Design** and **Modern Design** in UiPath Studio. 

_You can check out the **automation demo video for classic solution** below_:

https://github.com/MaxineXiong/Scraping-Scanned-PDF-Docs-using-OCR-with-RPA/assets/55864839/8d69eca4-f89e-4f59-938f-e84264234603


Below is **a snapshot of an example of the final output from the modern solution** (Unfortunately, I am unable to showcase the automation demo video for the modern solution here since the solution
directly extracts information from the scanned documents without the need to open them, making it significantly faster!):

![scraping-scanned-receipt-modern-OCR](https://github.com/MaxineXiong/Scraping-Scanned-PDF-Docs-using-OCR-with-RPA/assets/55864839/8e8c9375-5391-4ca1-a543-364ec84af6e8)



<br/>


## **Installation**

Before installing **UiPath Softwares**, please make sure your system meets the hardware and software requirements outlined in the **[UiPath documentation](https://docs.uipath.com/studio/standalone/2022.10/user-guide/hardware-and-software-requirements)**.

The **Uipath Platform** includes the following tools:

- **UiPath Studio**
- **UiPath Robot**
- **UiPath Orchestrator**

<details>  
<summary> To run this project successfully, please follow these steps to install UiPath Studio:
</summary>

***

Step 1 : Visit [uipath.com](https://www.uipath.com/) and click **Try UiPath Free** button.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_1.png">
</p>

Step 2: **Sign up** for a personal account.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_2.png">
</p>  

Step 3: **Verify** your account in email.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_3.png">
</p>  

Step 4: **Log into** the **UiPath Automation Cloud** using your account, and click the **Download Uipath Studio** button.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_4.png">
</p>   

Step 5: Click **Sign in**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_5.png">
</p>    

Step 6: Select **UiPath Studio Pro**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_6.png">
</p>  

Step 7: Follow the system instructions to complete the installation of **UiPath Studio Pro**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_7.png">
</p> 

</details> 

<br/>

## **Usage**

To run the RPA workflow on your local machine, follow these steps:

1. Either **download** this repository to your local machine or **clone** it directly within your UiPath Studio.
2. Open the **UiPath Studio** software on your machine.
3. Locate and **open** the **Main.xaml** file from the downloaded repository in **UiPath Studio**.
4. **Run** the **Main_modern.xaml** or **Main_classic.xaml**file to start the OCR-based scraping process on the scanned documents.

<br/>

## **Acknowledgement**

I would like to express my gratitude to the **[UiPath community](https://community.uipath.com/)** for providing resources, tutorials, and a platform for automation enthusiasts to learn and collaborate.

<br/>

## **License**

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/), which means you're free to modify, distribute, and use the code in your own projects.








