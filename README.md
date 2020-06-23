# Catalina 10.15.5 (19F101)
# ASUS-TUF B365M-Plus Gaming hackintosh-EFI OpenCore 0.59

 - 配置清单: 
   - Intel i5 9400
   - Kingston 8G DDR4 2666 * 4
   - ASUS RX580 2304
   - INTEL SSDPEKKW512G8
   - LG HDR DQHD 打开 HIDPI


- BIOS需要打开选项
  - VT-x
  - Above 4G decoding
  - Hyper-Threading
  - Execute Disable Bit
  - EHCI/XHCI Hand-off
  - OS type: Windows 8.1/10 UEFI Mode
  - DVMT Pre-Allocated(iGPU Memory): 64MB



- BIOS需要关闭的选项
  - Fast Boot
  - Secure Boot
  - VT-D （虽然可以不关闭，不过这个直通好象macos也用不上）
  - CSM
  - Thunderbolt
  - Intel SGX
  - Intel Platform Trust
  - CFG Lock



- 参考网站：
    - OpenCore: https://dortania.github.io/OpenCore-Desktop-Guide/config.plist/coffee-lake.html
    - ProperTree：https://github.com/corpnewt/ProperTree
    - GenSMBIOS：https://github.com/corpnewt/GenSMBIOS

## 目前使用未发现问题
