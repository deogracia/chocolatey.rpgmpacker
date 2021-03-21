# RPGMPacker chocolatey package

## Get it from chocolatey

```
choc install rpgmpacker
```

## Update it

* Get the new release inside the `tools` directory
* Rename it `rpgmpacker.exe`
* Update (maybe version at least) `rpgmpacker.nuspec`
* Run

```
choco pack
choco push MyPackage.$VERSION$.nupkg --source https://push.chocolatey.org/
```