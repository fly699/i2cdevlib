# SomnoPod (眠舱) Privacy Policy & Apple HealthKit Disclosure | 隐私政策声明

**Last Updated**: November 12, 2026  
**Applicable App**: SomnoPod: Sleep Sounds & HRV / 眠舱 (`com.somnopod.sleep.ios`, `com.somnopod.sleep.global`, `com.somnopod.sleep.china`)  
**Developer**: CHUNHONG TANG  
**Privacy Contact Email**: [t58@163.com](mailto:t58@163.com)  
**HTML Version**: https://fly699.github.io/i2cdevlib/somnopod/PRIVACY_POLICY.html

## 1. 100% On-Device Local Sandbox Commitment (核心本地沙盒承诺)
SomnoPod requires zero account registration and processes all physiological waveforms, sleep records, and optional 8-second snore/sleep-talk audio highlights **100% locally inside your device's private sandbox**. We do NOT upload, sell, or share any personal, sensor, audio, or HealthKit data with any external server, advertiser, or third party.

## 2. Permissions & Data Usage (系统权限与本地用途)
- **Microphone (`NSMicrophoneUsageDescription`)**: Real-time local breathing airflow acoustic envelope (RMS) analysis and optional 8-second snore/sleep-talk highlight clips stored strictly offline on your device (one-tap deletion anytime).
- **Motion & Barometer (`NSMotionUsageDescription`)**: Local bedside BCG micro-vibration, chest tilt respiration, and bedroom barometric pressure sensing.
- **Front Optical Ambient Illuminance (`NSCameraUsageDescription`)**: Reads front optical exposure & ISO metadata **only while the screen is awake** solely to meter bedroom ambient light in Lux; stops immediately when the screen dims/locks and **never captures, saves, or transmits any photos or videos**.
- **Bluetooth LE (`NSBluetoothAlwaysUsageDescription`)**: Connects standard BLE `0x180D` heart rate sensors for live HRV analysis and sleep acoustic entrainment.
- **Apple HealthKit (`NSHealthShareUsageDescription` & `NSHealthUpdateUsageDescription`)**: Reads Heart Rate, Resting Heart Rate, HRV (SDNN), and Sleep Analysis; writes completed real Sleep Sanctuary sessions (`SleepAnalysis`) and Mindful Minutes (`MindfulSession`). Demo records are never written to HealthKit. HealthKit data is never uploaded or used for advertising, marketing, or data mining.
- **Location While In Use (`NSLocationWhenInUseUsageDescription`)**: Local sunset/sunrise circadian alignment and barometric altitude calibration only; coordinates are never uploaded.
- **Photos & Media Library (`NSPhotoLibraryAddUsageDescription` & `NSAppleMusicUsageDescription`)**: Saves sleep report posters to Photos upon user action and allows optional local music mixing alongside the 48kHz sleep synth.

## 3. Contact & Data Control (联系方式与数据控制)
You can delete any or all local records inside SomnoPod at any time, or contact us at **[t58@163.com](mailto:t58@163.com)**.
