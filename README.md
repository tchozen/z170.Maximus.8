# z170 Maximus VIII - MacOS 26.1
<div style="text-align: left;">
  <img 
    src="https://github.com/user-attachments/assets/05529562-dae2-4d73-8619-d6dcba560377" 
    alt="Imagem Espelhada" 
    style="width: 301px; border-radius: 8px; transform: scaleX(-1); display: inline-block;" 
  />
</div>

⚠️ Disable FileVault after installation! You’ve been warned! ⚠️

⚠️ This EFI was built for Radeon GPUs 5000/6000 series ⚠️

⚠️ Don’t forget to add your Serial Number to config.plist⚠️

⚠️ USB ports may require post-installation adjustment ⚠️

<h2>📁 EFI Folder Structure</h2>
<pre>
EFI/
├── BOOT/
│   └── BOOTx64.efi
├── OC/
│   ├── ACPI/
│   │   └── MaLd0n.aml
│   ├── Drivers/
│   │   ├── apfs_aligned.efi
│   │   ├── AppleALC.efi
│   │   ├── AppleIGC.efi
│   │   ├── OpenCanopy.efi
│   │   ├── OpenRuntime.efi
│   │   └── ResetNvramEntry.efi
│   ├── Kexts/
│   │   ├── AirportBrcmFixup.kext
│   │   ├── AppleALC.kext
│   │   ├── AppleIGC.kext
│   │   ├── AtherosE2200Ethernet.kext
│   │   ├── IntelMausi.kext
│   │   ├── LucyRTL8125Ethernet.kext
│   │   ├── Lilu.kext
│   │   ├── NVMeFix.kext
│   │   ├── RadeonSensor.kext
│   │   ├── RealtekRTL8111.kext
│   │   ├── RestrictEvents.kext
│   │   ├── SMCProcessor.kext
│   │   ├── SMCRadeonGPU.kext
│   │   ├── SMCSuperIO.kext
│   │   ├── USBInjectAll.kext
│   │   ├── VirtualSMC.kext
│   │   ├── WhateverGreen.kext
│   │   └── XHCI-unsupported.kext
│   ├── config.plist
│   └── OpenCore.efi
</pre>
