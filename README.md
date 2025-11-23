# SolarPILOT_NREL_How-to-install-in-your-Laptop

See also the official NREL web sites:

https://github.com/NREL/SolarPILOT

https://github.com/NREL/SAM/wiki/Windows-Build-Instructions

## Step 1: Download and Install Build Tools for Visual Studio 2022

https://visualstudio.microsoft.com/vs/older-downloads/

<img width="1912" height="818" alt="image" src="https://github.com/user-attachments/assets/ca2ab832-0c39-46e3-8253-14c25d64f523" />

https://my.visualstudio.com/Downloads?q=visual%20studio%202022&wt.mc_id=o~msft~vscom~older-downloads

<img width="1918" height="966" alt="image" src="https://github.com/user-attachments/assets/1ba0daf3-478d-44b3-b130-e89301c65b4c" />

Be sure to install: Desktop Development for C++ and Tools for developement with Linux and Mac

<img width="1672" height="565" alt="image" src="https://github.com/user-attachments/assets/93e5199f-5b19-449c-a442-9b679c21f147" />

<img width="1675" height="711" alt="image" src="https://github.com/user-attachments/assets/80286e78-6d47-486f-ab77-8b7fa2414ee3" />

Verify the Build Tools for Visual Studio 2022 installation:

<img width="1254" height="695" alt="image" src="https://github.com/user-attachments/assets/14514e8c-09cc-4fbd-bd6b-377c179fe5a5" />

## Step 2: Download and Build wxWidgets 3.1.1

We download wxWidgets 3.1.1 from this web page:

https://github.com/wxWidgets/wxWidgets/releases/tag/v3.1.1

<img width="1918" height="961" alt="image" src="https://github.com/user-attachments/assets/4988590b-5ad8-4464-ad79-17951872687f" />

We extract the ZIP file in C:\wxWidgets-3.1.1 and we open the solution wx_vc15.sln with Visual Studio:

<img width="1176" height="517" alt="image" src="https://github.com/user-attachments/assets/b026aaf0-5727-4a04-83b8-e79475eab95a" />

We configure the Platform ToolSet (Visual Studio 2022 (v143)) in all the projects:

<img width="1919" height="831" alt="image" src="https://github.com/user-attachments/assets/4f606afb-50d3-4dcc-afb5-569f0cbaf936" />

<img width="1919" height="853" alt="image" src="https://github.com/user-attachments/assets/0df4b4ce-840d-4ced-a3c7-2769ba3c205e" />

We select the Compilation Configuration "Release" and the Platform "x64"

<img width="1884" height="258" alt="image" src="https://github.com/user-attachments/assets/593499cf-e2b9-4bf8-8749-7a9acc10620d" />

We confirm with the Configuration Manager the Compilation Configuration

<img width="1078" height="257" alt="image" src="https://github.com/user-attachments/assets/11505527-4c9b-4c1d-85f4-02153eda6509" />

<img width="800" height="584" alt="image" src="https://github.com/user-attachments/assets/10197c1b-ef9c-458a-b29f-d1f5ce8d6e70" />

We select the Build all the project selecting the menu option Build-Batch Build

<img width="1058" height="380" alt="image" src="https://github.com/user-attachments/assets/d56974d6-ee02-4797-b9a1-df80154b4c0a" />




## Step 3: Download and Install CMake


We verify the CMake version installed:

<img width="860" height="185" alt="image" src="https://github.com/user-attachments/assets/fbf55c27-8ab7-4313-908c-52715e7a66f8" />


## Step 4: Clone SolarPILOT Code Repositories


## Step 5: Set Environment Variables

## Step 6: Run CMake to Generate SolarPILOT VS 2022 Project Files



## Step 7: Build SolarPILOT


## Step 8: Run SolarPilot



## Step 4: 



