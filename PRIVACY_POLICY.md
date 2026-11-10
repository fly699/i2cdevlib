# 眠舱 (SomnoPod) 隐私政策 | Privacy Policy | プライバシーポリシー

**生效日期 / Effective Date / 発効日**: 2026-11-10  
**最后更新 / Last Updated / 最終更新日**: 2026-11-10 (v1.0)  
**适用应用与包名 / Applicable App & Bundle IDs**: **眠舱 (SomnoPod)** (`com.somnopod.sleep.ios` / `com.somnopod.sleep.global` / `com.somnopod.sleep.china`)  
**联系邮箱 / Contact Email / お問い合わせ**: [fly699@gmail.com](mailto:fly699@gmail.com)

---

## 一、中文隐私政策 (Chinese Privacy Policy)

欢迎使用 **眠舱 (SomnoPod) — 脑波白噪音助眠、五源传感睡眠监测与冥想呼吸恢复舱**（以下简称“本应用”）。我们高度重视您的个人隐私与睡眠健康数据安全。本隐私政策严格遵循 Apple《App Review 指南》第 5.1.1 条及《中华人民共和国个人信息保护法》等相关法律法规制定，秉持 **“无需注册账号、100% 设备本地存储、数据最小化、零第三方广告追踪、零音频云端上传”** 的核心架构原则。

### 1. 我们处理的设备权限与数据类型（100% 本地沙盒处理与存储）

本应用**不设账号体系、无需登录注册**，亦无任何收集用户个人健康或音频数据的云端后台。所有传感计算与历史睡眠账本均 **100% 存储在您的 iPhone 本地沙盒 (`UserDefaults` / 本地应用私有目录)** 中：

1. **麦克风声学呼吸包络与可选本地睡眠高光片段 (`NSMicrophoneUsageDescription`)**：
   - **收集与处理方式**：当您主动开启夜间睡眠监测并授权麦克风权限时，本应用在设备本地实时计算环境声压包络能量 (RMS)、呼吸节律频率以及鼾声/梦话声学特征，用于驱动 48kHz 脑波与自然白噪音助眠声景的智能自适应柔化及睡眠周期评估。
   - **可选本地高光片段存储说明**：若您主动开启“鼾声/梦话高光片段本地留存”选项，触发阈值的短音频片段**仅保存在您手机本地的应用私有沙盒目录中**，仅供您本人在次日清晨回放查阅；您可随时单条删除或一键清空。若关闭该选项，声学分析仅在设备易失性内存 (RAM) 中瞬时完成，不落盘保存任何音频文件。
   - **零上传铁律**：**无论何种模式，本应用绝不向任何开发者服务器或第三方云端上传、传输或备份任何原始录音、环境声音或声学特征数据。**

2. **运动、加速度计、气压计与距离传感器 (`NSMotionUsageDescription` / `CoreMotion` / `CMAltimeter` / 近距离传感)**：
   - **用途**：当您将手机置于枕边或床垫一侧进行睡眠监测与小睡恢复时，本应用在本地读取加速度计、陀螺仪、运动协处理器、气压计微压变化及近距离传感器状态（如翻转扣屏息屏节能感知），用于无穿戴评估床垫微振动、夜间翻身睡姿体动频率与胸腹呼吸节律。
   - **存储与保护**：原始高频传感器波形仅在本地内存中实时推演，生成的睡眠阶段摘要仅保存在本机，绝不外传。

3. **蓝牙心率外设直连 (`NSBluetoothAlwaysUsageDescription` / `CoreBluetooth`)**：
   - **用途**：仅在您主动进入蓝牙心率连接面板时，扫描并直连符合开放标准的 **Bluetooth LE (`0x180D`) 蓝牙心率胸带、心率臂带或运动手环**，用于实时计算夜间静息心率、心率变异性 (HRV) 自主神经压力恢复指数与共振呼吸生物反馈。
   - **保护承诺**：蓝牙连接仅用于读取实时心率测量值，不收集外设无关隐私信息，亦不上传服务器。

4. **Apple Health 健康数据读写权限 (`NSHealthShareUsageDescription` / `NSHealthUpdateUsageDescription`)**：
   - **涉及的数据类型**：在获得您的明确单项授权后，本应用仅通过 Apple 官方 `HealthKit` 框架在设备端读取与写入以下三类数据：
     - 心率 (`HKQuantityTypeIdentifierHeartRate`)：读取睡眠与冥想期间的心率表现以评估自主神经恢复度；
     - 睡眠分析 (`HKCategoryTypeIdentifierSleepAnalysis`)：将完成的夜间睡眠阶段与卧床时长同步写入系统“健康”应用，或读取历史睡眠时长作本地恢复趋势参考；
     - 正念训练 (`HKCategoryTypeIdentifierMindfulSession`)：将完成的冥想呼吸、4-7-8 助眠呼吸与 0.1Hz 共振呼吸时长写入系统“健康”应用的正念分钟数。
   - **Apple HealthKit 专项合规承诺（Guideline 5.1.1）**：
     - 所有通过 `HealthKit` 读取或生成的健康数据仅在您的设备本地用于睡眠质量展示与恢复评估；
     - **我们绝不将任何 `HealthKit` 数据用于广告宣传、精准营销、用户画像或基于使用行为的数据挖掘；**
     - **我们绝不向任何广告平台、数据经纪商或任何第三方出售、共享、披露或传输您的 `HealthKit` 数据。**

5. **后台音频播放 (`UIBackgroundModes: audio`) 与相册保存 (`NSPhotoLibraryAddUsageDescription`)**：
   - **后台音频**：确保您在锁屏息屏或切换至系统桌面后，仍能不间断聆听 48kHz 脑波双耳节拍、自然白噪音助眠声景、呼吸引导脉冲与智能唤醒轻音。
   - **相册写入**：仅在您主动点击“保存睡眠报告海报至相册”时向系统相册写入生成的分享图片，绝不读取您相册中的任何已有照片。

### 2. 应用内购买与会员订阅 (SomnoPod Pro)
- 本应用内的 `眠舱 Pro (SomnoPod Pro)` 会员服务——包括月度自动续期订阅 (`com.somnopod.pro.monthly`)、年度自动续期订阅 (`com.somnopod.pro.yearly`) 及终身买断版 (`com.somnopod.pro.lifetime`)——均 **100% 通过 Apple 官方 App Store (`StoreKit 2`)** 完成支付与收据核验。
- 我们无法也不会收集您的 Apple ID 密码、银行卡号或账单地址等敏感支付信息。

### 3. 第三方追踪、广告与数据共享声明
- **零追踪、零广告 SDK**：本应用未集成任何第三方广告 SDK 或跨应用行为追踪组件，不请求广告标识符 (`IDFA` / `NSUserTrackingUsageDescription`)，不与任何第三方共享个人数据。
- **儿童隐私保护**：本应用不针对儿童收集任何个人身份信息；因所有数据仅保存在设备本地，任何年龄段用户的信息均不会离开本机。

### 4. 您的数据控制权、权限撤回与一键彻底擦除
- **随时撤回权限**：您可随时在 `iOS 设置 -> 隐私与安全性` 或 `健康 -> 数据访问与设备` 中关闭麦克风、运动与健身、蓝牙或 Apple Health 读写授权。关闭后，48kHz 脑波白噪音播放与冥想计时等核心功能依然正常可用。
- **一键销毁全部本地数据**：您可随时在应用内 **“设置 -> 隐私与数据管理 -> 一键清除所有本地睡眠记录与音频片段”**（或直接卸载本应用），立即且不可逆地彻底销毁保存在手机本地的所有睡眠账本、高光音频片段与个人偏好配置。

### 5. 非医疗器械免责声明 (Apple Guideline 1.4.1 Medical Disclaimer)
> **重要健康提示**：**眠舱 (SomnoPod)** 仅用于日常睡眠环境声景助眠、正念呼吸放松训练及个人睡眠习惯记录参考。**本应用不属于医疗器械（Not a Medical Device）**，其提供的睡眠分期估算、鼾声包络记录、呼吸节律及心率/HRV 压力恢复指标**不能替代专业多导睡眠监测 (PSG) 或临床医学诊断**，亦不用于诊断、治疗、治愈或预防阻塞性睡眠呼吸暂停综合征 (OSA)、临床失眠症、心律失常或任何其他疾病。如您存在睡眠呼吸暂停风险、严重睡眠障碍或任何身体不适，或在做出任何医疗决定前，请务必咨询执业医师或合格医疗专业人士。

### 6. 联系我们
如您对本隐私政策或本地数据处理机制有任何疑问、建议或投诉，请随时联系我们：
- **联系邮箱**：[fly699@gmail.com](mailto:fly699@gmail.com)
- **官方技术支持页面**：[https://github.com/fly699/i2cdevlib/blob/somnopod-legal/SUPPORT.md](https://github.com/fly699/i2cdevlib/blob/somnopod-legal/SUPPORT.md)

---

## 二、English Privacy Policy

Welcome to **SomnoPod (眠舱) — Sleep Sounds, Brainwave White Noise, Bedside Sleep Tracker & Mindful Breathing** ("the App", Bundle IDs: `com.somnopod.sleep.ios`, `com.somnopod.sleep.global`, `com.somnopod.sleep.china`). Your privacy is foundational to SomnoPod. In full compliance with **Apple App Review Guideline 5.1.1**, SomnoPod is built on **Zero Account Registration, 100% Local On-Device Storage, Zero Ad Tracking, and Zero Cloud Audio Uploads**.

### 1. Data & Permissions Processed Exclusively On-Device

SomnoPod requires **no sign-up or cloud account**. All sensor processing, sleep logs, and settings stay **100% inside your iPhone's local app sandbox**:

1. **Microphone Acoustic Breathing/Snore Envelope & Local-Only Optional Highlight Clips (`NSMicrophoneUsageDescription`)**:
   - **Purpose**: When you start bedside sleep tracking and grant microphone access, SomnoPod analyzes real-time acoustic sound pressure envelopes (RMS), breathing rhythm cadence, and snore/sleep-talk events strictly on your device to adapt 48kHz sleep soundscapes and estimate sleep quality.
   - **Local-Only Optional Highlight Clip Storage**: If you opt in to saving sleep highlight clips (e.g., snoring or sleep talking), short audio snippets are stored **100% locally in your device's private app sandbox** solely for your personal morning review, and can be deleted individually or wiped at any time. When highlight clip capture is turned off, acoustic envelope analysis occurs strictly in volatile RAM without writing audio files to disk.
   - **Strict Zero-Upload Guarantee**: **Audio streams, acoustic envelopes, and optional highlight clips are NEVER uploaded, transmitted, or synced to any developer server or third-party cloud.**

2. **Motion, Accelerometer, Barometer & Proximity Sensors (`NSMotionUsageDescription` / `CoreMotion` / `CMAltimeter` / Proximity)**:
   - **Purpose**: Used locally while your iPhone rests at your bedside to detect mattress micro-vibrations, sleep posture turnovers, ambient barometric micro-fluctuations, and face-down proximity screen dimming, enabling contactless breathing rhythm and restlessness estimation.
   - **Storage**: Processed locally in real time; summarized sleep metrics remain strictly on your device.

3. **Bluetooth LE 0x180D Heart Rate Sensors (`NSBluetoothAlwaysUsageDescription` / `CoreBluetooth`)**:
   - **Purpose**: Used only when initiated by you to scan and connect to standard **Bluetooth Low Energy (`0x180D`) heart rate chest straps, armbands, or wristbands** for real-time resting heart rate, HRV autonomic stress/recovery scoring, and coherent breathing biofeedback.

4. **Apple HealthKit Read & Write Permissions (`NSHealthShareUsageDescription` / `NSHealthUpdateUsageDescription`)**:
   - **Data Types Accessed**: Only with your explicit permission in Apple Health, SomnoPod reads and/or writes:
     - `HKQuantityTypeIdentifierHeartRate` (Heart Rate during sleep & relaxation sessions);
     - `HKCategoryTypeIdentifierSleepAnalysis` (Sleep stages and time asleep/in bed);
     - `HKCategoryTypeIdentifierMindfulSession` (Mindful breathing and meditation minutes).
   - **Strict HealthKit Privacy Commitment**: HealthKit data is processed exclusively on your device for personal wellness insights. **SomnoPod strictly NEVER uses HealthKit data for advertising, marketing, user profiling, or use-based data mining, and NEVER sells, shares, or discloses HealthKit data to any third parties or data brokers.**

5. **In-App Purchases & Subscriptions (`StoreKit 2`)**:
   - All **SomnoPod Pro** purchases (`com.somnopod.pro.monthly`, `com.somnopod.pro.yearly`, `com.somnopod.pro.lifetime`) are processed directly by Apple via StoreKit 2. We never access your credit card or billing details.

6. **Zero Tracking & Complete Local Data Control**:
   - SomnoPod contains **zero third-party analytics or ad SDKs** and never requests `IDFA`. You can revoke any system permission in iOS Settings or permanently erase all local sleep logs and highlight clips anytime inside **Settings -> Privacy & Data -> Erase All Local Data** (or by uninstalling the App).

### 2. Non-Medical Device Disclaimer (Apple Guideline 1.4.1)
> **Medical Disclaimer**: **SomnoPod** is intended solely for general wellness, relaxation soundscapes, mindful breathing exercises, and personal sleep habit awareness. **SomnoPod is NOT a medical device** and is not intended to diagnose, treat, cure, or prevent any disease or medical condition (including obstructive sleep apnea, clinical insomnia, or cardiac disorders). All sleep stage, snore envelope, respiratory rhythm, and heart rate/HRV metrics are for informational wellness reference only and are not a substitute for clinical polysomnography or professional medical advice. Always seek the advice of a physician or other qualified healthcare provider with any questions regarding a medical condition or before making any medical decisions.

### 3. Contact Us
If you have any questions about privacy or data protection, please contact us at:
- **Email**: [fly699@gmail.com](mailto:fly699@gmail.com)
- **Support Page**: [https://github.com/fly699/i2cdevlib/blob/somnopod-legal/SUPPORT.md](https://github.com/fly699/i2cdevlib/blob/somnopod-legal/SUPPORT.md)

---

## 三、日本語プライバシーポリシー (Japanese Privacy Policy)

**SomnoPod（眠艙：脳波ホワイトノイズ睡眠導入・睡眠記録・瞑想呼吸）**（対象バンドルID：`com.somnopod.sleep.ios` / `com.somnopod.sleep.global` / `com.somnopod.sleep.china`、以下「本アプリ」）は、Apple App Review ガイドライン 5.1.1 を厳格に遵守し、**「アカウント登録不要・100%端末内ローカル処理・広告トラッキングゼロ・音声データのクラウド送信ゼロ」**の設計原則に基づいています。

### 1. 端末内で処理される権限とデータ（100% ローカル保存）

1. **マイクによる呼吸・いびき音響包絡線解析およびローカル限定のハイライト音声保存 (`NSMicrophoneUsageDescription`)**：
   - 睡眠モニタリング中、マイク入力を用いて端末内でリアルタイムに音圧包絡線（RMS）や呼吸リズム・いびきイベントを解析し、48kHz 睡眠サウンドの自動調整および睡眠ステージ推定を行います。
   - **ローカル限定の任意クリップ保存**：ユーザーが「ハイライト音声のローカル保存」を有効にした場合のみ、短い音声クリップがお使いの iPhone 内のアプリ専用サンドボックス領域に**ローカル保存**されます（いつでも個別に削除または一括消去可能）。オフの場合は揮発性メモリ（RAM）内でのみ処理されます。**いかなる場合も、音声データや音響データが外部サーバーへアップロード・送信されることは一切ありません。**

2. **モーション・加速度センサー・気圧計・近接センサー (`CoreMotion` / `CMAltimeter` / 近接センサー)**：
   - 枕元に置いた iPhone から寝返り・体動・マットレスの微細振動および気圧変化を端末内で解析し、非装着での睡眠姿勢・呼吸リズム推定および伏せ置き時の画面消灯省電力制御にのみ使用します。

3. **Bluetooth LE (0x180D) 心拍センサー連携 ＆ Apple ヘルスケア (`HealthKit`) 読み書き権限**：
   - **Bluetooth (`CoreBluetooth`)**：標準 BLE `0x180D` 心拍計（チェストストラップ・アームバンド等）と接続し、心拍数および HRV（心拍変動）ストレス回復指標をリアルタイム表示するためにのみ使用します。
   - **Apple ヘルスケア (`HealthKit`)**：ユーザーの明示的な許可に基づき、心拍数（`HKQuantityTypeIdentifierHeartRate`）、睡眠分析（`HKCategoryTypeIdentifierSleepAnalysis`）、マインドフルネス時間（`HKCategoryTypeIdentifierMindfulSession`）の読み取りおよび書き込みを端末内で行います。**HealthKit から取得したデータを広告・マーケティング・プロファイリングに使用したり、第三者やデータブローカーに販売・共有・開示したりすることは一切ありません。**

4. **アプリ内課金・サブスクリプション (`StoreKit 2`) ＆ データ消去**：
   - `SomnoPod Pro`（月額 `com.somnopod.pro.monthly`、年額 `com.somnopod.pro.yearly`、買い切り `com.somnopod.pro.lifetime`）の決済はすべて Apple 公式 StoreKit 2 を通じて安全に処理されます。アプリ内の設定からいつでも全ローカルデータと保存クリップを一括消去できます。

### 2. 非医療機器に関する免責事項（Apple Guideline 1.4.1）
> **医療免責事項**：**SomnoPod** は一般的なリラクゼーション、快眠サウンド再生、呼吸瞑想ガイドおよび個人の睡眠習慣の記録のみを目的としたウェルネスアプリであり、**医療機器ではありません**。睡眠無呼吸症候群、不眠症、不整脈その他の疾病の診断・治療・予防を目的としたものではありません。健康上の懸念がある場合や医療上の判断を行う前には、必ず医師または医療専門家にご相談ください。

### 3. お問い合わせ
プライバシーポリシーに関するご質問は、以下までご連絡ください：
- **メールアドレス**：[fly699@gmail.com](mailto:fly699@gmail.com)
- **公式サポートページ**：[https://github.com/fly699/i2cdevlib/blob/somnopod-legal/SUPPORT.md](https://github.com/fly699/i2cdevlib/blob/somnopod-legal/SUPPORT.md)
