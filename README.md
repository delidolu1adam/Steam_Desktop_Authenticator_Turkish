<h1 align="center">
  <img src="https://raw.githubusercontent.com/Jessecar96/SteamDesktopAuthenticator/master/icon.png" height="64" width="64" />
  <br/>
  Steam Masaüstü Kimlik Doğrulayıcı
</h1>
<p align="">
Steam Masaüstü Kimlik Doğrulayıcı, Steam mobil kimlik doğrulama uygulamasının alternatif bir masaüstü sürümüdür.<br/> Bu proje <a href="https://github.com/Jessecar96" target="_blank">Jessecar96</a> tarafından geliştirilen <a href="https://github.com/Jessecar96/SteamDesktopAuthenticator" target="_blank">Steam Dekstop Authenticator</a> uygulamasının açık kaynak kodları Türkçe'ye tercüme edilerek ve orjinal kodlarda herhangi bir değişiklik yapılmadan üretilmiştir.</br></br>
<b>Steam veya Scrap.TF ile hiçbir şekilde bağlantımız yoktur!</b> Bu proje topluluk gönüllüleri tarafından yürütülmektedir.
</p>
<h3 align="center">
  <p>DİKKAT: Steam Masaüstü Kimlik Doğrulayıcı artık geliştiricisi tarafından desteklenmeyecek ve herhangi bir güncelleme almayacaktır.
  <p>UYARI: Son zamanlarda Steam hesabınızı çalacak sahte SMKD sürümleri ortalıkta dolaşıyor. SMKD'yı bu github deposundan başka hiçbir yerden asla indirmeyin!</p>
</h3>
<h3 align="center" style="margin-bottom:0">
  <a href="https://github.com/delidolu1adam/Steam_Desktop_Authenticator_Turkish/releases/latest">[Buradan İndir]</a>
</h3>
<p align="center">Windows 10 ve üzeri sürümleri destekler.</p>
<br>

**Clicking "Download ZIP" will not work!** This project uses git submodules so you must use git to download it properly. Using [GitHub Desktop](https://desktop.github.com/) is an easy way to do that.

**SORUMLULUK REDDİ: Bu uygulamayı uzun yıllardır kullanıyorum ve şimdiye kadar da Valve tarafından yasaklanmadım ve yasaklanan birini de duymadım. Ancak bunun yin de bir garantisi yok. Bu uygulamayı kullanmadan önce, hesabınızın yasaklanma riskini göz önünde bulundurarak kullanıp ya da kullanmamak tamamen kendi insiyatifinizdedir. Bu uygulamada herhangi bir Virüs ya da Trojen yoktur, kullanmadan önce dosyaları bir virüs taramasından geçirmeniz önemle arz edilir. Dilerseniz uygulamanın kaynak kodlarını da inceleyebilirsiniz. Bu konuda hiç bir sorumluluk kabul etmediğim gibi Steam Masaüstü Kimlik Doğrulayıcı uygulama kullanırken size hiçbir destek sağlamıyorum!**

**REMEMBER: Always make backups of your `maFiles` directory! If you lose your encryption key or delete `maFiles` by accident AND you didn't save your revocation code, you are screwed.**

**FINALLY: Using this application is a bad idea, because it COMPLETELY DEFEATS THE PURPOSE of two-factor authentication! If your desktop is infected with a virus, it will be able to hijack the authenticator app and completely subvert the protection. THIS APPLICATION DOES NOT PROTECT YOUR ACCOUNT; IT ONLY ALLOWS YOU TO USE STEAM FEATURES THAT REQUIRE THE AUTHENTICATOR WITHOUT HAVING A PHONE. If you have a phone that supports the Mobile Authenticator, you really shouldn't use this application!**

IF you lost your `maFiles` OR lost your encryption key, go [here](https://store.steampowered.com/twofactor/manage) and click "Remove Authenticator" then enter your revocation code that you wrote down when you first added your account to SDA.

If you did not follow the directions and did not write your revocation code down, you're well and truly screwed. The only option is beg to [Steam Support](https://support.steampowered.com/) and say you lost your mobile authenticator and the revocation code.

## Detailed setup instructions
- Download & Install [.NET 8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0).
- Visit [the releases page](https://github.com/Jessecar96/SteamDesktopAuthenticator/releases) and download the latest .zip (not the source code one).
- Extract the files somewhere very safe on your computer. If you lose the files you can lose access to your Steam account.
- Run `Steam Desktop Authenticator.exe` and click the button to set up a new account.
- Login to Steam and follow the instructions to set it up. **Note: you still need a mobile phone that can receive SMS.**
- You may be asked to set up encryption, this is to make sure if someone gains access to your computer they can't steal your Steam account from this program. This is optional but highly recommended.
- Select your account from the list to view the current login code, and click `Trade Confirmations` to see pending trade confirmations.
- For your safety, remember to get Steam Guard backup codes! Follow [this link](https://store.steampowered.com/twofactor/manage) and click "Get Backup Codes," then print out that page and save it in a safe place. You can use these codes if you lose access to your authenticator.

[How to update SDA.](https://github.com/Jessecar96/SteamDesktopAuthenticator/wiki/Updating)

[How to use SDA on multiple computers.](https://github.com/Jessecar96/SteamDesktopAuthenticator/wiki/Using-SDA-on-multiple-computers)


## Command line options
```
-k [encryption key]
  Set your encryption key when opened
-s
  Auto-minimize to tray when opened
```

## Troubleshooting
- **Trade confirmation list is just white or a blank screen**
 - First open the "Selected Account" menu, then click "Force session refresh". If it still doesn't work after that, open the "Selected Account" menu again, then click "Login again" and login to your Steam account.

If your problem doesn't appear on the list or none of the solutions worked, submit an issue on the issue tracker. When posting logs in an issue, please upload it to some site like [Pastebin](http://www.pastebin.com).
