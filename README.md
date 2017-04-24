### Welcome to 3Down

If you went over here, you probably are a N3DS user using Arm9LoaderHax + Luma3DS/Corbenik/anything else that supports the 11.4 NFIRM of the 3DS.

And you want to CTRTRANSFER to another Firmware instead of using SysDowngrader.
So just follow the given instructions.

**NEVER EVER WRITE CHANGES TO YOUR SYSNAND WITHOUT HAVING A NAND BACKUP**


### What you need

- The latest release of [Decrypt9WIP](https://github.com/d0k3/Decrypt9WIP/releases/latest)
- The latest release of [Luma3DS](https://github.com/AuroraWright/Luma3DS/releases/latest)
- A Torrent Client like [Deluge](http://dev.deluge-torrent.org/wiki/Download)
- The CTRNAND-Transer File corresponding to your 3DS Model, Region and Firmware you want.

## N3DS       
**11.2**
   - [11.2.0-35E_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:1C1C3CA3791D32CF5130A896E1DAE81F70AB40F5&dn=11.2.0-35E_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)   (by me)
   
**11.3**   
   - [11.3.0-36E_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:1D57D6CEC27B6C69212E3D38A423D2920CD7F35B&dn=11.3.0-36E_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)   (by me)
   - [11.3.0-36U_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:E092D5CD157AAE22A286E8691B135D380962356C&dn=11.3.0-36U_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)   (by @MegaMagikarp)
   - [11.3.0-36J_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:B77C5E836159AED32E9056E8AB296053BC2BD40A&dn=11.3.0-36J_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)   (by @MegaMagikarp)
   
**11.4**   
   - [11.4.0-37E_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:E2BC86AB8A1BE69C146A22667F03D3A6FBE833F3&dn=11.4.0-37E_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)   (by me)
   
## O3DS/2DS
**11.2**
- [11.2.0-35U_ctrtransfer_o3ds.7z](magnet:?xt=urn:btih:e448fa57d33ce6fb69dce2ddf08fc657fdc3910a&dn=11.2.0-35U_ctrtransfer_o3ds.7z&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce)

### Section I - Updating Luma3DS

### Overview of steps
In this section, we will be Updating Luma3DS to the latest one available. If you a already using Luma v7+ you can skip this step
   
### Instructions

1. Remove your SD card from your device, then insert your SD card into your computer
2. Put the **arm9loaderhax.bin** from the **Luma3DS.7z** onto the root of your SD Card, overwriting existing files

### Section II - Backing up Tickets & friendsave.bin

### Overview of steps
In this section, we will be backing up your device's Tickets and friendsave.bin

### Instructions

1. Remove your SD card from your device, then insert your SD card into your computer
2. Put the Decrypt9WIP.bin from the Decrypt9WIP release into /luma/payloads
3. Put the SD Card back into your N3DS and launch the Luma3DS Chainloader by holding **START** at boot
4. Launch Decrypt9WIP
5. Navigate to **Ticket/Titlekey Options**
6. Navigate to **Ticket Dump (SysNAND) / (EmuNAND) if you are using this guide on an EmuNAND**
7. Wait for the process to finish 
8. Navigate to **SysNAND Options / EmuNAND Options if you are using this guide on an EmuNAND**
9. Navigate to **System Save Dump...**
10. Select **Dump friendsave.bin** 


### Section III - CTRNAND Transfer

### Overview of steps
In this section, we will be flashing your Device's CTRNAND partition to the desired version

### Instructions

1. Remove your SD card from your device, then insert your SD card into your computer
3. Extract the content of the **11.X.0-3XX_ctrtransfer_x3ds.7z file** to the root of your SD Card
4. Put the SD Card back into your N3DS and launch the Luma3DS Chainloader by holding **START** at boot
5. Launch Decrypt9WIP
6. Navigate to **SysNAND Options / EmuNAND Options if you are using this guide on an EmuNAND**
7. Navigate to **CTRNAND transfer...**
8. Select **Auto CTRNAND Transfer**
9. Put in the given Code to unlock NAND writing
10. Select **11.X.0-3XX_ctrtransfer_x3ds.bin** and hit **A** to confirm
11. Wait for the process to finish and reboot

### Section IV - Restoring Tickets

### Overview of steps
In this section, we will be restoring your device's Tickets and friendsave.bin

### Instructions

1. Launch Decrypt9WIP
2. Navigate to **Ticket/Titlekey Options**
3. Navigate to **SysNAND Options / EmuNAND Options if you are using this guide on an EmuNAND**
4. Navigate to **System Save Inject...**
5. Select **Inject friendsave.bin** 
6. Put in the given Code to unlock NAND writing and confirm the injecton
7. Launch **FBI**
8. Navigate to **SD -> files9**
9. Navigate to **current directory**
10. Hit **A**
11. Select **Install and delete all Tickets** and hit **A** to install
12. Exit **FBI**


### Donations

If you want to support me to keep this project alive you can do that right Here:
- [Paypal](https://www.paypal.me/adrifcastr)
- Bitcoin: 19oxvLrCc688DRV9cXTSV1wnQtozRKC6uC


(I am seeding the Torrents by myself rn!)

### Contact
- Mail: adrian.f.castro.mail@gmail.com
- Temp: @addi33
- Discord: #4530

### Credits
- me (adrifcastr/addi33)
- MegaMagikarp
- Yuan
- d0k3 for his work on Decrypt9WIP
- saibotu for some ticket related info
- Plailects-Guide-Writing-Style





Do you see any ads? ^^



(Disclaimer: I am not responsible if your console takes any type of damage!)
