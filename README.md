This project is used to download NXP NFC source code of android. You can use following command to perform download:

```

repo init -u https://github.com/Kaling1203/NXPNFCProject_manifest.git -m br_android_ncihalx_p.xml
repo sync

```

-u specify the repository of manifest

-m specify the xml used to download source code. You man fork the project and change the content of xml to download the revision that you need.



If you cannot download repo from Google, you can use following command instead:

```
repo init -u https://github.com/Kaling1203/NXPNFCProject_manifest.git -m br_android_ncihalx_p.xml --repo-url=git://codeaurora.org/tools/repo.git --repo-branch=caf-stable
```

It will download repo from codeaurora