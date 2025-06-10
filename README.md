# SX-TOOLS Cracked

this tools was using python 3.10 you can download in here, please make sure u use 3.10
[download here](https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe)

This repository contains a cracked version of **SX-TOOLS**, a Python-based reconnaissance tool. idk why thou this tools was in the sell

### 🔓 Status: Cracked

**Byte-patched** to bypass authentication 

---

## 🔐 Authentication APIs (Blocked/Tracked)

SX-TOOLS attempts to authenticate using the following endpoints (now bypassed):

```
https://akbarwiran.my.id/log/tobrut.php?login=
https://sx-tools-e91565f48b95.herokuapp.com/proxy.php?site=https://akbarwiran.my.id/log/tobrut.php?login=
https://tokoawn.com/sx/proxy.php?site=https://akbarwiran.my.id/log/tobrut.php?login=
https://sx-tools-e91565f48b95.herokuapp.com/?login=
```

These URLs are used to log credentials or track tool usage. They have been **neutralized** in this release.

---

## 🔎 Scraping Targets (Recon Sources)

SX-TOOLS uses **Cloudscraper** to bypass Cloudflare protection and scrape data from:

* `https://www.cubdomain.com/domains-registered-by-date/`
* `https://api.cubdomain.com/Home/domains-registered-by-date/`
* `https://haxor.id/archive?page={}`
* `https://haxor.id/archive/special?page={}`
* `https://zone-h.org/archive/filter=1/filter_date_select=week/page=`
* `https://crt.sh/?q=%25&output=json`

These are commonly used for finding new domains, leaked defacements, and Certificate Transparency logs.

---


