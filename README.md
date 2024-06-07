### ROCm Library Files for "unsupported" AMD GPUs for use in Windows.

This repo was created to host ROCm Library files for use in the ZLUDA CUDA Wrapper for AMD GPUs  

- Open Explorer and navigate to  `%ProgramFiles%\AMD\ROCm\5.7\bin\rocblas\`  
- Make a backup of the library folder.  
- Download the relevant optimised ROCm Library 7zip file and place them into the library folder, overwriting any files there.  

#### Added Optimised_ROCmLibs_gfx1032.7z for gfx1032 (6600)
#### Added Optimised_ROCmLibs_gfx1031.7z for gfx1031 (6700)

_(You'll need to install 7-zip or WinRAR to extract these archives.)_

For testing purposes, the old version of ROCmLibs.zip can be accessed on dropbox from here;  
https://www.dropbox.com/scl/fi/qx0ritf10zqof3rlw3rfh/ROCmLibs.zip?rlkey=t8kmkbhm7muk6a26kxoexw0mb&st=kthr8d9f&dl=0  

These libs were pulled from YellowCx's ROCm fork of KoboldCPP.
