# Releases

Download latest PowerTuner release [here](https://github.com/PowerTuner/PowerTuner-releases/releases).

## Packages

### Windows

Download **PowerTunerWindows.zip**.

### Linux

#### AppImage

All distros can use the AppImages.

PowerTunerDaemon must be running in background,

either stand-alone:

```bash
$ sudo ./PowerTunerDaemon-x86_64-1.0.AppImage 
```
or as a systemd service:

Download the service file from [here](https://github.com/PowerTuner/PowerTuner-releases/blob/main/linux/powertunerd.service) and place the file in:

```bash
usr/lib/systemd/system/powertunerd.service
```

Open the newly downloaded file and replace **/usr/bin/PowerTunerDaemon** in **ExecStart** with the path to your **PowerTunerDaemon AppImage**.

####  PowerTunerLinuxUnpacked

This is for manual installation, if you don't like AppImages.

Compiled in latest **Ubuntu** available in GitHub runners, this may not work on ArchLinux or other bleeding edge distros.

#### PowerTunerArchLinux

This is for manual installation, if you don't like AppImages.

This is also what the official AUR package uses.

Compiled in latest **ArchLinux** image available at the time of release, will not work on debian distros, use this for Arch and derivatives.
