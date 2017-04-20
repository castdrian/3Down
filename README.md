### Welcome to 3Down

If you went over here, you probably are a N3DS user using Arm9LoaderHax + Luma3DS/Corbenik/anything else that supports the 11.4 NFIRM of the 3DS.

And you want to CTRTRANSFER to another Firmware instead of using SysDowngrader.
So just follow the given instructions.


### What you need

- The latest release of [Decrypt9WIP](https://github.com/d0k3/Decrypt9WIP/releases/latest)
- The latest release of [Luma3DS](https://github.com/AuroraWright/Luma3DS/releases/latest)
- A Torrent Client like [Deluge](http://dev.deluge-torrent.org/wiki/Download)
- The CTRNAND-Transer File corresponding to your 3DS Model, Region and Firmware you want.
   - [11.2.0-35E_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:1C1C3CA3791D32CF5130A896E1DAE81F70AB40F5&dn=11.2.0-35E_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)
   - [11.3.0-36E_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:1D57D6CEC27B6C69212E3D38A423D2920CD7F35B&dn=11.3.0-36E_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce) 
   - [11.3.0-36U_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:E092D5CD157AAE22A286E8691B135D380962356C&dn=11.3.0-36U_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)
   - [11.3.0-36J_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:B77C5E836159AED32E9056E8AB296053BC2BD40A&dn=11.3.0-36J_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)
   - [11.4.0-37E ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:E2BC86AB8A1BE69C146A22667F03D3A6FBE833F3&dn=11.4.0-37E_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)

### Section I - Updating Luma3DS

### Overview of steps
In this section, we will be Updating Luma3DS to the latest one available. If you a already using Luma v7+ you can skip this step
   
### Instructions

1. Remove your SD card from your device, then insert your SD card into your computer
2. Put the **arm9loaderhax.bin** from the **Luma3DS.7z** onto the root of your SD Card, overwriting existing files

### Section II - Backing up Tickets

### Overview of steps
In this section, we will be backing up your device's Tickets

### Instructions

1. Remove your SD card from your device, then insert your SD card into your computer
2. Put the Decrypt9WIP.bin from the Decrypt9WIP release into /luma/payloads
3. Put the SD Card back into your N3DS and launch the Luma3DS Chainloader by holding **START** at boot
4. Launch Decrypt9WIP
5. Navigate to **SysNAND Options**
6. Navigate to **System File Dump...**
7. Select **Dump ticket.db** 

### Section III - CTRNAND Transfer

### Overview of steps
In this section, we will be flashing your Device's CTRNAND partition to the desired version

### Instructions

1. Remove your SD card from your device, then insert your SD card into your computer
3. Extract the content of the **11.X.0-3XX_ctrtransfer_x3ds.7z file** to the root of your SD Card
4. Put the SD Card back into your N3DS and launch the Luma3DS Chainloader by holding **START** at boot
5. Launch Decrypt9WIP
6. Navigate to **SysNAND Options**
7. Navigate to **CTRNAND transfer...**
8. Select **Auto CTRNAND Transfer**
9. Put in the given Code to unlock SysNAND writing
10. Select **11.X.0-3XX_ctrtransfer_x3ds.bin** and hit **A** to confirm
11. Wait for the process to finish and reboot

### Section IV - Restoring Tickets

### Overview of steps
In this section, we will be restoring your device's Tickets

### Instructions
1. Launch the Luma3DS Chainloader by holding **START** at boot
2. Launch Decrypt9WIP
3. Navigate to **SysNAND Options**
4. Navigate to **System File Inject...**
6. Select **Inject ticket.db**
7. Hit **A** to inject it
7. Hit **START** to reboot

### Donations

If you want to support me to keep this project alive you can do that right [Here](https://www.paypal.me/adrifcastr)
(I am seeding the Torrents by myself rn!)

### Credits
- me (adrifcastr/addi33)
- MegaMagikarp
- d0k3 for his work on Decrypt9WIP
- Plailects-Guide-Writing-Style





Do you see any ads? ^^
