# ***New Vegas* Modding INI Notes**
----
## **NVSE INI**
### **Add the following to `Data/nvse/nvse_config.ini` if you want logging for any game errors**
```fix
[Logging]
EnableGameErrorLog=1
[RELEASE]
LogLevel=1
```
### **`Data/nvse/nvse_config.ini` -> `[Memory] DefaultHeapInitialAllocMB`**
### **4GB Patch ❌ 8GB RAM ❌ 2GB vRAM ❌ `DefaultHeapInitialAllocMB=256`**
### **4GB Patch ✅ 8GB RAM ✅ 2GB vRAM ❌  `DefaultHeapInitialAllocMB=400`**
### **4GB Patch ✅ 8GB RAM ✅ 2GB vRAM ✅ `DefaultHeapInitialAllocMB=496`**
----
## NVSR INI
### **`Data/nvse/plugins/sr_New_Vegas_Stutter_Remover.ini` -> `Master.bHookLightSections`**
### **`bHookLightSections = 1` for performance**
### **`bHookLightSections = 0` for stability**
### **`Data/nvse/plugins/sr_New_Vegas_Stutter_Remover.ini` -> `FPS_Management.fMinimumFPS`**
### **`fMinimumFPS = 15` for consistent, actual minimum FPS at the cost of no extra LODs and effects**
### **`fMinimumFPS = 1` for NO consistent, actual minimum FPS at the bonus of extra LODs and effects**
