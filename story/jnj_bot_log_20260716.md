# JNJ 자동매수 봇 구동 로그 (2026-07-16)

존슨앤존슨(JNJ) 자동 매수 봇의 가동 및 거래 감시 로그 기록입니다.

## 구동 현황 요약
* **대상 종목**: 존슨앤존슨 (JNJ)
* **매수 조건**: 미국 정규장 운영 시간 내 시가 대비 5% 이상 하락 시 $4.00 분할 매수
* **구동 모드**: 🚀 실전 투자 (REAL)
* **상태**: 정상 가동 및 장외 대기 중 (다음 장 시작: 2026-07-16 22:30 KST)

## 전체 로그 내용
```text
/Users/kimseonjoy/joy-seonjeong/dobby-project/trading/.venv/lib/python3.9/site-packages/urllib3/__init__.py:35: NotOpenSSLWarning: urllib3 v2 only supports OpenSSL 1.1.1+, currently the 'ssl' module is compiled with 'LibreSSL 2.8.3'. See: https://github.com/urllib3/urllib3/issues/3020
  warnings.warn(
============================================================
 🤖 JNJ 모멘텀 자동 매수 프로그램 가동 시작
  - 구동 모드: 🚀 실전 투자 (REAL)
============================================================
💾 상태 저장 완료: {'last_buy_date': None, 'open_price': None, 'open_price_date': None, 'last_checked_hour': 0}
💤 장외 대기 중... (현재 KST: 22:23:14, 다음 장 시작: 2026-07-14 22:30)
💾 상태 저장 완료: {'last_buy_date': None, 'open_price': None, 'open_price_date': None, 'last_checked_hour': 0}
... (중략) ...
⏰ 정규장 구동 중... (KST: 22:42:35)
⏰ 정규장 구동 중... (KST: 22:42:45)
⏰ 정규장 구동 중... (KST: 22:42:55)
⏰ 정규장 구동 중... (KST: 22:43:05)
⏰ 정규장 구동 중... (KST: 22:43:15)
⏰ 정규장 구동 중... (KST: 22:43:25)
⏰ 정규장 구동 중... (KST: 22:43:35)
Traceback (most recent call last):
  File "/Users/kimseonjoy/joy-seonjeong/dobby-project/trading/jnj_momentum_buyer.py", line 7, in <module>
    import requests
ModuleNotFoundError: No module named 'requests'
/Users/kimseonjoy/joy-seonjeong/dobby-project/trading/.venv/lib/python3.9/site-packages/urllib3/__init__.py:35: NotOpenSSLWarning: urllib3 v2 only supports OpenSSL 1.1.1+, currently the 'ssl' module is compiled with 'LibreSSL 2.8.3'. See: https://github.com/urllib3/urllib3/issues/3020
  warnings.warn(
============================================================
 🤖 JNJ 모멘텀 자동 매수 프로그램 가동 시작
  - 구동 모드: 🚀 실전 투자 (REAL)
============================================================
⏰ 정규장 구동 중... (KST: 22:43:50)
... (중략) ...
⏰ 정규장 구동 중... (KST: 22:45:40)
/Users/kimseonjoy/joy-seonjeong/dobby-project/trading/.venv/lib/python3.9/site-packages/urllib3/__init__.py:35: NotOpenSSLWarning: urllib3 v2 only supports OpenSSL 1.1.1+, currently the 'ssl' module is compiled with 'LibreSSL 2.8.3'. See: https://github.com/urllib3/urllib3/issues/3020
  warnings.warn(
============================================================
 🤖 JNJ 모멘텀 자동 매수 프로그램 가동 시작
  - 구동 모드: 🚀 실전 투자 (REAL)
============================================================
⏰ 정규장 구동 중... (KST: 22:45:51)
💤 다음 감시 예정 시각: 23:30:10 (약 2658초 대기)
⏰ 정규장 구동 중... (KST: 23:30:07)
📊 장 시작 후 1시간 경과 감시 작동
🔍 [1시간째 감시] 시가: $255.53 | 현재가: $253.80 (변동률: -0.68%)
💾 상태 저장 완료: {'last_buy_date': None, 'open_price': 255.53, 'open_price_date': '2026-07-14', 'last_checked_hour': 1}
ℹ️ 하락률(-0.68%)이 기준치(-5.00%)에 미달하여 매수를 보류합니다.
💤 다음 감시 예정 시각: 00:30:10 (약 3602초 대기)
/Users/kimseonjoy/joy-seonjeong/dobby-project/trading/.venv/lib/python3.9/site-packages/urllib3/__init__.py:35: NotOpenSSLWarning: urllib3 v2 only supports OpenSSL 1.1.1+, currently the 'ssl' module is compiled with 'LibreSSL 2.8.3'. See: https://github.com/urllib3/urllib3/issues/3020
  warnings.warn(
============================================================
 🤖 JNJ 모멘텀 자동 매수 프로그램 가동 시작
  - 구동 모드: 🚀 실전 투자 (REAL)
============================================================
⏰ 정규장 구동 중... (KST: 23:41:28)
🔍 금일 시가 획득 시도 중...
💾 상태 저장 완료: {'last_buy_date': None, 'open_price': 250.0, 'open_price_date': '2026-07-15', 'last_checked_hour': 0}
📢 [Telegram] 📈 금일 JNJ 정규장 시가 획득 완료: $250.00
📊 장 시작 후 1시간 경과 감시 작동
🔍 [1시간째 감시] 시가: $250.00 | 현재가: $253.34 (변동률: +1.34%)
💾 상태 저장 완료: {'last_buy_date': None, 'open_price': 250.0, 'open_price_date': '2026-07-15', 'last_checked_hour': 1}
ℹ️ 하락률(1.34%)이 기준치(-5.00%)에 미달하여 매수를 보류합니다.
💤 다음 감시 예정 시각: 00:30:10 (약 2921초 대기)
💾 상태 저장 완료: {'last_buy_date': None, 'open_price': None, 'open_price_date': None, 'last_checked_hour': 0}
💤 장외 대기 중... (현재 KST: 00:30:09, 다음 장 시작: 2026-07-16 22:30, 약 1800초 대기)
💾 상태 저장 완료: {'last_buy_date': None, 'open_price': None, 'open_price_date': None, 'last_checked_hour': 0}
💤 장외 대기 중... (현재 KST: 01:00:09, 다음 장 시작: 2026-07-16 22:30, 약 1800초 대기)
... (중략) ...
💤 장외 대기 중... (현재 KST: 09:00:09, 다음 장 시작: 2026-07-16 22:30, 약 1800초 대기)
/Users/kimseonjoy/joy-seonjeong/dobby-project/trading/.venv/lib/python3.9/site-packages/urllib3/__init__.py:35: NotOpenSSLWarning: urllib3 v2 only supports OpenSSL 1.1.1+, currently the 'ssl' module is compiled with 'LibreSSL 2.8.3'. See: https://github.com/urllib3/urllib3/issues/3020
  warnings.warn(
============================================================
 🤖 JNJ 모멘텀 자동 매수 프로그램 가동 시작
  - 구동 모드: 🚀 실전 투자 (REAL)
============================================================
💾 상태 저장 완료: {'last_buy_date': None, 'open_price': None, 'open_price_date': None, 'last_checked_hour': 0}
💤 장외 대기 중... (현재 KST: 09:15:08, 다음 장 시작: 2026-07-16 22:30, 약 1800초 대기)
```
