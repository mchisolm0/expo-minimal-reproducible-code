expo / expo Issue#: [ADD ISSUE LINK HERE]

## Steps to create repo and reproduce error
1. `npx create-expo-app@latest --template blank`
2. `npm run android`

## Output from expo-cli
```
> expo-minimal-reproducible-code@1.0.0 android
> expo start --android

Starting project at /home/mcc/code/expo-minimal-reproducible-code
Starting Metro Bundler
Failed to resolve the Android SDK path. Default install location not found: /home/mcc/Android/sdk. Use ANDROID_HOME to set the Android SDK location.
Failed to resolve the Android SDK path. Default install location not found: /home/mcc/Android/sdk. Use ANDROID_HOME to set the Android SDK location.
Error: spawn adb ENOENT
Error: spawn adb ENOENT
    at Process.ChildProcess._handle.onexit (node:internal/child_process:285:19)
    at onErrorNT (node:internal/child_process:483:16)
    at processTicksAndRejections (node:internal/process/task_queues:82:21)
```
