# Bypass requirement to login or create a Microsoft account for Windows

From the OOBE Screen press Shift + F10

```
curl -L raw.githubusercontent.com/Nerdworks-Services/bypassnro/refs/heads/main/bypass.cmd -o bypass.cmd
bypass.cmd
```

This will skip the entire OOBE process including microsoft account and ANY questions during the setup process. It still allows you to select your language, region, and keyboard layout.
