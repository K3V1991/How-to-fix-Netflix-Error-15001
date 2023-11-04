<p align="center"><img src="https://github.com/K3V1991/How-to-fix-Netflix-Error-15001/blob/main/Fix.png" width="200"></a>
<h1 align="center"><b>How to fix Netflix Error 15001</b></h1>
<br />

<p align="center">
<a href="https://liberapay.com/K3V1991" alt="LiberaPay"><img src="https://img.shields.io/badge/Liberapay-F6C915?style=for-the-badge&logo=liberapay&logoColor=black" /></a>
<a href="https://ko-fi.com/k3v1991" alt="Ko-fi"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white" /></a>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="PayPal"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" /></a>
<a href="https://github.com/K3V1991/Donate-Crypto/blob/main/README.md" alt="Crypto"><img src="https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white" /></a>
</p>
<hr>
<br />
<br />

## Enable Zygisk & Enforce DenyList:
1. Launch the Magisk App and tap on the ```Settings Icon``` at the top right
2. Scroll to the ```Magisk``` Section and enable the Toggle next to ```Zygisk``` & ```Enforce DenyList```
3. Restart the Device for the Changes to take Place. Verify that Zygisk status is ```Yes``` under ```Magisk```

## 1. Configure DenyList:
1. Open ```Magisk Settings``` Menu and tap on ```Configure DenyList```
2. Now Checkmark the ```Netflix App```
3. After that, tap on the ```Overflow Icon``` at the top right and select ```Show system apps```
4. Now checkmark ```Google Play Store```, ```Google Play Services```  & ```Google Service Framework```

## 2. Hide Magisk App:
1. Go to the ```Magisk Settings Menu``` and tap on ```Hide the Magisk App```
2. Then give it the desired Name of your Choice and tap ```OK```
3. The Hiding Process will begin. Once done, it will ask whether you wish to have the ```App Shortcut``` on the ```Home Screen```
4. You may select ```Yes``` and then tap on the ```Add to Home Screen``` Button

## 3. Delete Google Play Store & Google Play Services Data: 
1. Open ```Settings``` > ```Apps``` > ```See All Apps```
2. Select ```Google Play Store```
3. Then go to the ```Storage & cache``` Section and tap on ```Clear Storage``` > ```OK```
4. Go back and select ```Google Play Service``` and go to its ```Storage & cache``` Section
5. After that, tap on ```Manage Space``` > ```Clear All Data```
6. Restart your Device for the Changes to take place

## 4. Install Magisk Modules:
1. Universal SafetyNet Fix - [XDA](https://forum.xda-developers.com/t/magisk-module-universal-safetynet-fix-2-4-0.4217823/) & liboemcrypto disabler - [XDA](https://forum.xda-developers.com/t/magisk-module-liboemcrypto-disabler-for-drm-protected-content-netflix-my5-etc.3794393/)
2. Reboot your Device
3. Netflix should now work normally
