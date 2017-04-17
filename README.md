### Welcome to 3Down

If you went over here, you probably are a N3DS user using Arm9LoaderHax + Luma3DS/Corbenik/anything else that supports the 11.4 NFIRM of the 3DS.

You are probably here because the 11.4 System Update patched a Module that requires NTR itself to be updated by Cell9 to re-allow N3DS Screen Streaming and you want to go back to 11.3 without using SysDowngrader and the CIA Package.
Or you simply don't like 11.4

### Overview of steps

In this section, we will be flashing your device’s CTRNAND partition to 11.3

### What you need

- The latest release of [Decrypt9WIP](https://github.com/d0k3/Decrypt9WIP/releases/latest)
- A Torrent Client like [Deluge](http://dev.deluge-torrent.org/wiki/Download)
- The CTRNAND-Transer File corresponding to your 3DS Model and Region.
   - [11.3.0-36E_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:1D57D6CEC27B6C69212E3D38A423D2920CD7F35B&dn=11.3.0-36E_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce) 
   - [11.3.0-36U_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:E092D5CD157AAE22A286E8691B135D380962356C&dn=11.3.0-36U_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)
   - [11.3.0-36J_ctrtransfer_n3ds.7z](magnet:?xt=urn:btih:B77C5E836159AED32E9056E8AB296053BC2BD40A&dn=11.3.0-36J_ctrtransfer_n3ds.7z&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a80%2fannounce&tr=udp%3a%2f%2ftracker.opentrackr.org%3a1337%2fannounce)
   
### Instructions

1. Remove your SD card from your device, then insert your SD card into your computer
2. Put the Decrypt9WIP.bin from the Decrypt9WIP release into /luma/payloads
3. Extract the content of the **ctrtransfer .7z file** to the root of your SD Card
4. Put the SD Card back into your N3DS and launch the Luma3DS Chainloader by holding **START** at boot.
5. Launch Decrypt9WIP
6. Navigate to **SysNAND Options**
7. Navigate to **CTRNAND transfer...**
8. Select **Auto CTRNAND Transfer**
9. Put in the given Code to unlock SysNAND writing
10. Select **11.3.0-36X_ctrtransfer_x3ds.bin** and hit **A** to confirm
11. Wait for the process to finish and reboot

### Credits
- me 
- MegaMagikarp
- d0k3 for his work on Decrypt9WIP
- Plailects-Guide-Writing-Style

### Donations

If you want to support me you can do that right [Here](https://www.paypal.me/adrifcastr)
(I am seeding the Torrents by myself rn!)


<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- 3Down -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-1269180183054029"
     data-ad-slot="7240651192"
     data-ad-format="auto"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>

Do you see any ads? ^^
