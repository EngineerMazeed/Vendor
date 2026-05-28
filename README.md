# Vendor
This repo is for specialized OEM and vendor firmware images. These files were originally built for specific carrier and vendor hardware. The main goal here is to give a second life to old, legacy devices that have been abandoned by manufacturers and no longer get official updates.

Everything hosted here was dumped directly from physical devices or pulled during my own research and firmware analysis.

### Repository Structure

```
Vendor/
└── UAE Emirates Telecommunications/
    ├── DIR-850L
    ├── DIR-853ET
    └── (more coming soon)
```

*More will be added as I get my hands on them.*

### Notes on the Files

> [!NOTE]
> **Bug Fixes:** Some of these builds have factory bugs fixed. But keep in mind, all vendor code has its own issues—you might find your original firmware actually runs better for your specific setup than the newer builds.

> [!TIP]
> **Empty Folders:** If you see directories with no files inside, it just means the placeholder is there for tracking but I haven't sourced a clean, working firmware dump for that specific model yet.

### CRITICAL WARNING — READ BEFORE FLASHING

> [!CAUTION]
> If you don't know what you are doing, do not touch these files.

> [!WARNING]
> **Carrier & Region Locks:** Some newer firmware versions were modified by vendors with specific carrier configs to lock down the hardware. If your device is currently unlocked on an older version, flashing these newer builds can permanently lock it to that specific regional carrier network. It will refuse to work with any other operator.

> [!WARNING]
> **Do Not Downgrade:** Never try to flash an older firmware version over a newer one. Partition layouts and partition tables change between updates. Forcing old code onto a modified layout will instantly brick the hardware.

> [!TIP]
> **Flash Over Ethernet Only:** To keep the risk as low as possible, run all updates over a wired Ethernet connection. Do not risk your hardware by flashing over Wi-Fi.

> [!CAUTION]
> If you flash the wrong image, break your partition tables during a downgrade, or brick your setup, that is entirely your fault. You took the risk to modify your hardware, so you carry the consequences. Any damage to your device is on you.

### ⚠️ Disclaimer & Legal
​​I don't condone, support, or allow any illegal activity or misuse of these dumps. This repo is just an archive for firmware preservation and analysis.

​All firmware files here where taken directly from working hardware. No external edits, no modifications, and no tampering. What you see is exactly what came off the physical chip. Read the disclaimer, know the risks, and you're good to go
