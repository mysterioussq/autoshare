# SPAMSHARE - Facebook Auto Share Tool

**Professional Facebook auto-sharing tool for Termux/Linux**

---

## Features

- ✅ Accurate interval timing (0.5s - 10s)
- ✅ Philippine timezone (12-hour format)
- ✅ Beautiful terminal UI
- ✅ Real-time statistics
- ✅ Cookie authentication

---

## Requirements

- Python 3.7+
- Termux (Android) or Linux

---

## Installation (Termux)

```bash
pkg update && pkg install python git -y
git clone https://github.com/YOUR_USERNAME/spamshare.git
cd spamshare
pip install rich requests pytz --break-system-packages
python autoshare.py
```

---

## Installation (Linux)

```bash
sudo apt update && sudo apt install python3 python3-pip git -y
git clone https://github.com/YOUR_USERNAME/spamshare.git
cd spamshare
pip3 install rich requests pytz
python3 autoshare.py
```

---

## How to Use

### 1. Get Facebook Cookie

**Using Kiwi Browser:**
1. Install Kiwi Browser + Cookie Editor extension
2. Login to Facebook
3. Open Cookie Editor
4. Copy full cookie string

### 2. Run Tool

```bash
python autoshare.py
```

### 3. Enter Details

```
ENTER COOKIE: [paste cookie]
POST LINK: https://facebook.com/post/123
AMOUNT: 50
DELAY: 1
```

### 4. Monitor Progress

```
02:30:15 PM #001 ✓ SHARED ➜ 100485858557
02:30:16 PM #002 ✓ SHARED ➜ 200596969668
...

SUMMARY
TOTAL   » 50
SUCCESS » 48
FAILED  » 2
```

---

## Troubleshooting

**Missing modules:**
```bash
pip install rich requests pytz --break-system-packages
```

**Invalid cookie:**
- Get fresh cookie from Kiwi Browser
- Copy full cookie string

**Sharing blocked:**
- Increase delay time
- Reduce amount

---

## Legal Notice

⚠️ **Educational purposes only**
- Violates Facebook TOS
- May result in account ban
- Use at your own risk
- Author not responsible for misuse

**Philippine Laws:** RA 10175, RA 8484

---

## Author

**SIEGFRIED SAMÁ**
- GitHub: [@mysteriousq](https://github.com/mysteriousq)
- Facebook: [mysterioussq](https://facebook.com/mysterioussq)

---

## License

MIT License - See LICENSE file

---

**© 2026 SIEGFRIED SAMÁ**
