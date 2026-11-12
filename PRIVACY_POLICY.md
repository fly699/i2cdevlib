# 律动健走 (WalkFit) 隐私政策 | Privacy Policy | プライバシーポリシー

**生效日期 / Effective Date / 発効日**: 2026-03-31  
**最后更新 / Last Updated / 最終更新日**: 2026-11-12 (v6.1.0)  
**应用与研发主体 / Developer**: WalkFit Clinical Sports Lab (`com.walkfit.app.ios` / `com.walkfit.app.china` / `com.walkfit.app.global`)  
**官方联系邮箱 / Contact Email**: [t58@163.com](mailto:t58@163.com)  
**工信部 App ICP 备案号 / China MIIT ICP Filing**: [京ICP备2026077713号-1A](https://beian.miit.gov.cn/)

---

## 一、中文隐私政策 (Chinese Privacy Policy)

欢迎使用 **律动健走 (WalkFit) — 3+3间歇快慢交替步行节拍器与夜间神经助眠剧场**（以下简称“本应用”）。我们深知运动、健康与睡眠数据的敏感性与重要性，本应用严格遵循 **“本地离线优先、数据最小化、零第三方广告追踪、零录音上传”** 的设计原则。

### 1. 我们处理哪些信息及用途（100% 设备本地存储）
本应用**无需注册账号**即可完整使用。所有个人体征参数、运动记录与睡眠节律账本均 **100% 存储在您的手机本地沙盒 (`UserDefaults` / 本地加密存储)** 中，绝不上传至任何开发者服务器：

1. **前台与后台运动位置权限 (`NSLocationWhenInUseUsageDescription` / `NSLocationAlwaysAndWhenInUseUsageDescription` / `UIBackgroundModes: location`)**：
   - **用途**：仅在您主动点击开启户外 `3+3` 间歇健走并授权定位时，用于记录户外运动配速轨迹、海拔爬升、步行距离，以及请求周边公开气象指数。当您在健走进行中将手机锁屏放入口袋或切回主屏幕时，应用会启用系统后台持续定位（并在 iOS 状态栏显著展示蓝色后台定位指示图标），以防户外轨迹与里程中断；**一旦您点击结束健走，后台定位立即停止**（夜间助眠与日常浏览期间绝不调用定位）。
   - **存储与保护**：轨迹坐标点仅保存在您的设备本地运动历史记录中。您可随时通过“历史记录 -> 删除”或“设置 -> 一键清除所有本地数据”彻底销毁。

2. **Apple Health 系统健康 (`HealthKit` — `NSHealthShareUsageDescription` / `NSHealthUpdateUsageDescription`) 与运动传感器 (`CMPedometer` / `NSMotionUsageDescription`)**：
   - **运动与气压传感器**：读取设备内置计步与惯性传感器以实时推算步频 (SPM)、动态步幅与夜间枕边床垫呼吸微振节律。
   - **Apple Health (HealthKit) 明确读写范围**：仅在您于首页或设置页的“Apple Health (HealthKit)”专属卡片明确授权后：
     - **读取 (4 项)**：心率 (`Heart Rate`, BPM)、活动能量/动态卡路里 (`Active Energy`, kcal)、步行+跑步距离 (`Walking + Running Distance`, km) 及体能训练记录 (`Workouts`)，用于在应用内健康看板展示今日消耗与计算储备心率强度 (`%HRR`)；
     - **写入 (3 项)**：将真实完成的间歇健走体能训练记录 (`Workouts`)、活动能量 (`Active Energy`, kcal) 及步行+跑步距离 (`Distance`, km) 写入系统“健康”App 以闭合 Apple 健身圆环（内置演示样本记录不会写入 HealthKit）。
   - **严格合规保护**：我们严格遵守 Apple HealthKit 规范，**绝不会将通过 HealthKit 获取的任何健康数据用于广告宣传、市场营销、用户画像，亦绝不出售或共享给任何第三方数据经纪商或云端服务器**。

3. **五源传感神经助眠剧场 4.0（夜间本地内存瞬时节律推演，100% 零录音、零上传）**：
   - **用途**：当您在夜间开启“五源传感神经助眠剧场 4.0”并选择包含声学感知的传感模式时，麦克风 (`NSMicrophoneUsageDescription`) 与加速度计/陀螺仪仅在设备易失性内存 (RAM) 中实时计算声压包络能量 (RMS) 与胸腹呼吸起伏节律，用于驱动 48kHz 助眠声景自适应柔化与睡眠呼吸节律评估。
   - **严格隐私承诺**：**本应用绝不录制、不落盘保存任何原始音频文件，亦绝不向任何云端服务器上传任何声音或传感器数据**。您也可随时切换为“枕边耦合微振模式”或关闭麦克风权限。

4. **蓝牙外设连接 (`CoreBluetooth` / `NSBluetoothAlwaysUsageDescription`)**：
   - **用途**：仅在您主动打开蓝牙心率连接面板时，扫描并直连符合开放标准的 **BLE 0x180D 蓝牙心率胸带、心率臂带或运动手表/手环**，以实时展示精准心率 (BPM) 与梅脱 (METs) 区间。

5. **后台音频播放 (`UIBackgroundModes: audio`)**：
   - **用途**：当您在日间 `3+3` 间歇健走或夜间助眠剧场运行期间将应用切入后台或锁屏息屏时，持续为您提供 48kHz 实时合成步频节拍器、和弦伴奏、快慢走阶段切换语音播报及夜间 48kHz 神经助眠声景，并在系统控制中心与锁屏界面提供媒体控制卡片。

6. **相册保存权限 (`NSPhotoLibraryAddUsageDescription`)**：
   - **用途**：仅在您主动点击“保存高清运动海报到相册”时，将本地渲染生成的分享图片写入系统相册。本应用不读取您的相册历史照片。

### 2. 应用内购买与订阅 (WalkFit Pro)
- 本应用内的 `WalkFit Pro` 会员订阅（月度订阅 `com.walkfit.pro.monthly`、年度订阅 `com.walkfit.pro.yearly`）与终身买断（`com.walkfit.pro.lifetime`）全部通过 **Apple 官方 StoreKit 2 (App Store)** 安全处理。
- 我们不收集、不接触您的银行卡号、Apple ID 密码或支付账单详情；恢复购买与权益校验均直接通过 Apple 官方加密收据在设备端完成。

### 3. 第三方 SDK 与数据共享声明
- **零广告追踪**：本应用不包含任何第三方广告或跨应用追踪 SDK，不请求 IDFA 广告标识符 (`NSUserTrackingUsageDescription`)，不向任何第三方共享您的个人数据。
- **气象接口**：当您开启户外气象同步时，应用仅使用去标识化的粗略网格坐标向公开气象服务请求实时温度、湿度与紫外线指数，不包含任何设备标识符或个人身份信息。

### 4. 您的数据控制权与一键擦除
- 您可以随时在应用内 **“设置 -> 隐私与数据管理 -> 一键清除所有本地运动与睡眠数据”**，或直接卸载本应用，立即且不可逆地清除保存在本机上的全部健走历史、睡眠账本与个人体征设置；也可随时在 iOS“设置 -> 隐私与安全性 -> 健康”中撤回 HealthKit 授权。

### 5. 联系我们
如您对本隐私政策或数据处理有任何疑问，请通过以下方式联系我们：
- **官方联系邮箱**：[t58@163.com](mailto:t58@163.com)
- **官方网站与帮助中心**：[https://fly699.github.io/i2cdevlib/SUPPORT.html](https://fly699.github.io/i2cdevlib/SUPPORT.html)

---

## 二、English Privacy Policy

Welcome to **WalkFit — 3+3 Interval Walking Metronome & 5-Sensor Sleep Sanctuary** ("the App"), developed by **WalkFit Clinical Sports Lab**. We built WalkFit strictly around **100% On-Device Storage, Data Minimization, Zero Ad Tracking, and Zero Audio Recording**.

### 1. Information We Process (100% Stored Locally on Your Device)
WalkFit requires **no account registration**. All personal physical parameters, walking workout logs, and sleep rhythm records are stored **100% locally on your device** and are never uploaded to any developer servers:

1. **Foreground & Background Location (`WhenInUse` / `AlwaysAndWhenInUse` / `UIBackgroundModes: location`)**:
   - **Purpose**: Used exclusively during an active outdoor `3+3` interval walking workout (when authorized by you) to record GPS route trajectories, elevation gain, distance, and pace calibration. While an active workout is running and you lock your screen or switch to the Home Screen with your phone in your pocket, WalkFit enables continuous background location updates (displaying the standard blue iOS status-bar location indicator) so outdoor route tracking is not interrupted. **Background location stops immediately the moment your workout ends.**
   - **Storage**: Route coordinates remain strictly on your device and can be deleted anytime in History or Settings.

2. **Apple Health (`HealthKit`) & Motion Sensors (`CMPedometer`)**:
   - **Motion & Barometer Sensors**: Reads step cadence (SPM) and step counts for real-time 3+3 interval coaching and pillow-side mattress micro-vibration breathing rhythm analysis.
   - **Explicit Apple Health (`HealthKit`) Scope**: Only after your explicit opt-in via the dedicated `"Apple Health (HealthKit) Fitness & HR Sync"` card on the Home or Settings tab:
     - **HealthKit Read (4 types)**: Heart Rate (`BPM`), Active Energy Burned (`kcal`), Walking + Running Distance (`km`), and Workouts (`HKWorkoutType`) to display daily activity metrics and calculate `%HRR` intensity zones;
     - **HealthKit Write (3 types)**: Writes completed real Interval Walking Workouts (`HKWorkoutType`), Active Energy Burned (`kcal`), and Walking + Running Distance (`km`) to Apple Health to close your Fitness Rings (built-in demo sample workouts are never written to HealthKit).
   - **Strict HealthKit Compliance**: **HealthKit data is processed exclusively on your device and is NEVER used for advertising, marketing, user profiling, or sold/shared with any third parties or external servers.**

3. **5-Sensor Sleep Sanctuary 4.0 (Volatile RAM Processing, Zero Audio Recording)**:
   - **Purpose**: When acoustic sensing is enabled in Sleep Sanctuary 4.0, the microphone (`NSMicrophoneUsageDescription`) and motion sensors compute sound pressure envelopes (RMS) and breathing rhythms strictly in volatile on-device RAM to drive real-time 48kHz sleep soundscape softening and sleep stage estimation.
   - **Strict Guarantee**: **WalkFit NEVER records, saves to disk, or transmits any audio files or voice data to any server.**

4. **Bluetooth LE Peripherals (`CoreBluetooth`)**:
   - **Purpose**: Used only when you open the Bluetooth Heart Rate Hub to scan and connect to standard **Bluetooth LE (0x180D) heart rate chest straps, armbands, or smartwatches** for live BPM and METs telemetry.

5. **Background Audio (`UIBackgroundModes: audio`)**:
   - **Purpose**: Ensures uninterrupted 48kHz walking metronome beats, chord accompaniment, interval voice coaching (during walking workouts), and 48kHz neuro-acoustic sleep soundscapes (during Sleep Sanctuary) when the screen is locked or when you navigate to the Home Screen, with full Lock Screen / Control Center Now Playing controls.

6. **In-App Purchases (`StoreKit 2`)**:
   - All `WalkFit Pro` subscriptions (`com.walkfit.pro.monthly`, `com.walkfit.pro.yearly`) and Lifetime unlock (`com.walkfit.pro.lifetime`) are processed exclusively by Apple via StoreKit 2. We never access your payment card details.

### 2. Contact Us
If you have any questions regarding privacy or data protection, please contact us at:
- **Email**: [t58@163.com](mailto:t58@163.com)
- **Official Support Center**: [https://fly699.github.io/i2cdevlib/SUPPORT.html](https://fly699.github.io/i2cdevlib/SUPPORT.html)

---

## 三、日本語プライバシーポリシー (Japanese Privacy Policy)

**WalkFit（律動インターバル速歩 ＆ 五感センサー睡眠シアター 4.0）**（以下「本アプリ」）は、ユーザーのプライバシーを最優先に設計されており、**「アカウント登録不要・100%端末内ローカル保存・広告トラッキングゼロ・録音ゼロ」**を徹底しています。

1. **端末内ローカル処理とデータ保護**：
   - **バックグラウンド位置情報（`UIBackgroundModes: location`）**：屋外の 3+3 インターバル速歩ワークアウト実行中のみ、画面ロック中やバックグラウンドでも GPS ルート軌跡と距離を途切れず記録するために使用され（iOS ステータスバーに青い位置情報インジケーターが表示されます）、ワークアウト終了と同時に即座に停止します。
   - **Apple ヘルスケア (`HealthKit`) 連携**：ユーザーの明示的な許可のもと、4項目（心拍数・アクティブエネルギー・ウォーキング＋ランニングの距離・ワークアウト）の読み取りと、完了した実ワークアウト3項目（ワークアウト・アクティブエネルギー・距離）の書き込みのみを行います。HealthKit データを広告・マーケティング目的で使用したり第三者に提供することは一切ありません。
   - **睡眠シアター 4.0（録音ゼロ・完全ローカル処理）**：睡眠中の呼吸リズムおよび音響包絡線（RMS）解析は端末のメモリ（RAM）内でリアルタイムに計算されるのみで、**音声データの録音・保存・外部送信は一切行いません**。
   - **Bluetooth 心拍計連携 ＆ バックグラウンドオーディオ再生**：標準 BLE (0x180D) 心拍センサーとの接続、および画面ロック中・バックグラウンドでの 48kHz メトロノーム／睡眠サウンド継続再生のためにのみ使用されます。
2. **お問い合わせ**：[t58@163.com](mailto:t58@163.com)

---
**合规备案信息 / Regulatory Filing**: [京ICP备2026077713号-1A](https://beian.miit.gov.cn/) | 工信部政务服务平台：https://beian.miit.gov.cn/
