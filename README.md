# Convert Office 2016/ 2019 /O365 ClickToRun installation licensing from Retail to Volume

which then can be activated easily using various KMS solutions

 - All current Office licenses will be cleaned up
then, proper Volume licenses will be installed based on detected Product IDs

 - "Mondo" Suite cover all products, if detected, only its licenses will be installed

 - "O365ProPlus" Suite will be converted with Mondo licenses by default

 - "Professional" Suite will be converted with ProPlus licenses

 - If main products SKUs are detected, separate apps licenses will not be installed to avoid duplication

SKUs : O365ProPlus, ProPlus, Professional, Standard, Visio, Project  
Apps : Access, Excel, Onenote, Outlook, Powerpoint, Publisher, SkypeForBusiness, Word  

O365ProPlus and ProPlus cover all apps  
Professional cover all apps except SkypeForBusiness  
Standard cover all apps except Access, SkypeForBusiness  

 - This is not an activator, just a licensing converter

 - Office 2019 products are officially blocked on Windows 7 and 8.1
to workaround that, follow these steps:

 - if you want Office Professional Plus 2019:  
 1) install O365ProPlusRetail SKU  
 2) edit Convert-C2R.cmd and set _O365asO2019=1  
 3) run Convert-C2R.cmd  

 - if you want Project 2019 and/or Visio 2019:  
 1) install desired SKU: ProjectProRetail, ProjectStdRetail, VisioProRetail, VisioStdRetail  
 2) run Convert-C2R.cmd  
 
# Office 2016 /2019 /O365 C2R转换VOL批处理
 - 该脚本用于转换c2r产品（office2016/ 2019 / O365）到VOL版本。  
 - 请用右键管理员运行，批处理会清除当前所有证书并根据对应产品ID导入VOL证书。  
 - Mondo证书覆盖所有产品，因此O365默认会安装Mondo证书，安装后会显示2016 Mondo，但它仍然是Office 365并具有Office 365的特性。而Professional默认会安装ProPlus证书。其他产品ID会安装对应产品证书。  
 - Windows7和8.1被微软禁止安装Office2019，可以安装O365并编辑脚本_O365asO2019=1即可。  
 
