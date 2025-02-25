# Legion-5-15ACH6H kernel config 6.6.62

## Graphics:
CONFIG_FB  
CONFIG_FB_EFI  
CONFIG_DRM  
CONFIG_DRM_KMS_HELPER  
CONFIG_DRM_FBDEV_EMULATION  
CONFIG_FB_ATY  
CONFIG_FB_ATY128  
CONFIG_FB_RADEON  
CONFIG_VGA_SWITCHEROO  
CONFIG_DRM_AMDGPU  
CONFIG_DRM_NOUVEAU  
CONFIG_DRM_SIMPLEDRM

## USB:
Settings for USB audio over Type-C:    


CONFIG_SND_USB_AUDIO


## NVMe:
CONFIG_BLK_DEV_NVME  
CONFIG_DEVTMPFS

## BPF:

dev-util/pahole should be installed


CONFIG_BPF_JIT  
CONFIG_BPF_JIT_ALWAYS_ON  
CONFIG_BPF_UNPRIV_DEFAULT_OFF  
CONFIG_BPF_PRELOAD  
CONFIG_DEBUG_INFO_DWARF4  
CONFIG_DEBUG_INFO_BTF  
CONFIG_DEBUG_INFO_BTF_MODULES  
CONFIG_MODULE_ALLOW_BTF_MISMATCH  
CONFIG_FUNCTION_TRACER

## Network
If cfg80211 and mac80211 are built as parts of the kernel, then the firmware must also be built into the kernel    


CONFIG_CFG80211    
CONFIG_MAC80211  
CONFIG_IWLWIFI  
CONFIG_IWLDVM  
CONFIG_IWLMVM  


WEXT:

CONFIG_CFG80211_WEXT  

TUN/TAP:

CONFIG_TUN  
CONFIG_VETH  

bridge:

CONFIG_BRIDGE  
CONFIG_BRIDGE_NETFILTER  

## Touchpad support  
I2C & HID:


CONFIG_ACPI_I2C_OPREGION  
CONFIG_I2C_PIIX4  
CONFIG_I2C_MUX  
CONFIG_I2C_SCMI  
CONFIG_I2C_DESIGNWARE_PLATFORM  
CONFIG_I2C_DESIGNWARE_PCI  
CONFIG_UHID  
CONFIG_HID_MULTITOUCH  
CONFIG_I2C_HID_ACPI  
CONFIG_PINCTRL_AMD  
