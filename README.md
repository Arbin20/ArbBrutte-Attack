# ArbBrutteAttack-Instagram v1.1.1
## Krijoi: Arbin Qazimi
## IG: instagram.com/arbin.qazimi
### Kodi në skript është shënuar nga ana ime personalisht prandaj për të përdorur këtë kodë duhet të tu dërgoj incialet, Ju Faleminderit! 
ArbBrutteAttack është një shell script programore në të cilë përdoren disa formula nga kriptografia si dhe algoritmi i Ceaser, 
i cili mundëson që një llogari në instagram të provoj shumë fjalëkalime dhe shpesh ndosh që të gjendet edhe fjalkalimi i saktë!

### Features
- Multi-thread (400 pass/min, 20 threads)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Usage:
```
git clone https://github.com/thelinuxchoice/instashell
cd instashell
chmod +x instashell.sh
service tor start
sudo ./instashell.sh
```

### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh
```

### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR and rotating the ip address to avoid blocking. 
The script uses Instagram-py algorithm, see the project at: https://github.com/antony-jr/instagram-py

### Donate!
Support the authors:

<noscript><a href="https://liberapay.com/thelinuxchoice/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
