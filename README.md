# RustCord
Tiny (5MiB) Discord client built with Pake/Tauri.
![preview.png](https://raw.githubusercontent.com/onrirr/rustCord/main/preview,.png)
you can download a pre-build windows installer [here](https://github.com/onrirr/rustCord/releases/download/educational/rustCord.msi) for testing and educational purposes.

# Statistics
These tests were done on a intel i5 5200u 2core@2.20ghz, 4gb 1600mhz ram
|  |RustCord|Discord|
|--|--|--|
|Ram usage:|186MB|324MB|
|CPU usage:|%1.6|%26.5|
|App size:|12MB|387MB|
|Installer size:|4.76MB|91MB|

# Does this go against the T.o.S.?
In technicality, as this is still a build of the [discord.com](https://discord.com) website, it does not violate the T.o.S. since it is not a custom client but rather a different runtime or browser. If we assume that tauri is just a one page web browser that is extremely minimal and that no changes are being made to the website, this is not against the t.o.s. 

# Building
prerequisites: Rust, Npm (Nodejs)
```
$ npm install -g pake-cli
$ pake https://discord.com/channels/@me
```
