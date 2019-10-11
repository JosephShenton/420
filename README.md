# 420 Signer

420 Signer is an extremely fast and versatile signing utility for the macOS (and CentOS soon) operating system.

  - Based on [zSign] by [@zhlynn]
  - Used by the Ignition Team [@TryIgnition]
  - 100% Open Source

### Requirements
* OpenSSL 1.0.2t
* macOS
* P12
* Mobileprovision
* Password
* Some terminal knowledge

### Features
* Sign app
* Bulk resign app (Soon)
* Resign app (basically sign app) (Soon)

### To-Do
* Finish resign function

### Installation
```
cd path/to/420Signer/folder/
chmod 777 420
chmod 777 420Signer
```

### Example
```
./420Signer -f SA -a ~/Downloads/unc0ver.ipa -m ~/Desktop/420/Epson.mobileprovi
sion -c ~/Desktop/420/Epson.p12 -p 1234
```

License
----
GNU General Public License v3.0


**Free Software, Hell Yeah!**
   
[@TryIgnition]: <https://twitter.com/TryIgnition>
[@zhlynn]: <https://github.com/zhlynn>
[zSign]: <https://github.com/zhlynn/zsign>