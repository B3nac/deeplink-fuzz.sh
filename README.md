# deeplink-fuzz.sh

A Bash wrapper for radamsa that can be used to fuzz exported activities and deep links.

#### Requirements

1. radamsa [https://gitlab.com/akihe/radamsa](https://gitlab.com/akihe/radamsa)

2. Android Debug Bridge [https://developer.android.com/studio/command-line/adb](https://developer.android.com/studio/command-line/adb)

3. The AndroidManifest.xml file from the target application. I provided a test AndroidManifest.xml from InjuredAndroid

4. A device connected to Android Debug Bridge

---

#### Commands

I kept this super simple for now.

For deeplinks

```bash
./deeplink-fuzz.sh deeplinks

or

bash deeplink-fuzz.sh deeplinks
```

For activities

```bash
./deeplink-fuzz.sh activities

or

bash deeplink-fuzz.sh activities
```

F.A.Q

Do I need to use the 💩 emoji to generate fuzzing data?

No this is a joke from a local CTF event called Bad Santa Hacking Adventure. :)