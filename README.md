# WIFI
Script to save WIFI password for OnionOs (Miyoo Mini + retro console)

Copy the WIFI folder to App folder on OnionOs SD card.

Copy/move wpa_supplicant.cunt from WIFI to /appconfig/ using File Explorer on MM+.

Now, when you connect to new WIFI, run the app/script. Script is simple as a stick, copies last 4 lines of wpa_supplicant.conf to wpa_supplicant.cunt and then copies wpa_supplicant.cunt to wpa_supplicant.conf. So, your current WIFI's SSID and password is added to the end of cunt file and then, whole list is copied to the conf file. 
