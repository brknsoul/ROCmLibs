### ROCm Library Files for "unsupported" AMD GPUs for use in Windows.

This repo was created to host ROCm Library files for use in the ZLUDA CUDA Wrapper for AMD GPUs  
_(Note: Unless stated, these libraries only support HIP SDK 5.7.1)_  

- Open Explorer and navigate to  `%ProgramFiles%\AMD\ROCm\5.7\bin\rocblas\`  
- Make a backup of the library folder.  
- Download the relevant ROCm Library 7zip file and extract the library folder, overwriting any files there.
- If the 7zip file also contains `rocblas.dll`, extract this into `%ProgramFiles%\AMD\ROCm\5.7\bin`  

#### Changes
- Added Optimised_ROCmLibs_gfx1032.7z for gfx1032 (6600)  
- Added Optimised_ROCmLibs_gfx1031.7z for gfx1031 (6700)  
- Added rocm gfx1031 for HIP SDK 6.1.2 optimized.7z  
- Added gfx1031, gfx1032 for HIP SDK 6.2.4  
- Added NewerROCmLibs.rar for HIP SDK 5.7.1. Might support gfx803.  
   _(These are from a later version YellowRoseCX's Fork of KoboldCPP)_
- Added gfx902-vega8, (supports 2200g, 2400g, 3200g, 3400g). This libary requires an older version of torch;  
  `pip install torch==2.2.1 torchvision==0.17.1 torchaudio==2.2.1 --index-url https://download.pytorch.org/whl/cu118`
- Added rocm gfx1201 for rocm 6.2.4-no-optimized.7z for 9000 series GPUs.
  
_(You'll need to install 7-zip or WinRAR to extract these archives.)_

---

For testing purposes, the old version of ROCmLibs.zip can be accessed on dropbox from [here](https://www.dropbox.com/scl/fi/qx0ritf10zqof3rlw3rfh/ROCmLibs.zip?rlkey=t8kmkbhm7muk6a26kxoexw0mb&st=kthr8d9f&dl=0).  
These libs were pulled from YellowRoseCx's ROCm [fork](https://github.com/YellowRoseCx/koboldcpp-rocm) of KoboldCPP.
