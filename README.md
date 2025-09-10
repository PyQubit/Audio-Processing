# 🔊 Advanced Audio Processing with Deep Learning | پردازش پیشرفته صدا با یادگیری عمیق  

یک پروژه **پیشرفته** در زمینه‌ی **پردازش سیگنال‌های صوتی** با استفاده از **شبکه‌های عصبی (LSTM / CNN / RNN)** روی داده‌های صوتی.  
An **advanced project** for **audio signal processing** using **deep learning models (LSTM / CNN / RNN)** on audio datasets.  

---

## 👤 Developer | توسعه‌دهنده  

* **Mohammad Mahdi Omidvar (PyQubit)** | **محمد مهدی امیدوار**  

---

## 🚀 Features | قابلیت‌ها  

* 🎙️ **Audio recording & advanced preprocessing** | ضبط و پیش‌پردازش پیشرفته صدا  
* 🔎 **Feature extraction (MFCC, Spectrogram, Mel-Spectrogram)** | استخراج ویژگی‌ها (MFCC، طیف‌نگار، Mel-Spectrogram)  
* 🧠 **Deep learning models (LSTM / CNN / Hybrid RNN)** | آموزش مدل‌های یادگیری عمیق (LSTM، CNN، مدل‌های ترکیبی)  
* 🗣️ **Speech recognition & audio classification** | شناسایی گفتار و طبقه‌بندی صدا  
* 📂 **Pretrained model loading with `model.load_weights('model.h5')`** | بارگذاری مدل از فایل `model.h5` بدون نیاز به آموزش دوباره  
* 📊 **Visualization with Matplotlib & Seaborn** | نمایش و تحلیل نتایج با Matplotlib و Seaborn  

---

## ⚙️ Requirements | پیش‌نیازها  

⚠️ **Important:** Use **Python 3.8.8** for full compatibility  
⚠️ **توجه:** حتما از **Python 3.8.8** استفاده کنید تا با کتابخانه‌ها سازگاری کامل داشته باشد  

### Install required libraries | نصب کتابخانه‌ها  

```bash
pip install tensorflow keras numpy matplotlib seaborn pyaudio wave librosa
```

---

## 🎙️ Dataset | دیتاست  

### Files to Download | فایل‌های موردنیاز  

* `down.zip`  
* `go.zip`  
* `left.zip`  
* `no.zip`  
* `right.zip`  
* `stop.zip`  
* `up.zip`  
* `yes.zip`  

### Instructions | دستورالعمل‌ها  

📂 **Step 1:** Extract all the above `.zip` files  
📂 **مرحله ۱:** تمام فایل‌های `.zip` بالا را از حالت فشرده خارج کنید  

📁 **Step 2:** Create a folder named `Data1/` in the project root  
📁 **مرحله ۲:** یک پوشه با نام `Data1/` در مسیر اصلی پروژه بسازید  

📥 **Step 3:** Move all extracted audio files into `Data1/`  
📥 **مرحله ۳:** تمام فایل‌های استخراج‌شده را داخل پوشه `Data1/` بریزید  

✅ Final structure | ساختار نهایی:  

```bash
project/
│
├── Data1/
│   ├── down/
│   ├── go/
│   ├── left/
│   ├── no/
│   ├── right/
│   ├── stop/
│   ├── up/
│   └── yes/
│
├── model.h5
└── Audio.ipynb
```

---

## 📊 Results | نتایج  

* ✅ **Trained model on audio samples** | آموزش مدل روی نمونه‌های صوتی  
* ⚡ **Fast inference using `model.h5` weights** | اجرای سریع با بارگذاری وزن‌های ذخیره‌شده  
* 📈 **Evaluation on test set** | ارزیابی روی داده‌های تست  
* 🌌 **Visualization of spectrograms & extracted features** | نمایش طیف‌نگارها و ویژگی‌های صوتی استخراج‌شده  

---

## 🐞 Debugging | رفع خطا  

* ⚠️ If you encounter microphone or driver issues, reinstall `pyaudio`.  
  در صورت بروز مشکل میکروفون یا درایور صدا، کتابخانه `pyaudio` را دوباره نصب کنید.  
* ⚠️ Common error: `OSError: [Errno -9996] Invalid input device` → check your audio input settings.  
  خطای رایج: `OSError: [Errno -9996] Invalid input device` → ورودی میکروفون خود را بررسی کنید.  

---

## 📝 How to Use | نحوه اجرا  

1. **Clone the repository** | ریپازیتوری را کلون کنید  
2. **Install dependencies** | پیش‌نیازها را نصب کنید  
3. **Prepare dataset inside `Data1/` folder** | دیتاست را داخل پوشه `Data1/` قرار دهید  
4. **Put `model.h5` in the project root** | فایل `model.h5` را در مسیر اصلی پروژه قرار دهید  
5. **Run the Jupyter notebook** | اجرای نوت‌بوک برای تست مدل  

```bash
jupyter notebook Audio.ipynb
```

---

## 🌐 Connect with Me | ارتباط با من  

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white&style=for-the-badge)](https://instagram.com/PyQubit)  
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?logo=telegram&logoColor=white&style=for-the-badge)](https://t.me/PyQubit)  
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=for-the-badge)](mailto:pyqubit@gmail.com)  

---

© 2025 Mohammad Mahdi Omidvar (PyQubit). All Rights Reserved.  
