# 律动健走 (WalkFit) 隐私政策 | Privacy Policy | プライバシーポリシー

**生效日期 / Effective Date / 発効日**: 2026-03-31  
**最后更新 / Last Updated / 最終更新日**: 2026-11-10 (v6.1.0)  
**开发者与运营主体 / Developer**: WalkFit Lab (`com.walkfit.app.ios` / `com.walkfit.app.china` / `com.walkfit.app.global`)  
**工信部 App ICP 备案号 / China MIIT ICP Filing**: [京ICP备2026077713号-1A](https://beian.miit.gov.cn/)

---

## 一、中文隐私政策 (Chinese Privacy Policy)

欢迎使用 **律动健走 (WalkFit) — 3+3间歇快慢交替步行节拍器与夜间神经助眠剧场**（以下简称“本应用”）。我们深知运动、健康与睡眠数据的敏感性与重要性，本应用严格遵循 **“本地离线优先、数据最小化、零第三方追踪、零录音上传”** 的设计原则。

### 1. 我们处理哪些信息及用途（100% 设备本地存储）
本应用**无需注册账号**即可完整使用。所有个人体征参数、运动记录与睡眠节律账本均 **100% 存储在您的手机本地沙盒 (`UserDefaults` / 本地加密存储)** 中，绝不上传至任何开发者服务器：

1. **精确与粗略位置权限 (`NSLocationWhenInUseUsageDescription` / `NSLocationAlwaysAndWhenInUseUsageDescription`)**：
   - **用途**：仅在您主动开启户外健走并授权定位时，用于在您的手机本地绘制高德/Apple Maps双引擎配速色温轨迹、计算实时海拔爬升、移动距离及获取目的地周边离线/实时气象指数。
   - **存储与保护**：轨迹坐标点仅保存在您的设备本地运动历史记录中。您可随时通过“历史记录 -> 删除”或“隐私与数据管理 -> 擦除所有本地数据”彻底销毁。

2. **运动与健身传感器 (`NSMotionUsageDescription`) 与系统健康 (`NSHealthShareUsageDescription` / `NSHealthUpdateUsageDescription`)**：
   - **用途**：读取设备内置计步传感器 (`CMPedometer`) 以计算实时步频 (SPM)、步数及自动暂停状态；在您明确授权 Apple Health (HealthKit) 后，在本地读取心率、静息心率、步数，并将完成的健走消耗热量与步行距离写入“系统健康”应用。
   - **存储与保护**：我们绝不会将通过 HealthKit 或运动传感器获取的数据用于广告营销、用户画像或出售给任何第三方数据经纪商。

3. **五源传感神经助眠剧场 4.0（夜间本地内存瞬时节律推演，100% 零录音、零上传）**：
   - **用途**：当您在夜间开启“五源传感神经助眠剧场 4.0”并选择包含声学感知的传感模式时，麦克风 (`NSMicrophoneUsageDescription`) 与加速度计/陀螺仪仅在设备本地 RAM 内存中实时计算声压包络能量 (RMS) 与胸腹呼吸起伏节律，用于驱动 48kHz 助眠声景自适应柔化与睡眠呼吸节律评估。
   - **严格隐私承诺**：**本应用绝不录制、不保存任何原始音频文件，亦绝不向任何云端服务器上传任何声音或传感器数据**。您也可随时在助眠剧场内切换为“枕边床垫微振模式”或关闭麦克风权限。

4. **蓝牙外设连接 (`NSBluetoothAlwaysUsageDescription`)**：
   - **用途**：仅在您主动打开“BLE 蓝牙心率外设直连面板”时，用于扫描并连接符合开放标准的 **BLE 0x180D 蓝牙心率胸带、心率臂带或运动手环**，以实时展示精准心率与梅脱 (METs) 区间。

5. **后台音频播放 (`UIBackgroundModes: audio`)**：
   - **用途**：当您在健走或夜间助眠过程中将应用切入后台或锁屏息屏时，持续为您提供 48kHz 原生节拍器提示音、和弦伴奏、阶段切换语音播报及夜间 48kHz 神经助眠和弦/自然声景。

6. **相册保存权限 (`NSPhotoLibraryAddUsageDescription`)**：
   - **用途**：仅在您主动点击“保存高清运动海报到相册”时，将本地渲染生成的分享图片写入系统相册。本应用不读取您的相册历史照片。

### 2. 应用内购买与订阅 (WalkFit Pro)
- 本应用内的 `WalkFit Pro` 会员订阅（月度订阅 `com.walkfit.pro.monthly`、年度订阅 `com.walkfit.pro.yearly`）与终身买断（`com.walkfit.pro.lifetime`）全部通过 **Apple 官方 StoreKit 2 (App Store)** 安全处理。
- 我们不收集、不接触您的银行卡号、Apple ID 密码或支付账单详情；恢复购买与权益校验均直接通过 Apple 官方加密收据在设备端验证。

### 3. 第三方 SDK 与数据共享声明
- **零广告追踪**：本应用不包含任何第三方跨应用追踪 SDK，不请求 IDFA 广告标识符 (`NSUserTrackingUsageDescription`)，不向任何广告网络共享您的个人数据。
- **气象接口**：当您开启户外气象同步时，应用仅使用去标识化的经纬度网格向公开气象服务请求实时温度、湿度与空气质量指数，不包含任何设备标识符或个人身份信息。

### 4. 您的数据控制权与一键擦除
- 您可以随时在应用内 **“方案与设置 -> 隐私与数据管理 -> 一键清除所有本地运动与睡眠数据”**，或直接卸载本应用，立即且不可逆地清除保存在本机上的全部健走历史、睡眠账本与个人体征设置。

### 5. 联系我们
如您对本隐私政策或数据处理有任何疑问，请通过以下方式联系我们：
- **电子邮箱**：support@walkfit.app
- **在线技术支持与问题反馈**：https://github.com/fly699/i2cdevlib/issues

---

## 二、English Privacy Policy

Welcome to **WalkFit — 3+3 Interval Walking Metronome & 5-Sensor Sleep Sanctuary** ("the App"). We respect your privacy and built WalkFit strictly around **100% On-Device Storage, Data Minimization, Zero Ad Tracking, and Zero Audio Recording**.

### 1. Information We Process (100% Stored Locally on Your Device)
WalkFit requires **no account registration**. All personal physical parameters, walking workout logs, and sleep rhythm records are stored **100% locally on your device** and are never uploaded to any developer servers:

1. **Location Data (`WhenInUse` / `AlwaysAndWhenInUse`)**:
   - **Purpose**: Used exclusively during active outdoor walking workouts (when authorized by you) to render pace-colored GPS route tracks, calculate elevation gain and distance, and fetch local weather/UV indices.
   - **Storage**: Route coordinates remain strictly on your device and can be deleted at any time from History or Settings.

2. **Motion Sensors (`CMPedometer`) & Apple Health (`HealthKit`)**:
   - **Purpose**: Reads step cadence (SPM) and step counts for real-time 3+3 interval coaching; with your explicit authorization, reads heart rate and step metrics from Apple Health and writes completed walking workouts back to the Health app.
   - **Protection**: HealthKit and motion data are never used for advertising, marketing, or shared with any third parties.

3. **5-Sensor Sleep Sanctuary 4.0 (Real-Time RAM Rhythm Processing, Zero Audio Recording)**:
   - **Purpose**: When you use Sleep Sanctuary 4.0 with acoustic sensing enabled, the microphone (`NSMicrophoneUsageDescription`) and accelerometer/gyroscope process sound pressure envelopes (RMS) and breathing rhythms strictly in volatile on-device RAM to drive real-time 48kHz sleep soundscape softening and sleep stage estimation.
   - **Strict Guarantee**: **WalkFit NEVER records, saves, or transmits any audio files or voice data to any server.**

4. **Bluetooth LE Peripherals (`CoreBluetooth`)**:
   - **Purpose**: Used only when you open the Bluetooth Heart Rate Hub to scan and connect to standard **Bluetooth LE (0x180D) heart rate chest straps, armbands, or fitness bands** for real-time BPM and METs display.

5. **Background Audio (`UIBackgroundModes: audio`)**:
   - **Purpose**: Ensures uninterrupted 48kHz walking metronome beats, chord accompaniment, interval voice coaching, and 48kHz sleep soundscapes when the screen is locked or when you switch to the iOS Home Screen.

6. **In-App Purchases (`StoreKit 2`)**:
   - All `WalkFit Pro` subscriptions (`com.walkfit.pro.monthly`, `com.walkfit.pro.yearly`) and Lifetime unlock (`com.walkfit.pro.lifetime`) are processed exclusively by Apple via StoreKit 2. We never access your payment card details.

### 2. Contact Us
If you have any questions regarding privacy or data protection, please contact us at:
- **Email**: support@walkfit.app
- **Support Page**: https://github.com/fly699/i2cdevlib/blob/walkfit-legal/SUPPORT.md

---

## 三、日本語プライバシーポリシー (Japanese Privacy Policy)

**WalkFit（律動インターバル速歩 ＆ 五感センサー睡眠シアター 4.0）**（以下「本アプリ」）は、ユーザーのプライバシーを最優先に設計されており、**「アカウント登録不要・100%端末内ローカル保存・広告トラッキングゼロ・録音ゼロ」**を徹底しています。

1. **端末内ローカル処理とデータ保護**：
   - **位置情報・モーションセンサー・Apple ヘルスケア (HealthKit)**：屋外ウォーキング時のルート軌跡描画、歩調（SPM）計測、およびヘルスケア連携のためにのみ使用され、すべてお使いの iPhone 内にのみ保存されます。外部サーバーへの送信や第三者への提供は一切行いません。
   - **睡眠シアター 4.0（録音ゼロ・完全ローカル処理）**：睡眠中の呼吸リズムおよび音響包絡線（RMS）解析は、端末のメモリ（RAM）内でリアルタイムに計算されるのみで、**音声データの録音・保存・外部送信は一切行いません**。
   - **Bluetooth 心拍計連携 ＆ バックグラウンド再生**：標準 BLE (0x180D) 心拍センサーとの接続、および画面ロック中・バックグラウンドでの 48kHz メトロノーム／睡眠サウンド再生のためにのみ使用されます。
2. **お問い合わせ**：support@walkfit.app

---
**合规备案信息 / Regulatory Filing**: [京ICP备2026077713号-1A](https://beian.miit.gov.cn/) | 工信部政务服务平台：https://beian.miit.gov.cn/
