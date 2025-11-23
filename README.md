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

Now we build the solution with the Compiler configuration Release and Debug 

In the toolbar: 

Platform: **x64**

Configuration:**Debug**

Then Build → Build Solution (or F7).

Change configuration to **Release** and build again.

After success, you should have folders:

```
C:\wxWidgets-3.1.1\build\msw\vc_x64_mswu
C:\wxWidgets-3.1.1\build\msw\vc_x64_mswud
```

<img width="1227" height="381" alt="image" src="https://github.com/user-attachments/assets/a7bb7988-0802-4c58-87a3-b7499c7cd575" />




## Step 3: Download and Install CMake

We download CMake version 3.31.10

https://cmake.org/download/#older

<img width="1919" height="469" alt="image" src="https://github.com/user-attachments/assets/2f43dcca-b3eb-4c2d-b661-1b6225256ceb" />

We execute the following command to open the Environmental Variables as Administrator to have access to the System Variables:

<img width="500" height="52" alt="image" src="https://github.com/user-attachments/assets/2f65efea-ed53-4f7c-8c1a-4cc18edc7f2c" />

```
C:\>SystemPropertiesAdvanced.exe
```

We confirm CMake was added to the PATH environmental variable:

<img width="1364" height="666" alt="image" src="https://github.com/user-attachments/assets/d712e4b4-dd08-4d95-a0cf-990175db10e6" />

We verify the CMake version installed:

<img width="860" height="185" alt="image" src="https://github.com/user-attachments/assets/fbf55c27-8ab7-4313-908c-52715e7a66f8" />

## Step 4: Clone SolarPILOT Code Repositories

We create a new folder solarpilot_dev in the C:\

```
C:\solarpilot_dev
```

We execute the following commands to git clone the repos:

```
cd C:\solarpilot_dev

git clone https://github.com/nrel/lk
git clone https://github.com/nrel/wex
git clone https://github.com/nrel/soltrace
git clone https://github.com/mjwagner2/ssc
git clone https://github.com/nrel/solarpilot
```
## Step 5: Set Environment Variables

## Step 6: Run CMake to Generate SolarPILOT VS 2022 Project Files



## Step 7: Build SolarPILOT


## Step 8: Run SolarPilot



## Step 4: 



