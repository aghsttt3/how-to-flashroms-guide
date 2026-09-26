how-to-flashroms-guide

A guide to the basic logic of custom ROMs.

The simplest guide—not for actual flashing/unlocking, but for a basic understanding of "What is this anyway?"

⚙️ How Custom ROM Logic Works: From Bootloader to Custom Builds
A guide for those who want to understand how unlocking works, why you need root, and how custom ROMs differ. No unnecessary theory.


📂 Bootloader (BOOTLOADER)
Every device has a bootloader whose primary job is to boot the operating system. Hardware initialization, running low-level code—all of this is handled by it. The OS boot process itself follows a similar structure across all smartphones, but differs deeply in the details depending on the processor, manufacturer, and specific platform.
The main rule: if you want to flash a custom ROM or root a device, its bootloader must be unlocked. Without this, security systems simply won't allow third-party code to run.
Each manufacturer has its own unlocking policy. Take Xiaomi, for example:
 * How it was before HyperOS: You just needed to install processor drivers (Qualcomm/MTK) along with Fastboot & ADB utilities. Turn on "OEM unlocking" in Developer options, link the phone to your Mi Account, connect it to a PC in Fastboot mode, click the coveted button in Mi Unlock Tool, and wait the mandatory 7 days.
 * How it became on HyperOS: Xiaomi made life significantly harder. Now official unlocking is tied to your account level inside the Xiaomi Community app. You need a certain account "tenure," passing Android knowledge quizzes (on Chinese or English forums), and you face strict annual unlock limits. You can't just casually waltz in and unlock a fresh Xiaomi running HyperOS anymore.
Currently, almost all brands have tightened the screws: OnePlus, OPPO, and Realme are clamping down with regional locks and unlock tokens. VIVO and Huawei cannot be unlocked using simple manual methods at all. Samsung is tightening its security loop as well (especially on newer One UI versions 8.0 and above, where Knox permanently disables features upon unlocking, and the "Download Mode" functionality itself has been completely stripped out).
Against this backdrop, Google Pixels remain among the easiest and most friendly devices for bootloader unlocking and modding. There, everything can still be flashed with a couple of terminal commands:
 * fastboot devices — Checks if the device is connected to the PC in Fastboot mode.
 * fastboot flashing unlock — The unlock command itself for older models (Pixel 2/3).
 * fastboot oem unlock — The unlock command itself for current models.
👑 What is ROOT and why do you need it?
If unlocking the bootloader is opening the door to the system, then getting Root rights (superuser) is gaining absolute control over the device. By default, the manufacturer treats the user as "clueless" and blocks access to system files. Root fixes that.
Back in the day, everyone used SuperSU, then Magisk became king, and now KernelSU is trending (working directly at the kernel level, making it much harder for banking apps to detect).
What root gives you in practice:
 * Full Debloating: Removing any system bloatware and uninstallable vendor software.
 * Sound and Graphics Customization: Installing advanced audio processing engines (Viper4Android, JamesDSP) and overriding display refresh rates or CPU profiles.
 * Bypassing Restrictions: Accessing hidden game/app files, spoofing system configs, and fine-tuning hardware.
💿 Types of Custom ROMs: What to flash?
Once your bootloader is unlocked, you face the choice of which system to flash. They can generally be divided into three camps:
1. Pure AOSP / LineageOS (Purebred Android)
* AOSP (Android Open Source Project) — "bare-bones" stock Android source code directly from Google, free of extra additions.
 * LineageOS (formerly CyanogenMod) — an icon of the custom ROM world. It’s the same clean Android experience, but packed with useful custom features.
 * Pros: Blazing fast performance, ultra-minimalism, revives even ancient hardware. Battery lasts longer, and there is a tons of free RAM.
 * Cons: The design is "an acquired taste" (it can feel plain after colorful vendor skins), and the camera on pure customs often performs worse because proprietary manufacturer algorithms (like Xiaomi's Leica processing) cannot be ported over.
2. Pixel Experience (Pixel Experience, Evolution X, etc.)
Custom ROMs designed to imitate Google Pixel smartphones. They come pre-baked with exclusive Pixel features: unlimited Google Photos cloud backup (via device spoofing), signature wallpapers, fonts, and widgets. The ideal balance between a custom build and a polished visual experience.
3. Stock-based Mods (Vendor Customs)
This is when developers take official stock firmware (such as MIUI/HyperOS or One UI), strip out all the junk, bloatware, ads, and Chinese trackers, then add root features, custom kernels, and smoothness tweaks.
 * Why use it: Perfect if you love your phone's signature stock features (camera quality, system gestures, ecosystem integration), but hate that the stock software lags or drains the battery.
