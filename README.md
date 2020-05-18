# hashcat-benchmark-2080ti
Hashcat benchmark 2080ti

hashcat (v5.1.0-1774-gf96594ef) starting in benchmark mode...

Benchmarking uses hand-optimized kernel code by default.
You can use it in your cracking session by setting the -O option.
Note: Using optimized kernel code limits the maximum supported password length.
To disable the optimized kernel code in benchmark mode, use the -w option.

CUDA API (CUDA 11.0)
====================
* Device #1: GeForce RTX 2080 Ti, 9248/11264 MB, 68MCU
* Device #2: GeForce RTX 2080 Ti, 9248/11264 MB, 68MCU

OpenCL API (OpenCL 1.2 CUDA 11.0.140) - Platform #1 [NVIDIA Corporation]
========================================================================
* Device #3: GeForce RTX 2080 Ti, skipped
* Device #4: GeForce RTX 2080 Ti, skipped

Benchmark relevant options:
===========================
* --benchmark-all
* --optimized-kernel-enable

Hashmode: 0 - MD5

Speed.#1.........: 64066.5 MH/s (35.28ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 55549.9 MH/s (40.82ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........:   119.6 GH/s

Hashmode: 10 - md5($pass.$salt)

Speed.#1.........: 63689.9 MH/s (35.48ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 53976.2 MH/s (42.01ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........:   117.7 GH/s

Hashmode: 11 - Joomla < 2.5.18

Speed.#1.........: 60564.2 MH/s (37.34ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 52008.7 MH/s (43.61ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........:   112.6 GH/s

Hashmode: 12 - PostgreSQL

Speed.#1.........: 60298.5 MH/s (37.50ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 52226.8 MH/s (43.43ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........:   112.5 GH/s

Hashmode: 20 - md5($salt.$pass)

Speed.#1.........: 34296.4 MH/s (66.19ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 29473.5 MH/s (77.14ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........: 63769.9 MH/s

Hashmode: 21 - osCommerce, xt:Commerce

Speed.#1.........: 34091.8 MH/s (66.57ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 29167.1 MH/s (77.97ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........: 63258.9 MH/s

Hashmode: 22 - Juniper NetScreen/SSG (ScreenOS)

Speed.#1.........: 33946.2 MH/s (66.88ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 28939.7 MH/s (78.58ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........: 62885.9 MH/s

Hashmode: 23 - Skype

Speed.#1.........: 34119.6 MH/s (66.54ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 29530.2 MH/s (77.00ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........: 63649.8 MH/s

Hashmode: 30 - md5(utf16le($pass).$salt)

Speed.#1.........: 62108.0 MH/s (36.39ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 53234.2 MH/s (42.57ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........:   115.3 GH/s

Hashmode: 40 - md5($salt.utf16le($pass))

Speed.#1.........: 34022.5 MH/s (66.72ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 29379.2 MH/s (77.41ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........: 63401.7 MH/s

Hashmode: 50 - HMAC-MD5 (key = $pass)

Speed.#1.........:  9891.5 MH/s (57.32ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  8564.8 MH/s (66.32ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 18456.3 MH/s

Hashmode: 60 - HMAC-MD5 (key = $salt)

Speed.#1.........: 21432.7 MH/s (52.89ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 18652.4 MH/s (60.91ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 40085.0 MH/s

Hashmode: 100 - SHA1

Speed.#1.........: 20078.4 MH/s (56.48ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 17383.8 MH/s (65.37ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 37462.2 MH/s

Hashmode: 101 - nsldap, SHA-1(Base64), Netscape LDAP SHA

Speed.#1.........: 20103.7 MH/s (56.41ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 17379.7 MH/s (65.38ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 37483.4 MH/s

Hashmode: 110 - sha1($pass.$salt)

Speed.#1.........: 20247.0 MH/s (56.00ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 17501.6 MH/s (64.92ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 37748.6 MH/s

Hashmode: 111 - nsldaps, SSHA-1(Base64), Netscape LDAP SSHA

Speed.#1.........: 20062.4 MH/s (56.52ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 17360.0 MH/s (65.46ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 37422.4 MH/s

Hashmode: 112 - Oracle S: Type (Oracle 11+)

Speed.#1.........: 20205.7 MH/s (56.12ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 17571.1 MH/s (64.67ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 37776.8 MH/s

Hashmode: 120 - sha1($salt.$pass)

Speed.#1.........: 15461.0 MH/s (73.45ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 13292.5 MH/s (85.56ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 28753.5 MH/s

Hashmode: 121 - SMF (Simple Machines Forum) > v1.1

Speed.#1.........: 15448.5 MH/s (73.51ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 13278.9 MH/s (85.67ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 28727.4 MH/s

Hashmode: 122 - macOS v10.4, macOS v10.5, MacOS v10.6

Speed.#1.........: 15391.1 MH/s (73.78ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 13271.9 MH/s (85.70ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 28663.0 MH/s

Hashmode: 124 - Django (SHA-1)

Speed.#1.........: 15417.5 MH/s (73.65ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 13253.8 MH/s (85.82ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 28671.3 MH/s

Hashmode: 125 - ArubaOS

Speed.#1.........: 15413.1 MH/s (73.68ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 13258.7 MH/s (85.80ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 28671.8 MH/s

Hashmode: 130 - sha1(utf16le($pass).$salt)

Speed.#1.........: 20205.9 MH/s (56.12ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 17512.2 MH/s (64.89ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 37718.1 MH/s

Hashmode: 131 - MSSQL (2000)

Speed.#1.........: 20192.3 MH/s (56.16ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 17392.7 MH/s (65.33ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 37585.0 MH/s

Hashmode: 132 - MSSQL (2005)

Speed.#1.........: 20226.7 MH/s (56.07ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 17398.8 MH/s (65.32ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 37625.5 MH/s

Hashmode: 133 - PeopleSoft

Speed.#1.........: 20040.0 MH/s (56.59ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 17287.2 MH/s (65.74ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 37327.2 MH/s

Hashmode: 140 - sha1($salt.utf16le($pass))

Speed.#1.........: 15389.2 MH/s (73.79ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 13160.3 MH/s (86.44ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 28549.5 MH/s

Hashmode: 141 - Episerver 6.x < .NET 4

Speed.#1.........: 15401.1 MH/s (73.74ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 13253.5 MH/s (85.82ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 28654.6 MH/s

Hashmode: 150 - HMAC-SHA1 (key = $pass)

Speed.#1.........:  4382.0 MH/s (64.75ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  3805.9 MH/s (74.64ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  8188.0 MH/s

Hashmode: 160 - HMAC-SHA1 (key = $salt)

Speed.#1.........:  8481.2 MH/s (66.92ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  7442.1 MH/s (76.39ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 15923.3 MH/s

Hashmode: 200 - MySQL323

Speed.#1.........:   177.1 GH/s (12.49ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........:   155.6 GH/s (14.41ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........:   332.7 GH/s

Hashmode: 300 - MySQL4.1/MySQL5

Speed.#1.........:  8696.0 MH/s (65.25ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  7589.3 MH/s (74.91ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 16285.3 MH/s

Hashmode: 400 - phpass (Iterations: 2048)

Speed.#1.........: 16385.3 kH/s (65.36ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 14620.4 kH/s (73.68ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 31005.7 kH/s

Hashmode: 500 - md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5) (Iterations: 1000)

Speed.#1.........: 27436.3 kH/s (76.83ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1
Speed.#2.........: 24087.8 kH/s (88.34ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1
Speed.#*.........: 51524.1 kH/s

Hashmode: 501 - Juniper IVE (Iterations: 1000)

Speed.#1.........: 27511.4 kH/s (76.62ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1
Speed.#2.........: 23828.7 kH/s (89.26ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1
Speed.#*.........: 51340.1 kH/s

Hashmode: 600 - BLAKE2b-512

Speed.#1.........:  4802.9 MH/s (59.05ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:  4243.9 MH/s (66.95ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  9046.7 MH/s

Hashmode: 900 - MD4

Speed.#1.........:   114.2 GH/s (19.60ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 99654.1 MH/s (22.63ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........:   213.9 GH/s

Hashmode: 1000 - NTLM

Speed.#1.........:   113.8 GH/s (19.73ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 99643.9 MH/s (22.65ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........:   213.5 GH/s

Hashmode: 1100 - Domain Cached Credentials (DCC), MS Cache

Speed.#1.........: 30583.1 MH/s (74.27ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 26539.1 MH/s (85.71ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........: 57122.2 MH/s

Hashmode: 1300 - SHA2-224

Speed.#1.........:  8418.0 MH/s (67.43ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  7264.2 MH/s (78.27ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 15682.1 MH/s

Hashmode: 1400 - SHA2-256

Speed.#1.........:  8636.5 MH/s (65.71ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  7458.4 MH/s (76.23ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 16094.9 MH/s

Hashmode: 1410 - sha256($pass.$salt)

Speed.#1.........:  8624.8 MH/s (65.80ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  7456.2 MH/s (76.25ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 16081.0 MH/s

Hashmode: 1411 - SSHA-256(Base64), LDAP {SSHA256}

Speed.#1.........:  8635.0 MH/s (65.72ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  7432.6 MH/s (76.49ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 16067.6 MH/s

Hashmode: 1420 - sha256($salt.$pass)

Speed.#1.........:  7734.7 MH/s (73.42ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  6652.7 MH/s (85.49ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 14387.3 MH/s

Hashmode: 1421 - hMailServer

Speed.#1.........:  7731.4 MH/s (73.44ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  6639.5 MH/s (85.65ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 14370.8 MH/s

Hashmode: 1430 - sha256(utf16le($pass).$salt)

Speed.#1.........:  8620.6 MH/s (65.83ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  7454.1 MH/s (76.27ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 16074.7 MH/s

Hashmode: 1440 - sha256($salt.utf16le($pass))

Speed.#1.........:  7737.5 MH/s (73.39ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  6638.2 MH/s (85.68ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 14375.7 MH/s

Hashmode: 1441 - Episerver 6.x >= .NET 4

Speed.#1.........:  7737.9 MH/s (73.37ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  6655.8 MH/s (85.43ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 14393.7 MH/s

Hashmode: 1450 - HMAC-SHA256 (key = $pass)

Speed.#1.........:  1581.4 MH/s (89.82ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#2.........:  1359.9 MH/s (104.59ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  2941.3 MH/s

Hashmode: 1460 - HMAC-SHA256 (key = $salt)

Speed.#1.........:  3602.7 MH/s (78.82ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:  3109.6 MH/s (91.45ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  6712.3 MH/s

Hashmode: 1500 - descrypt, DES (Unix), Traditional DES

Speed.#1.........:  2232.7 MH/s (63.28ms) @ Accel:32 Loops:1024 Thr:64 Vec:1
Speed.#2.........:  1878.9 MH/s (75.44ms) @ Accel:32 Loops:1024 Thr:64 Vec:1
Speed.#*.........:  4111.5 MH/s

Hashmode: 1600 - Apache $apr1$ MD5, md5apr1, MD5 (APR) (Iterations: 1000)

Speed.#1.........: 27378.1 kH/s (77.04ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1
Speed.#2.........: 23794.3 kH/s (89.48ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1
Speed.#*.........: 51172.4 kH/s

Hashmode: 1700 - SHA2-512

Speed.#1.........:  2755.7 MH/s (51.41ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2392.6 MH/s (59.34ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  5148.3 MH/s

Hashmode: 1710 - sha512($pass.$salt)

Speed.#1.........:  2759.8 MH/s (51.33ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2391.8 MH/s (59.38ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  5151.6 MH/s

Hashmode: 1711 - SSHA-512(Base64), LDAP {SSHA512}

Speed.#1.........:  2759.1 MH/s (51.35ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2380.0 MH/s (59.66ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  5139.0 MH/s

Hashmode: 1720 - sha512($salt.$pass)

Speed.#1.........:  2615.1 MH/s (54.19ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2254.3 MH/s (63.01ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  4869.4 MH/s

Hashmode: 1722 - macOS v10.7

Speed.#1.........:  2618.4 MH/s (54.12ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2257.8 MH/s (62.90ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  4876.2 MH/s

Hashmode: 1730 - sha512(utf16le($pass).$salt)

Speed.#1.........:  2754.0 MH/s (51.44ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:  2372.3 MH/s (59.86ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  5126.3 MH/s

Hashmode: 1731 - MSSQL (2012, 2014)

Speed.#1.........:  2759.8 MH/s (51.34ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2382.9 MH/s (59.59ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  5142.6 MH/s

Hashmode: 1740 - sha512($salt.utf16le($pass))

Speed.#1.........:  2617.5 MH/s (54.14ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2253.9 MH/s (63.01ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  4871.4 MH/s

Hashmode: 1750 - HMAC-SHA512 (key = $pass)

Speed.#1.........:   593.6 MH/s (59.72ms) @ Accel:1 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   509.1 MH/s (69.77ms) @ Accel:1 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  1102.7 MH/s

Hashmode: 1760 - HMAC-SHA512 (key = $salt)

Speed.#1.........:  1216.2 MH/s (58.29ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  1053.5 MH/s (67.43ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  2269.7 MH/s

Hashmode: 1800 - sha512crypt $6$, SHA512 (Unix) (Iterations: 5000)

Speed.#1.........:   238.6 kH/s (57.93ms) @ Accel:8 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   250.2 kH/s (55.28ms) @ Accel:8 Loops:128 Thr:1024 Vec:1
Speed.#*.........:   488.8 kH/s

Hashmode: 2000 - STDOUT

Speed.#1.........:  7567.8 GH/s (0.01ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 10302.5 GH/s (0.01ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 17870.3 GH/s

Hashmode: 2100 - Domain Cached Credentials 2 (DCC2), MS Cache 2 (Iterations: 10239)

Speed.#1.........:   802.2 kH/s (69.11ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   695.6 kH/s (79.78ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  1497.8 kH/s

Hashmode: 2400 - Cisco-PIX MD5

Speed.#1.........: 45176.3 MH/s (50.18ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 39122.7 MH/s (58.06ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........: 84298.9 MH/s

Hashmode: 2410 - Cisco-ASA MD5

Speed.#1.........: 45548.0 MH/s (49.76ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 39716.5 MH/s (57.19ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........: 85264.5 MH/s

Hashmode: 2500 - WPA-EAPOL-PBKDF2 (Iterations: 4095)

Speed.#1.........:   995.6 kH/s (69.62ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   865.2 kH/s (80.17ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  1860.8 kH/s

Hashmode: 2501 - WPA-EAPOL-PMK (Iterations: 0)

Speed.#1.........:   359.7 MH/s (0.00ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:   338.5 MH/s (0.00ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:   698.2 MH/s

Hashmode: 2600 - md5(md5($pass))

Speed.#1.........: 17962.0 MH/s (63.18ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 15630.2 MH/s (72.74ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 33592.2 MH/s

Hashmode: 2611 - vBulletin < v3.8.5

Speed.#1.........: 17881.0 MH/s (63.47ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 15546.1 MH/s (73.13ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 33427.1 MH/s

Hashmode: 2612 - PHPS

Speed.#1.........: 17839.1 MH/s (63.62ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 15633.6 MH/s (72.71ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 33472.6 MH/s

Hashmode: 2711 - vBulletin >= v3.8.5

Speed.#1.........: 12586.7 MH/s (90.31ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 10970.4 MH/s (103.73ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 23557.1 MH/s

Hashmode: 2811 - MyBB 1.2+, IPB2+ (Invision Power Board)

Speed.#1.........: 13650.6 MH/s (83.25ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 11857.5 MH/s (95.96ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 25508.0 MH/s

Hashmode: 3000 - LM

Speed.#1.........: 54628.7 MH/s (41.18ms) @ Accel:512 Loops:1024 Thr:64 Vec:1
Speed.#2.........: 46577.6 MH/s (48.54ms) @ Accel:512 Loops:1024 Thr:64 Vec:1
Speed.#*.........:   101.2 GH/s

Hashmode: 3100 - Oracle H: Type (Oracle 7+)

Speed.#1.........:   877.4 MH/s (40.30ms) @ Accel:32 Loops:16 Thr:1024 Vec:1
Speed.#2.........:   739.5 MH/s (47.96ms) @ Accel:32 Loops:16 Thr:1024 Vec:1
Speed.#*.........:  1617.0 MH/s

Hashmode: 3200 - bcrypt $2*$, Blowfish (Unix) (Iterations: 32)

Speed.#1.........:    59244 H/s (35.31ms) @ Accel:2 Loops:32 Thr:16 Vec:1
Speed.#2.........:    49173 H/s (42.89ms) @ Accel:2 Loops:32 Thr:16 Vec:1
Speed.#*.........:   108.4 kH/s

Hashmode: 3710 - md5($salt.md5($pass))

Speed.#1.........: 16723.8 MH/s (67.88ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 14506.6 MH/s (78.38ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 31230.4 MH/s

Hashmode: 3711 - MediaWiki B type

Speed.#1.........: 16715.3 MH/s (67.91ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 14586.8 MH/s (77.94ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 31302.1 MH/s

Hashmode: 3800 - md5($salt.$pass.$salt)

Speed.#1.........: 33818.8 MH/s (67.13ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#2.........: 29445.7 MH/s (77.24ms) @ Accel:32 Loops:1024 Thr:1024 Vec:4
Speed.#*.........: 63264.5 MH/s

Hashmode: 3910 - md5(md5($pass).md5($salt))

Speed.#1.........: 12661.7 MH/s (89.77ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 11065.9 MH/s (102.84ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 23727.5 MH/s

Hashmode: 4010 - md5($salt.md5($salt.$pass))

Speed.#1.........: 14830.9 MH/s (76.59ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 12692.0 MH/s (89.63ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 27522.8 MH/s

Hashmode: 4110 - md5($salt.md5($pass.$salt))

Speed.#1.........: 15871.9 MH/s (71.53ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 13730.9 MH/s (82.83ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 29602.8 MH/s

Hashmode: 4300 - md5(strtoupper(md5($pass)))

Speed.#1.........: 17871.2 MH/s (63.51ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 15552.8 MH/s (73.10ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 33424.0 MH/s

Hashmode: 4400 - md5(sha1($pass))

Speed.#1.........: 10776.8 MH/s (52.59ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  9325.4 MH/s (60.91ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 20102.2 MH/s

Hashmode: 4500 - sha1(sha1($pass))

Speed.#1.........:  7711.3 MH/s (73.63ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  6698.9 MH/s (84.88ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 14410.2 MH/s

Hashmode: 4520 - sha1($salt.sha1($pass))

Speed.#1.........:  4540.3 MH/s (62.48ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  3900.6 MH/s (72.87ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  8440.9 MH/s

Hashmode: 4521 - Redmine

Speed.#1.........:  4530.7 MH/s (62.62ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  3886.5 MH/s (73.12ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  8417.2 MH/s

Hashmode: 4522 - PunBB

Speed.#1.........:  7121.0 MH/s (79.77ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  6161.5 MH/s (92.33ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 13282.5 MH/s

Hashmode: 4700 - sha1(md5($pass))

Speed.#1.........: 11083.9 MH/s (51.13ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  9656.0 MH/s (58.83ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 20739.9 MH/s

Hashmode: 4710 - sha1(md5($pass).$salt)

Speed.#1.........: 10540.5 MH/s (53.78ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  9159.9 MH/s (62.02ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 19700.4 MH/s

Hashmode: 4711 - Huawei sha1(md5($pass).$salt)

Speed.#1.........: 10343.7 MH/s (54.81ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  8979.3 MH/s (63.27ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 19323.0 MH/s

Hashmode: 4800 - iSCSI CHAP authentication, MD5(CHAP)

Speed.#1.........: 43383.0 MH/s (52.26ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 38093.7 MH/s (59.64ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........: 81476.7 MH/s

Hashmode: 4900 - sha1($salt.$pass.$salt)

Speed.#1.........: 15039.5 MH/s (75.52ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 12853.8 MH/s (88.49ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 27893.3 MH/s

Hashmode: 5100 - Half MD5

Speed.#1.........: 38886.3 MH/s (58.34ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 34151.3 MH/s (66.56ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 73037.7 MH/s

Hashmode: 5200 - Password Safe v3 (Iterations: 2049)

Speed.#1.........:  3429.2 kH/s (64.36ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  3001.5 kH/s (73.48ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  6430.6 kH/s

Hashmode: 5300 - IKE-PSK MD5

Speed.#1.........:  2297.3 MH/s (61.74ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2013.4 MH/s (70.58ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  4310.6 MH/s

Hashmode: 5400 - IKE-PSK SHA1

Speed.#1.........:   918.2 MH/s (77.33ms) @ Accel:4 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   783.1 MH/s (90.79ms) @ Accel:4 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  1701.3 MH/s

Hashmode: 5500 - NetNTLMv1 / NetNTLMv1+ESS

Speed.#1.........: 61457.4 MH/s (36.79ms) @ Accel:32 Loops:1024 Thr:1024 Vec:2
Speed.#2.........: 53177.4 MH/s (42.65ms) @ Accel:32 Loops:1024 Thr:1024 Vec:2
Speed.#*.........:   114.6 GH/s

Hashmode: 5600 - NetNTLMv2

Speed.#1.........:  4351.9 MH/s (65.20ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  3792.5 MH/s (74.95ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  8144.4 MH/s

Hashmode: 5700 - Cisco-IOS type 4 (SHA256)

Speed.#1.........:  8627.2 MH/s (65.78ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  7448.3 MH/s (76.33ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 16075.5 MH/s

Hashmode: 5800 - Samsung Android Password/PIN (Iterations: 1023)

Speed.#1.........: 13608.3 kH/s (53.00ms) @ Accel:32 Loops:511 Thr:1024 Vec:1
Speed.#2.........: 11841.4 kH/s (61.20ms) @ Accel:32 Loops:511 Thr:1024 Vec:1
Speed.#*.........: 25449.7 kH/s

Hashmode: 6000 - RIPEMD-160

Speed.#1.........: 13248.8 MH/s (85.78ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 11397.1 MH/s (99.86ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 24645.9 MH/s

Hashmode: 6100 - Whirlpool

Speed.#1.........:   667.0 MH/s (53.12ms) @ Accel:8 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   563.2 MH/s (63.05ms) @ Accel:8 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  1230.2 MH/s

Hashmode: 6211 - TrueCrypt RIPEMD160 + XTS 512 bit (Iterations: 1999)

Speed.#1.........:   737.7 kH/s (86.03ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   641.6 kH/s (98.77ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  1379.3 kH/s

Hashmode: 6212 - TrueCrypt RIPEMD160 + XTS 1024 bit (Iterations: 1999)

Speed.#1.........:   455.1 kH/s (77.27ms) @ Accel:32 Loops:32 Thr:1024 Vec:1
Speed.#2.........:   398.0 kH/s (88.30ms) @ Accel:32 Loops:32 Thr:1024 Vec:1
Speed.#*.........:   853.2 kH/s

Hashmode: 6213 - TrueCrypt RIPEMD160 + XTS 1536 bit (Iterations: 1999)

Speed.#1.........:   311.3 kH/s (56.18ms) @ Accel:32 Loops:16 Thr:1024 Vec:1
Speed.#2.........:   273.2 kH/s (64.00ms) @ Accel:32 Loops:16 Thr:1024 Vec:1
Speed.#*.........:   584.5 kH/s

Hashmode: 6221 - TrueCrypt SHA512 + XTS 512 bit (Iterations: 999)

Speed.#1.........:  1065.0 kH/s (51.13ms) @ Accel:8 Loops:124 Thr:1024 Vec:1
Speed.#2.........:   923.1 kH/s (58.95ms) @ Accel:8 Loops:124 Thr:1024 Vec:1
Speed.#*.........:  1988.1 kH/s

Hashmode: 6222 - TrueCrypt SHA512 + XTS 1024 bit (Iterations: 999)

Speed.#1.........:   496.8 kH/s (52.13ms) @ Accel:4 Loops:124 Thr:1024 Vec:1
Speed.#2.........:   430.8 kH/s (60.02ms) @ Accel:4 Loops:124 Thr:1024 Vec:1
Speed.#*.........:   927.6 kH/s

Hashmode: 6223 - TrueCrypt SHA512 + XTS 1536 bit (Iterations: 999)

Speed.#1.........:   327.4 kH/s (77.64ms) @ Accel:4 Loops:124 Thr:1024 Vec:1
Speed.#2.........:   280.8 kH/s (90.34ms) @ Accel:4 Loops:124 Thr:1024 Vec:1
Speed.#*.........:   608.2 kH/s

Hashmode: 6231 - TrueCrypt Whirlpool + XTS 512 bit (Iterations: 999)

Speed.#1.........:    77465 H/s (444.48ms) @ Accel:8 Loops:62 Thr:1024 Vec:1
Speed.#2.........:    65806 H/s (523.28ms) @ Accel:8 Loops:62 Thr:1024 Vec:1
Speed.#*.........:   143.3 kH/s

Hashmode: 6232 - TrueCrypt Whirlpool + XTS 1024 bit (Iterations: 999)

Speed.#1.........:    38483 H/s (446.47ms) @ Accel:8 Loops:31 Thr:1024 Vec:1
Speed.#2.........:    32635 H/s (526.20ms) @ Accel:8 Loops:31 Thr:1024 Vec:1
Speed.#*.........:    71118 H/s

Hashmode: 6233 - TrueCrypt Whirlpool + XTS 1536 bit (Iterations: 999)

Speed.#1.........:    25987 H/s (331.85ms) @ Accel:2 Loops:62 Thr:1024 Vec:1
Speed.#2.........:    21911 H/s (393.61ms) @ Accel:2 Loops:62 Thr:1024 Vec:1
Speed.#*.........:    47898 H/s

Hashmode: 6241 - TrueCrypt RIPEMD160 + XTS 512 bit + boot-mode (Iterations: 999)

Speed.#1.........:  1355.0 kH/s (81.17ms) @ Accel:32 Loops:62 Thr:1024 Vec:1
Speed.#2.........:  1178.5 kH/s (93.33ms) @ Accel:32 Loops:62 Thr:1024 Vec:1
Speed.#*.........:  2533.5 kH/s

Hashmode: 6242 - TrueCrypt RIPEMD160 + XTS 1024 bit + boot-mode (Iterations: 999)

Speed.#1.........:   704.9 kH/s (73.42ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#2.........:   612.7 kH/s (83.95ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#*.........:  1317.6 kH/s

Hashmode: 6243 - TrueCrypt RIPEMD160 + XTS 1536 bit + boot-mode (Iterations: 999)

Speed.#1.........:   469.5 kH/s (52.45ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#2.........:   546.8 kH/s (60.00ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#*.........:  1016.3 kH/s

Hashmode: 6300 - AIX {smd5} (Iterations: 1000)

Speed.#1.........: 27399.8 kH/s (77.03ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1
Speed.#2.........: 23812.7 kH/s (89.49ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1
Speed.#*.........: 51212.5 kH/s

Hashmode: 6400 - AIX {ssha256} (Iterations: 63)

Speed.#1.........: 45000.9 kH/s (42.68ms) @ Accel:32 Loops:63 Thr:1024 Vec:1
Speed.#2.........: 39276.7 kH/s (49.33ms) @ Accel:32 Loops:63 Thr:1024 Vec:1
Speed.#*.........: 84277.6 kH/s

Hashmode: 6500 - AIX {ssha512} (Iterations: 63)

Speed.#1.........: 16553.8 kH/s (39.60ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#2.........: 14319.5 kH/s (45.82ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#*.........: 30873.3 kH/s

Hashmode: 6600 - 1Password, agilekeychain (Iterations: 999)

Speed.#1.........:  8001.4 kH/s (54.12ms) @ Accel:32 Loops:249 Thr:1024 Vec:1
Speed.#2.........:  6906.6 kH/s (62.65ms) @ Accel:32 Loops:249 Thr:1024 Vec:1
Speed.#*.........: 14907.9 kH/s

Hashmode: 6700 - AIX {ssha1} (Iterations: 63)

Speed.#1.........: 97718.4 kH/s (17.08ms) @ Accel:32 Loops:63 Thr:1024 Vec:1
Speed.#2.........: 87855.1 kH/s (19.73ms) @ Accel:32 Loops:63 Thr:1024 Vec:1
Speed.#*.........:   185.6 MH/s

Hashmode: 6800 - LastPass + LastPass sniffed (Iterations: 499)

Speed.#1.........:  6504.4 kH/s (54.47ms) @ Accel:16 Loops:249 Thr:1024 Vec:1
Speed.#2.........:  5689.8 kH/s (62.54ms) @ Accel:16 Loops:249 Thr:1024 Vec:1
Speed.#*.........: 12194.1 kH/s

Hashmode: 6900 - GOST R 34.11-94

Speed.#1.........:   471.8 MH/s (75.24ms) @ Accel:8 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   397.6 MH/s (89.40ms) @ Accel:8 Loops:64 Thr:1024 Vec:1
Speed.#*.........:   869.4 MH/s

Hashmode: 7000 - FortiGate (FortiOS)

Speed.#1.........: 17526.3 MH/s (64.76ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 15015.4 MH/s (75.71ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 32541.7 MH/s

Hashmode: 7100 - macOS v10.8+ (PBKDF2-SHA512) (Iterations: 1023)

Speed.#1.........:  1160.0 kH/s (57.49ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#2.........:  1006.8 kH/s (66.32ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#*.........:  2166.8 kH/s

Hashmode: 7200 - GRUB 2 (Iterations: 1023)

Speed.#1.........:  1162.4 kH/s (39.28ms) @ Accel:2 Loops:511 Thr:1024 Vec:1
Speed.#2.........:  1018.9 kH/s (44.92ms) @ Accel:2 Loops:511 Thr:1024 Vec:1
Speed.#*.........:  2181.3 kH/s

Hashmode: 7300 - IPMI2 RAKP HMAC-SHA1

Speed.#1.........:  2540.9 MH/s (55.80ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  2188.5 MH/s (64.90ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  4729.4 MH/s

Hashmode: 7400 - sha256crypt $5$, SHA256 (Unix) (Iterations: 5000)

Speed.#1.........:   773.9 kH/s (71.12ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   662.9 kH/s (83.07ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  1436.8 kH/s

Hashmode: 7401 - MySQL $A$ (sha256crypt) (Iterations: 5000)

Speed.#1.........:   721.3 kH/s (76.13ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   619.7 kH/s (88.70ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  1340.9 kH/s

Hashmode: 7500 - Kerberos 5, etype 23, AS-REQ Pre-Auth

Speed.#1.........:   756.3 MH/s (93.96ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#2.........:   644.5 MH/s (110.38ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1400.7 MH/s

Hashmode: 7700 - SAP CODVN B (BCODE)

Speed.#1.........:  3017.5 MH/s (94.20ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  2724.4 MH/s (104.42ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  5741.9 MH/s

Hashmode: 7701 - SAP CODVN B (BCODE) from RFC_READ_TABLE

Speed.#1.........:  3111.1 MH/s (91.35ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  2816.6 MH/s (100.98ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  5927.7 MH/s

Hashmode: 7800 - SAP CODVN F/G (PASSCODE)

Speed.#1.........:  3039.2 MH/s (46.59ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:  2683.9 MH/s (52.87ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  5723.1 MH/s

Hashmode: 7801 - SAP CODVN F/G (PASSCODE) from RFC_READ_TABLE

Speed.#1.........:  2829.6 MH/s (50.06ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#2.........:  2721.4 MH/s (52.14ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  5551.1 MH/s

Hashmode: 7900 - Drupal7 (Iterations: 16384)

Speed.#1.........:   147.2 kH/s (58.92ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   128.0 kH/s (67.82ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#*.........:   275.2 kH/s

Hashmode: 8000 - Sybase ASE

Speed.#1.........:  1061.2 MH/s (66.86ms) @ Accel:1 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:   914.5 MH/s (77.69ms) @ Accel:1 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  1975.7 MH/s

Hashmode: 8100 - Citrix NetScaler (SHA1)

Speed.#1.........: 17155.4 MH/s (66.17ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 14692.5 MH/s (77.39ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 31847.8 MH/s

Hashmode: 8200 - 1Password, cloudkeychain (Iterations: 39999)

Speed.#1.........:    30448 H/s (58.41ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#2.........:    26334 H/s (67.57ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#*.........:    56781 H/s

Hashmode: 8300 - DNSSEC (NSEC3)

Speed.#1.........:  7543.0 MH/s (75.30ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  6513.4 MH/s (87.32ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 14056.4 MH/s

Hashmode: 8400 - WBB3 (Woltlab Burning Board)

Speed.#1.........:  3091.4 MH/s (91.93ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2669.6 MH/s (106.58ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  5761.0 MH/s

Hashmode: 8500 - RACF

Speed.#1.........:  5562.6 MH/s (50.94ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  4689.3 MH/s (60.56ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 10251.9 MH/s

Hashmode: 8600 - Lotus Notes/Domino 5

Speed.#1.........:   408.8 MH/s (43.27ms) @ Accel:32 Loops:8 Thr:1024 Vec:1
Speed.#2.........:   344.9 MH/s (51.40ms) @ Accel:32 Loops:8 Thr:1024 Vec:1
Speed.#*.........:   753.7 MH/s

Hashmode: 8700 - Lotus Notes/Domino 6

Speed.#1.........:   136.7 MH/s (64.88ms) @ Accel:16 Loops:8 Thr:1024 Vec:1
Speed.#2.........:   114.9 MH/s (77.28ms) @ Accel:16 Loops:8 Thr:1024 Vec:1
Speed.#*.........:   251.6 MH/s

Hashmode: 8800 - Android FDE <= 4.3 (Iterations: 1999)

Speed.#1.........:  2011.0 kH/s (68.24ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  1777.8 kH/s (77.30ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  3788.8 kH/s

Hashmode: 8900 - scrypt (Iterations: 1)

Speed.#1.........:   695.9 kH/s (24.24ms) @ Accel:16 Loops:1 Thr:16 Vec:1
Speed.#2.........:   685.9 kH/s (24.71ms) @ Accel:16 Loops:1 Thr:16 Vec:1
Speed.#*.........:  1381.8 kH/s

Hashmode: 9000 - Password Safe v2 (Iterations: 1000)

Speed.#1.........:   968.3 kH/s (34.00ms) @ Accel:64 Loops:1000 Thr:12 Vec:1
Speed.#2.........:   841.7 kH/s (39.29ms) @ Accel:64 Loops:1000 Thr:12 Vec:1
Speed.#*.........:  1810.0 kH/s

Hashmode: 9100 - Lotus Notes/Domino 8 (Iterations: 4999)

Speed.#1.........:  1623.2 kH/s (67.48ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  1411.5 kH/s (77.55ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  3034.8 kH/s

Hashmode: 9200 - Cisco-IOS $8$ (PBKDF2-SHA256) (Iterations: 19999)

Speed.#1.........:   166.7 kH/s (85.32ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   144.2 kH/s (98.69ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   311.0 kH/s

Hashmode: 9300 - Cisco-IOS $9$ (scrypt) (Iterations: 1)

Speed.#1.........:    42465 H/s (204.27ms) @ Accel:16 Loops:1 Thr:8 Vec:1
Speed.#2.........:    35769 H/s (242.74ms) @ Accel:16 Loops:1 Thr:8 Vec:1
Speed.#*.........:    78234 H/s

Hashmode: 9400 - MS Office 2007 (Iterations: 50000)

Speed.#1.........:   334.3 kH/s (68.07ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   288.0 kH/s (79.05ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........:   622.3 kH/s

Hashmode: 9500 - MS Office 2010 (Iterations: 100000)

Speed.#1.........:   166.9 kH/s (68.17ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   143.1 kH/s (79.55ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........:   310.0 kH/s

Hashmode: 9600 - MS Office 2013 (Iterations: 100000)

Speed.#1.........:    25818 H/s (55.10ms) @ Accel:4 Loops:512 Thr:1024 Vec:1
Speed.#2.........:    21874 H/s (65.07ms) @ Accel:4 Loops:512 Thr:1024 Vec:1
Speed.#*.........:    47692 H/s

Hashmode: 9700 - MS Office <= 2003 $0/$1, MD5 + RC4

Speed.#1.........:   676.6 MH/s (52.36ms) @ Accel:128 Loops:64 Thr:64 Vec:1
Speed.#2.........:   579.4 MH/s (61.28ms) @ Accel:128 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1256.0 MH/s

Hashmode: 9710 - MS Office <= 2003 $0/$1, MD5 + RC4, collider #1

Speed.#1.........:   726.5 MH/s (48.78ms) @ Accel:128 Loops:64 Thr:64 Vec:1
Speed.#2.........:   613.0 MH/s (57.89ms) @ Accel:128 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1339.5 MH/s

Hashmode: 9720 - MS Office <= 2003 $0/$1, MD5 + RC4, collider #2

Speed.#1.........:  5061.8 MH/s (56.02ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  4353.5 MH/s (65.24ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  9415.3 MH/s

Hashmode: 9800 - MS Office <= 2003 $3/$4, SHA1 + RC4

Speed.#1.........:   757.8 MH/s (93.76ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#2.........:   643.1 MH/s (110.60ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1400.9 MH/s

Hashmode: 9810 - MS Office <= 2003 $3, SHA1 + RC4, collider #1

Speed.#1.........:   802.4 MH/s (88.57ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#2.........:   680.1 MH/s (104.57ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1482.5 MH/s

Hashmode: 9820 - MS Office <= 2003 $3, SHA1 + RC4, collider #2

Speed.#1.........:  8123.1 MH/s (69.89ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  6984.4 MH/s (81.40ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 15107.5 MH/s

Hashmode: 9900 - Radmin2

Speed.#1.........: 22101.9 MH/s (51.29ms) @ Accel:32 Loops:512 Thr:1024 Vec:4
Speed.#2.........: 19215.1 MH/s (59.11ms) @ Accel:32 Loops:512 Thr:1024 Vec:4
Speed.#*.........: 41317.0 MH/s

Hashmode: 10000 - Django (PBKDF2-SHA256) (Iterations: 9999)

Speed.#1.........:   331.1 kH/s (83.90ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   285.5 kH/s (97.35ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   616.6 kH/s

Hashmode: 10100 - SipHash

Speed.#1.........: 68253.0 MH/s (33.11ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 59318.9 MH/s (38.21ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:   127.6 GH/s

Hashmode: 10200 - CRAM-MD5

Speed.#1.........:  9860.2 MH/s (57.51ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  8556.2 MH/s (66.39ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 18416.4 MH/s

Hashmode: 10300 - SAP CODVN H (PWDSALTEDHASH) iSSHA-1 (Iterations: 1023)

Speed.#1.........: 13191.9 kH/s (81.47ms) @ Accel:16 Loops:1023 Thr:1024 Vec:1
Speed.#2.........: 11437.2 kH/s (94.69ms) @ Accel:16 Loops:1023 Thr:1024 Vec:1
Speed.#*.........: 24629.2 kH/s

Hashmode: 10400 - PDF 1.1 - 1.3 (Acrobat 2 - 4)

Speed.#1.........:   850.6 MH/s (83.47ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#2.........:   724.6 MH/s (98.12ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1575.2 MH/s

Hashmode: 10410 - PDF 1.1 - 1.3 (Acrobat 2 - 4), collider #1

Speed.#1.........:   866.6 MH/s (81.95ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#2.........:   737.4 MH/s (96.43ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1604.0 MH/s

Hashmode: 10420 - PDF 1.1 - 1.3 (Acrobat 2 - 4), collider #2

Speed.#1.........: 18960.7 MH/s (59.84ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 16444.3 MH/s (69.12ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 35405.0 MH/s

Hashmode: 10500 - PDF 1.4 - 1.6 (Acrobat 5 - 8) (Iterations: 70)

Speed.#1.........: 39077.9 kH/s (52.46ms) @ Accel:512 Loops:70 Thr:64 Vec:1
Speed.#2.........: 29510.4 kH/s (69.99ms) @ Accel:512 Loops:70 Thr:64 Vec:1
Speed.#*.........: 68588.3 kH/s

Hashmode: 10600 - PDF 1.7 Level 3 (Acrobat 9)

Speed.#1.........:  8657.7 MH/s (65.56ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  7406.4 MH/s (76.75ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 16064.1 MH/s

Hashmode: 10700 - PDF 1.7 Level 8 (Acrobat 10 - 11) (Iterations: 64)

Speed.#1.........:    95259 H/s (91.22ms) @ Accel:4 Loops:2 Thr:1024 Vec:1
Speed.#2.........:    79712 H/s (109.06ms) @ Accel:4 Loops:2 Thr:1024 Vec:1
Speed.#*.........:   175.0 kH/s

Hashmode: 10800 - SHA2-384

Speed.#1.........:  2717.3 MH/s (52.14ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  2341.1 MH/s (60.63ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  5058.4 MH/s

Hashmode: 10900 - PBKDF2-HMAC-SHA256 (Iterations: 999)

Speed.#1.........:  3227.0 kH/s (75.67ms) @ Accel:32 Loops:124 Thr:1024 Vec:1
Speed.#2.........:  2777.2 kH/s (87.87ms) @ Accel:32 Loops:124 Thr:1024 Vec:1
Speed.#*.........:  6004.2 kH/s

Hashmode: 10901 - RedHat 389-DS LDAP (PBKDF2-HMAC-SHA256) (Iterations: 8191)

Speed.#1.........:   405.5 kH/s (85.61ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   346.5 kH/s (100.25ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   752.0 kH/s

Hashmode: 11000 - PrestaShop

Speed.#1.........: 23685.7 MH/s (47.84ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 20628.1 MH/s (55.04ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 44313.8 MH/s

Hashmode: 11100 - PostgreSQL CRAM (MD5)

Speed.#1.........: 17423.8 MH/s (65.15ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 15211.0 MH/s (74.75ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 32634.8 MH/s

Hashmode: 11200 - MySQL CRAM (SHA1)

Speed.#1.........:  5209.8 MH/s (54.41ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  4478.4 MH/s (63.40ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  9688.1 MH/s

Hashmode: 11300 - Bitcoin/Litecoin wallet.dat (Iterations: 200459)

Speed.#1.........:    12843 H/s (55.26ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:    10939 H/s (64.92ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:    23781 H/s

Hashmode: 11400 - SIP digest authentication (MD5)

Speed.#1.........:  7954.8 MH/s (71.38ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  6953.9 MH/s (81.76ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 14908.7 MH/s

Hashmode: 11500 - CRC32

Speed.#1.........: 13672.0 MH/s (41.39ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 11927.1 MH/s (47.55ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 25599.1 MH/s

Hashmode: 11600 - 7-Zip (Iterations: 16384)

Speed.#1.........:   830.5 kH/s (65.76ms) @ Accel:4 Loops:4096 Thr:1024 Vec:1
Speed.#2.........:   788.0 kH/s (72.74ms) @ Accel:4 Loops:4096 Thr:1024 Vec:1
Speed.#*.........:  1618.5 kH/s

Hashmode: 11700 - GOST R 34.11-2012 (Streebog) 256-bit, big-endian

Speed.#1.........: 97127.5 kH/s (91.44ms) @ Accel:2 Loops:64 Thr:1024 Vec:1
Speed.#2.........: 83447.5 kH/s (106.55ms) @ Accel:2 Loops:64 Thr:1024 Vec:1
Speed.#*.........:   180.6 MH/s

Hashmode: 11750 - HMAC-Streebog-256 (key = $pass), big-endian

Speed.#1.........: 34532.3 kH/s (64.20ms) @ Accel:8 Loops:4 Thr:1024 Vec:1
Speed.#2.........: 29668.3 kH/s (74.83ms) @ Accel:8 Loops:4 Thr:1024 Vec:1
Speed.#*.........: 64200.7 kH/s

Hashmode: 11760 - HMAC-Streebog-256 (key = $salt), big-endian

Speed.#1.........: 47874.9 kH/s (92.75ms) @ Accel:2 Loops:32 Thr:1024 Vec:1
Speed.#2.........: 41042.8 kH/s (108.30ms) @ Accel:2 Loops:32 Thr:1024 Vec:1
Speed.#*.........: 88917.6 kH/s

Hashmode: 11800 - GOST R 34.11-2012 (Streebog) 512-bit, big-endian

Speed.#1.........: 97105.6 kH/s (91.46ms) @ Accel:1 Loops:128 Thr:1024 Vec:1
Speed.#2.........: 83186.9 kH/s (106.86ms) @ Accel:1 Loops:128 Thr:1024 Vec:1
Speed.#*.........:   180.3 MH/s

Hashmode: 11850 - HMAC-Streebog-512 (key = $pass), big-endian

Speed.#1.........: 30525.2 kH/s (72.65ms) @ Accel:2 Loops:16 Thr:1024 Vec:1
Speed.#2.........: 26193.2 kH/s (84.79ms) @ Accel:2 Loops:16 Thr:1024 Vec:1
Speed.#*.........: 56718.4 kH/s

Hashmode: 11860 - HMAC-Streebog-512 (key = $salt), big-endian

Speed.#1.........: 40077.3 kH/s (55.26ms) @ Accel:1 Loops:32 Thr:1024 Vec:1
Speed.#2.........: 34487.7 kH/s (64.34ms) @ Accel:1 Loops:32 Thr:1024 Vec:1
Speed.#*.........: 74565.0 kH/s

Hashmode: 11900 - PBKDF2-HMAC-MD5 (Iterations: 999)

Speed.#1.........: 18544.0 kH/s (37.15ms) @ Accel:32 Loops:499 Thr:1024 Vec:1
Speed.#2.........: 16567.3 kH/s (41.91ms) @ Accel:32 Loops:499 Thr:1024 Vec:1
Speed.#*.........: 35111.3 kH/s

Hashmode: 12000 - PBKDF2-HMAC-SHA1 (Iterations: 999)

Speed.#1.........:  7872.5 kH/s (45.45ms) @ Accel:16 Loops:499 Thr:1024 Vec:1
Speed.#2.........:  6915.3 kH/s (51.99ms) @ Accel:16 Loops:499 Thr:1024 Vec:1
Speed.#*.........: 14787.9 kH/s

Hashmode: 12001 - Atlassian (PBKDF2-HMAC-SHA1) (Iterations: 9999)

Speed.#1.........:   824.7 kH/s (67.18ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   723.6 kH/s (76.64ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  1548.3 kH/s

Hashmode: 12100 - PBKDF2-HMAC-SHA512 (Iterations: 999)

Speed.#1.........:  1204.6 kH/s (50.67ms) @ Accel:8 Loops:124 Thr:1024 Vec:1
Speed.#2.........:  1057.5 kH/s (57.75ms) @ Accel:8 Loops:124 Thr:1024 Vec:1
Speed.#*.........:  2262.2 kH/s

Hashmode: 12200 - eCryptfs (Iterations: 65536)

Speed.#1.........:    39719 H/s (54.65ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:    33771 H/s (64.32ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:    73490 H/s

Hashmode: 12300 - Oracle T: Type (Oracle 12+) (Iterations: 4095)

Speed.#1.........:   299.2 kH/s (57.85ms) @ Accel:4 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   229.2 kH/s (75.63ms) @ Accel:4 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   528.4 kH/s

Hashmode: 12400 - BSDi Crypt, Extended DES (Iterations: 2194)

Speed.#1.........:  3972.0 kH/s (110.72ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  3026.7 kH/s (145.54ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  6998.8 kH/s

Hashmode: 12500 - RAR3-hp (Iterations: 262144)

Speed.#1.........:    69084 H/s (62.81ms) @ Accel:1 Loops:16384 Thr:1024 Vec:1
Speed.#2.........:    65366 H/s (66.42ms) @ Accel:1 Loops:16384 Thr:1024 Vec:1
Speed.#*.........:   134.4 kH/s

Hashmode: 12600 - ColdFusion 10+

Speed.#1.........:  4920.2 MH/s (57.63ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  3974.5 MH/s (71.46ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  8894.7 MH/s

Hashmode: 12700 - Blockchain, My Wallet (Iterations: 9)

Speed.#1.........:   150.3 MH/s (5.79ms) @ Accel:32 Loops:9 Thr:1024 Vec:1
Speed.#2.........:   134.7 MH/s (7.28ms) @ Accel:32 Loops:9 Thr:1024 Vec:1
Speed.#*.........:   285.1 MH/s

Hashmode: 12800 - MS-AzureSync PBKDF2-HMAC-SHA256 (Iterations: 99)

Speed.#1.........: 27834.9 kH/s (64.89ms) @ Accel:32 Loops:99 Thr:1024 Vec:1
Speed.#2.........: 24002.4 kH/s (74.01ms) @ Accel:32 Loops:99 Thr:1024 Vec:1
Speed.#*.........: 51837.3 kH/s

Hashmode: 12900 - Android FDE (Samsung DEK) (Iterations: 4095)

Speed.#1.........:   847.9 kH/s (81.52ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   733.9 kH/s (94.30ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  1581.8 kH/s

Hashmode: 13000 - RAR5 (Iterations: 32799)

Speed.#1.........:   106.0 kH/s (81.80ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:    91608 H/s (94.67ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   197.6 kH/s

Hashmode: 13100 - Kerberos 5, etype 23, TGS-REP

Speed.#1.........:   752.7 MH/s (94.40ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#2.........:   643.1 MH/s (110.61ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1395.8 MH/s

Hashmode: 13200 - AxCrypt (Iterations: 10467)

Speed.#1.........:   214.9 kH/s (253.19ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   182.9 kH/s (297.39ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   397.8 kH/s

Hashmode: 13300 - AxCrypt in-memory SHA1

Speed.#1.........: 18445.8 MH/s (61.52ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 16030.6 MH/s (70.90ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 34476.4 MH/s

Hashmode: 13400 - KeePass 1 (AES/Twofish) and KeePass 2 (AES) (Iterations: 24569)

Speed.#1.........:    65713 H/s (176.47ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:    55978 H/s (207.18ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:   121.7 kH/s

Hashmode: 13500 - PeopleSoft PS_TOKEN

Speed.#1.........: 14242.9 MH/s (79.77ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 12372.1 MH/s (91.95ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 26615.0 MH/s

Hashmode: 13600 - WinZip (Iterations: 999)

Speed.#1.........:  7802.5 kH/s (68.52ms) @ Accel:8 Loops:999 Thr:1024 Vec:1
Speed.#2.........:  7114.6 kH/s (75.43ms) @ Accel:8 Loops:999 Thr:1024 Vec:1
Speed.#*.........: 14917.2 kH/s

Hashmode: 13711 - VeraCrypt RIPEMD160 + XTS 512 bit (Iterations: 655330)

Speed.#1.........:     2466 H/s (42.26ms) @ Accel:32 Loops:62 Thr:1024 Vec:1
Speed.#2.........:     2177 H/s (47.91ms) @ Accel:32 Loops:62 Thr:1024 Vec:1
Speed.#*.........:     4643 H/s

Hashmode: 13712 - VeraCrypt RIPEMD160 + XTS 1024 bit (Iterations: 655330)

Speed.#1.........:     1389 H/s (37.32ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#2.........:     1224 H/s (42.39ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#*.........:     2613 H/s

Hashmode: 13713 - VeraCrypt RIPEMD160 + XTS 1536 bit (Iterations: 655330)

Speed.#1.........:      933 H/s (26.71ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#2.........:      831 H/s (30.02ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#*.........:     1764 H/s

Hashmode: 13721 - VeraCrypt SHA512 + XTS 512 bit (Iterations: 499999)

Speed.#1.........:     2435 H/s (28.43ms) @ Accel:4 Loops:250 Thr:1024 Vec:1
Speed.#2.........:     2125 H/s (32.65ms) @ Accel:4 Loops:250 Thr:1024 Vec:1
Speed.#*.........:     4560 H/s

Hashmode: 13722 - VeraCrypt SHA512 + XTS 1024 bit (Iterations: 499999)

Speed.#1.........:     1139 H/s (29.08ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#2.........:     1001 H/s (33.11ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#*.........:     2140 H/s

Hashmode: 13723 - VeraCrypt SHA512 + XTS 1536 bit (Iterations: 499999)

Speed.#1.........:      763 H/s (43.42ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#2.........:      668 H/s (49.62ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#*.........:     1431 H/s

Hashmode: 13731 - VeraCrypt Whirlpool + XTS 512 bit (Iterations: 499999)

Speed.#1.........:      156 H/s (220.98ms) @ Accel:8 Loops:62 Thr:1024 Vec:1
Speed.#2.........:      133 H/s (257.85ms) @ Accel:8 Loops:62 Thr:1024 Vec:1
Speed.#*.........:      289 H/s

Hashmode: 13732 - VeraCrypt Whirlpool + XTS 1024 bit (Iterations: 499999)

Speed.#1.........:       79 H/s (218.53ms) @ Accel:4 Loops:62 Thr:1024 Vec:1
Speed.#2.........:       67 H/s (255.37ms) @ Accel:4 Loops:62 Thr:1024 Vec:1
Speed.#*.........:      146 H/s

Hashmode: 13733 - VeraCrypt Whirlpool + XTS 1536 bit (Iterations: 499999)

Speed.#1.........:       52 H/s (164.17ms) @ Accel:4 Loops:31 Thr:1024 Vec:1
Speed.#2.........:       45 H/s (191.71ms) @ Accel:4 Loops:31 Thr:1024 Vec:1
Speed.#*.........:       97 H/s

Hashmode: 13741 - VeraCrypt RIPEMD160 + XTS 512 bit + boot-mode (Iterations: 327660)

Speed.#1.........:     4942 H/s (43.55ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:     4362 H/s (49.35ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:     9304 H/s

Hashmode: 13742 - VeraCrypt RIPEMD160 + XTS 1024 bit + boot-mode (Iterations: 327660)

Speed.#1.........:     2765 H/s (38.72ms) @ Accel:32 Loops:32 Thr:1024 Vec:1
Speed.#2.........:     2451 H/s (43.72ms) @ Accel:32 Loops:32 Thr:1024 Vec:1
Speed.#*.........:     5216 H/s

Hashmode: 13743 - VeraCrypt RIPEMD160 + XTS 1536 bit + boot-mode (Iterations: 327660)

Speed.#1.........:     1873 H/s (28.41ms) @ Accel:32 Loops:16 Thr:1024 Vec:1
Speed.#2.........:     1671 H/s (31.86ms) @ Accel:32 Loops:16 Thr:1024 Vec:1
Speed.#*.........:     3543 H/s

Hashmode: 13751 - VeraCrypt SHA256 + XTS 512 bit (Iterations: 499999)

Speed.#1.........:     3362 H/s (40.62ms) @ Accel:32 Loops:62 Thr:1024 Vec:1
Speed.#2.........:     2926 H/s (46.68ms) @ Accel:32 Loops:62 Thr:1024 Vec:1
Speed.#*.........:     6288 H/s

Hashmode: 13752 - VeraCrypt SHA256 + XTS 1024 bit (Iterations: 499999)

Speed.#1.........:     1716 H/s (39.86ms) @ Accel:16 Loops:62 Thr:1024 Vec:1
Speed.#2.........:      832 H/s (81.86ms) @ Accel:16 Loops:62 Thr:1024 Vec:1
Speed.#*.........:     2548 H/s

Hashmode: 13753 - VeraCrypt SHA256 + XTS 1536 bit (Iterations: 499999)

Speed.#1.........:     1082 H/s (30.20ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#2.........:      846 H/s (38.56ms) @ Accel:32 Loops:15 Thr:1024 Vec:1
Speed.#*.........:     1928 H/s

Hashmode: 13761 - VeraCrypt SHA256 + XTS 512 bit + boot-mode (Iterations: 199999)

Speed.#1.........:     8437 H/s (41.75ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:     6872 H/s (51.25ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:    15309 H/s

Hashmode: 13762 - VeraCrypt SHA256 + XTS 1024 bit + boot-mode (Iterations: 199999)

Speed.#1.........:     4271 H/s (41.33ms) @ Accel:16 Loops:64 Thr:1024 Vec:1
Speed.#2.........:     3433 H/s (51.45ms) @ Accel:16 Loops:64 Thr:1024 Vec:1
Speed.#*.........:     7704 H/s

Hashmode: 13763 - VeraCrypt SHA256 + XTS 1536 bit + boot-mode (Iterations: 199999)

Speed.#1.........:     2794 H/s (31.49ms) @ Accel:16 Loops:32 Thr:1024 Vec:1
Speed.#2.........:     2377 H/s (36.97ms) @ Accel:16 Loops:32 Thr:1024 Vec:1
Speed.#*.........:     5170 H/s

Hashmode: 13771 - VeraCrypt Streebog-512 + XTS 512 bit (Iterations: 499999)

Speed.#1.........:       61 H/s (142.04ms) @ Accel:2 Loops:62 Thr:1024 Vec:1
Speed.#2.........:       46 H/s (186.26ms) @ Accel:2 Loops:62 Thr:1024 Vec:1
Speed.#*.........:      107 H/s

Hashmode: 13772 - VeraCrypt Streebog-512 + XTS 1024 bit (Iterations: 499999)

Speed.#1.........:       30 H/s (127.94ms) @ Accel:8 Loops:7 Thr:1024 Vec:1
Speed.#2.........:       23 H/s (165.37ms) @ Accel:8 Loops:7 Thr:1024 Vec:1
Speed.#*.........:       53 H/s

Hashmode: 13773 - VeraCrypt Streebog-512 + XTS 1536 bit (Iterations: 499999)

Speed.#1.........:       20 H/s (163.49ms) @ Accel:16 Loops:3 Thr:1024 Vec:1
Speed.#2.........:        9 H/s (356.19ms) @ Accel:16 Loops:3 Thr:1024 Vec:1
Speed.#*.........:       29 H/s

Hashmode: 13800 - Windows Phone 8+ PIN/password

Speed.#1.........:  2106.0 MH/s (67.35ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   924.3 MH/s (153.77ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  3030.3 MH/s

Hashmode: 13900 - OpenCart

Speed.#1.........:  4843.6 MH/s (58.52ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  2105.7 MH/s (134.67ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  6949.2 MH/s

Hashmode: 14000 - DES (PT = $salt, key = $pass)

Speed.#1.........: 54543.2 MH/s (41.19ms) @ Accel:512 Loops:1024 Thr:64 Vec:1
Speed.#2.........: 25488.3 MH/s (88.69ms) @ Accel:512 Loops:1024 Thr:64 Vec:1
Speed.#*.........: 80031.5 MH/s

Hashmode: 14100 - 3DES (PT = $salt, key = $pass)

Speed.#1.........:  5615.0 MH/s (101.22ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  2291.5 MH/s (248.35ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  7906.4 MH/s

Hashmode: 14400 - sha1(CX)

Speed.#1.........:   931.6 MH/s (76.18ms) @ Accel:4 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   446.0 MH/s (159.27ms) @ Accel:4 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  1377.6 MH/s

Hashmode: 14600 - LUKS (Iterations: 163044)

Speed.#1.........:    25371 H/s (68.69ms) @ Accel:512 Loops:128 Thr:64 Vec:1
Speed.#2.........:    11752 H/s (148.21ms) @ Accel:512 Loops:128 Thr:64 Vec:1
Speed.#*.........:    37123 H/s

Hashmode: 14700 - iTunes backup < 10.0 (Iterations: 9999)

Speed.#1.........:   408.6 kH/s (69.53ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   194.2 kH/s (146.23ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:   602.9 kH/s

Hashmode: 14800 - iTunes backup >= 10.0 (Iterations: 9999999)

Speed.#1.........:      332 H/s (85.49ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:      135 H/s (210.51ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:      467 H/s

Hashmode: 14900 - Skip32 (PT = $salt, key = $pass)

Speed.#1.........: 10127.4 MH/s (2.97ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........:        0 H/s (0.00ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 10127.4 MH/s

Hashmode: 15000 - FileZilla Server >= 0.9.55

Speed.#1.........:  2575.7 MH/s (55.00ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  1436.7 MH/s (98.78ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  4012.4 MH/s

Hashmode: 15100 - Juniper/NetBSD sha1crypt (Iterations: 19999)

Speed.#1.........:   414.0 kH/s (68.69ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   205.8 kH/s (138.14ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   619.7 kH/s

Hashmode: 15200 - Blockchain, My Wallet, V2 (Iterations: 4999)

Speed.#1.........:   813.2 kH/s (68.15ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   437.7 kH/s (129.82ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  1250.8 kH/s

Hashmode: 15300 - DPAPI masterkey file v1 (Iterations: 23999)

Speed.#1.........:   172.4 kH/s (68.46ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:    85815 H/s (138.11ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:   258.2 kH/s

Hashmode: 15400 - ChaCha20

Speed.#1.........: 11648.5 MH/s (195.51ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  5684.8 MH/s (400.66ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 17333.3 MH/s

Hashmode: 15500 - JKS Java Key Store Private Keys (SHA1)

Speed.#1.........: 19032.7 MH/s (59.57ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 10349.1 MH/s (109.75ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 29381.9 MH/s

Hashmode: 15600 - Ethereum Wallet, PBKDF2-HMAC-SHA256 (Iterations: 1023)

Speed.#1.........:  3271.4 kH/s (66.47ms) @ Accel:16 Loops:255 Thr:1024 Vec:1
Speed.#2.........:  1169.1 kH/s (187.16ms) @ Accel:16 Loops:255 Thr:1024 Vec:1
Speed.#*.........:  4440.5 kH/s

Hashmode: 15700 - Ethereum Wallet, SCRYPT (Iterations: 1)

Speed.#1.........:        1 H/s (17973.71ms) @ Accel:1 Loops:1 Thr:1 Vec:1
Speed.#2.........:        1 H/s (71592.27ms) @ Accel:1 Loops:1 Thr:1 Vec:1
Speed.#*.........:        2 H/s

Hashmode: 15900 - DPAPI masterkey file v2 (Iterations: 12899)

Speed.#1.........:    95415 H/s (55.87ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#2.........:    34281 H/s (160.78ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#*.........:   129.7 kH/s

Hashmode: 16000 - Tripcode

Speed.#1.........:   343.7 MH/s (51.50ms) @ Accel:1 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   140.6 MH/s (126.10ms) @ Accel:1 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   484.3 MH/s

Hashmode: 16100 - TACACS+

Speed.#1.........: 34278.7 MH/s (66.21ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 11609.0 MH/s (195.50ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 45887.7 MH/s

Hashmode: 16200 - Apple Secure Notes (Iterations: 19999)

Speed.#1.........:   174.6 kH/s (81.44ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:    54567 H/s (260.26ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   229.2 kH/s

Hashmode: 16300 - Ethereum Pre-Sale Wallet, PBKDF2-HMAC-SHA256 (Iterations: 1999)

Speed.#1.........:  1692.3 kH/s (79.89ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   521.9 kH/s (262.94ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  2214.2 kH/s

Hashmode: 16400 - CRAM-MD5 Dovecot

Speed.#1.........: 62578.0 MH/s (36.10ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........: 21724.3 MH/s (104.18ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........: 84302.3 MH/s

Hashmode: 16500 - JWT (JSON Web Token)

Speed.#1.........:  1605.5 MH/s (88.46ms) @ Accel:4 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   743.7 MH/s (191.18ms) @ Accel:4 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  2349.2 MH/s

Hashmode: 16600 - Electrum Wallet (Salt-Type 1-3)

Speed.#1.........:   979.6 MH/s (72.41ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   447.7 MH/s (158.71ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  1427.2 MH/s

Hashmode: 16700 - FileVault 2 (Iterations: 19999)

Speed.#1.........:   174.0 kH/s (81.73ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:    76802 H/s (185.12ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   250.8 kH/s

Hashmode: 16800 - WPA-PMKID-PBKDF2 (Iterations: 4095)

Speed.#1.........:   999.8 kH/s (69.32ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   484.6 kH/s (142.97ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  1484.4 kH/s

Hashmode: 16801 - WPA-PMKID-PMK (Iterations: 0)

Speed.#1.........:   355.0 MH/s (0.00ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:   244.2 MH/s (0.00ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:   599.2 MH/s

Hashmode: 16900 - Ansible Vault (Iterations: 9999)

Speed.#1.........:   346.7 kH/s (80.02ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   153.8 kH/s (184.76ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   500.5 kH/s

Hashmode: 17200 - PKZIP (Compressed)

Speed.#1.........:  5503.2 MH/s (51.46ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:  2875.3 MH/s (98.57ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  8378.5 MH/s

Hashmode: 17210 - PKZIP (Uncompressed)

Speed.#1.........:  2729.7 MH/s (25.76ms) @ Accel:32 Loops:32 Thr:1024 Vec:1
Speed.#2.........:  1436.1 MH/s (48.98ms) @ Accel:32 Loops:32 Thr:1024 Vec:1
Speed.#*.........:  4165.8 MH/s

Hashmode: 17220 - PKZIP (Compressed Multi-File)

Speed.#1.........: 12503.7 MH/s (45.25ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  6502.7 MH/s (87.12ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 19006.4 MH/s

Hashmode: 17225 - PKZIP (Mixed Multi-File)

Speed.#1.........: 16118.7 MH/s (70.40ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  8634.1 MH/s (131.65ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 24752.8 MH/s

Hashmode: 17230 - PKZIP (Mixed Multi-File Checksum-Only)

Speed.#1.........: 16963.3 MH/s (66.90ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  7591.7 MH/s (149.71ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 24555.0 MH/s

Hashmode: 17300 - SHA3-224

Speed.#1.........:  1980.9 MH/s (71.63ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   908.3 MH/s (156.29ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  2889.1 MH/s

Hashmode: 17400 - SHA3-256

Speed.#1.........:  1964.8 MH/s (72.22ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  1025.1 MH/s (138.58ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  2989.9 MH/s

Hashmode: 17500 - SHA3-384

Speed.#1.........:  1965.2 MH/s (72.20ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   840.9 MH/s (168.93ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  2806.1 MH/s

Hashmode: 17600 - SHA3-512

Speed.#1.........:  1964.5 MH/s (72.22ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   837.9 MH/s (169.51ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  2802.4 MH/s

Hashmode: 17700 - Keccak-224

Speed.#1.........:  1930.8 MH/s (73.49ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   743.5 MH/s (191.05ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  2674.4 MH/s

Hashmode: 17800 - Keccak-256

Speed.#1.........:  1965.9 MH/s (72.17ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   807.4 MH/s (175.91ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  2773.3 MH/s

Hashmode: 17900 - Keccak-384

Speed.#1.........:  1599.8 MH/s (88.77ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:   686.3 MH/s (207.11ms) @ Accel:2 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  2286.0 MH/s

Hashmode: 18000 - Keccak-512

Speed.#1.........:  1961.7 MH/s (72.32ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   778.4 MH/s (182.49ms) @ Accel:16 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  2740.1 MH/s

Hashmode: 18100 - TOTP (HMAC-SHA1)

Speed.#1.........:  3854.0 MH/s (73.63ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  1607.9 MH/s (176.68ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  5461.9 MH/s

Hashmode: 18200 - Kerberos 5, etype 23, AS-REP

Speed.#1.........:   750.6 MH/s (94.63ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#2.........:   354.3 MH/s (200.47ms) @ Accel:256 Loops:64 Thr:64 Vec:1
Speed.#*.........:  1104.8 MH/s

Hashmode: 18300 - Apple File System (APFS) (Iterations: 19999)

Speed.#1.........:   171.8 kH/s (82.67ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:    65285 H/s (217.23ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:   237.1 kH/s

Hashmode: 18400 - Open Document Format (ODF) 1.2 (SHA-256, AES) (Iterations: 99999)

Speed.#1.........:    40916 H/s (69.47ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:    16819 H/s (168.89ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:    57735 H/s

Hashmode: 18500 - sha1(md5(md5($pass)))

Speed.#1.........:  7490.3 MH/s (75.79ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  2642.4 MH/s (215.06ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 10132.7 MH/s

Hashmode: 18600 - Open Document Format (ODF) 1.1 (SHA-1, Blowfish) (Iterations: 1023)

Speed.#1.........:  1266.7 kH/s (53.11ms) @ Accel:1024 Loops:255 Thr:12 Vec:1
Speed.#2.........:   578.3 kH/s (125.06ms) @ Accel:1024 Loops:255 Thr:12 Vec:1
Speed.#*.........:  1845.0 kH/s

Hashmode: 18700 - Java Object hashCode()

Speed.#1.........:   479.0 GH/s (4.39ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#2.........:   212.6 GH/s (10.40ms) @ Accel:32 Loops:1024 Thr:1024 Vec:8
Speed.#*.........:   691.6 GH/s

Hashmode: 18800 - Blockchain, My Wallet, Second Password (SHA256) (Iterations: 9999)

Speed.#1.........:   715.3 kH/s (77.61ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:   301.1 kH/s (184.67ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  1016.4 kH/s

Hashmode: 18900 - Android Backup (Iterations: 9999)

Speed.#1.........:   412.1 kH/s (67.36ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   187.8 kH/s (151.48ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:   599.9 kH/s

Hashmode: 19000 - QNX /etc/shadow (MD5) (Iterations: 1000)

Speed.#1.........: 72736.0 kH/s (11.66ms) @ Accel:32 Loops:500 Thr:1024 Vec:1
Speed.#2.........: 37152.1 kH/s (23.11ms) @ Accel:32 Loops:500 Thr:1024 Vec:1
Speed.#*.........:   109.9 MH/s

Hashmode: 19100 - QNX /etc/shadow (SHA256) (Iterations: 1000)

Speed.#1.........: 34866.0 kH/s (27.67ms) @ Accel:32 Loops:500 Thr:1024 Vec:1
Speed.#2.........: 14785.3 kH/s (66.40ms) @ Accel:32 Loops:500 Thr:1024 Vec:1
Speed.#*.........: 49651.3 kH/s

Hashmode: 19200 - QNX /etc/shadow (SHA512) (Iterations: 1000)

Speed.#1.........: 19032.5 kH/s (52.82ms) @ Accel:32 Loops:500 Thr:1024 Vec:1
Speed.#2.........:  7918.5 kH/s (129.66ms) @ Accel:32 Loops:500 Thr:1024 Vec:1
Speed.#*.........: 26951.0 kH/s

Hashmode: 19300 - sha1($salt1.$pass.$salt2)

Speed.#1.........:  1829.8 MH/s (77.57ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   972.4 MH/s (145.99ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  2802.2 MH/s

Hashmode: 19500 - Ruby on Rails Restful-Authentication

Speed.#1.........:   231.0 MH/s (76.79ms) @ Accel:32 Loops:8 Thr:1024 Vec:1
Speed.#2.........:   114.8 MH/s (154.64ms) @ Accel:32 Loops:8 Thr:1024 Vec:1
Speed.#*.........:   345.8 MH/s

Hashmode: 19600 - Kerberos 5, etype 17, TGS-REP (Iterations: 4095)

Speed.#1.........:  1983.8 kH/s (69.28ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:   811.6 kH/s (169.83ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  2795.4 kH/s

Hashmode: 19700 - Kerberos 5, etype 18, TGS-REP (Iterations: 4095)

Speed.#1.........:  1003.7 kH/s (68.79ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#2.........:   507.8 kH/s (136.10ms) @ Accel:16 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  1511.5 kH/s

Hashmode: 19800 - Kerberos 5, etype 17, Pre-Auth (Iterations: 4095)

Speed.#1.........:  1995.9 kH/s (68.96ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  1033.3 kH/s (133.71ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  3029.2 kH/s

Hashmode: 19900 - Kerberos 5, etype 18, Pre-Auth (Iterations: 4095)

Speed.#1.........:  1000.4 kH/s (69.13ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   468.7 kH/s (148.04ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  1469.0 kH/s

Hashmode: 20011 - DiskCryptor SHA512 + XTS 512 bit (Iterations: 999)

Speed.#1.........:  1066.3 kH/s (51.07ms) @ Accel:8 Loops:124 Thr:1024 Vec:1
Speed.#2.........:   548.2 kH/s (100.56ms) @ Accel:8 Loops:124 Thr:1024 Vec:1
Speed.#*.........:  1614.5 kH/s

Hashmode: 20012 - DiskCryptor SHA512 + XTS 1024 bit (Iterations: 999)

Speed.#1.........:   502.8 kH/s (51.33ms) @ Accel:4 Loops:124 Thr:1024 Vec:1
Speed.#2.........:   217.4 kH/s (119.90ms) @ Accel:4 Loops:124 Thr:1024 Vec:1
Speed.#*.........:   720.2 kH/s

Hashmode: 20013 - DiskCryptor SHA512 + XTS 1536 bit (Iterations: 999)

Speed.#1.........:   330.7 kH/s (76.37ms) @ Accel:4 Loops:124 Thr:1024 Vec:1
Speed.#2.........:   152.3 kH/s (167.51ms) @ Accel:4 Loops:124 Thr:1024 Vec:1
Speed.#*.........:   483.0 kH/s

Hashmode: 20200 - Python passlib pbkdf2-sha512 (Iterations: 24999)

Speed.#1.........:    49326 H/s (57.46ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#2.........:    23686 H/s (120.14ms) @ Accel:2 Loops:512 Thr:1024 Vec:1
Speed.#*.........:    73012 H/s

Hashmode: 20300 - Python passlib pbkdf2-sha256 (Iterations: 28999)

Speed.#1.........:   114.5 kH/s (85.63ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#2.........:    59780 H/s (163.93ms) @ Accel:32 Loops:128 Thr:1024 Vec:1
Speed.#*.........:   174.2 kH/s

Hashmode: 20400 - Python passlib pbkdf2-sha1 (Iterations: 130999)

Speed.#1.........:    62789 H/s (69.15ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:    29728 H/s (146.07ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........:    92517 H/s

Hashmode: 20500 - PKZIP Master Key

Speed.#1.........:   204.7 GH/s (10.77ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 91181.3 MH/s (24.74ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:   295.8 GH/s

Hashmode: 20510 - PKZIP Master Key (6 byte optimization)

Speed.#1.........: 38838.0 MH/s (28.99ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#2.........: 11924.6 MH/s (94.66ms) @ Accel:32 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 50762.6 MH/s

Hashmode: 20600 - Oracle Transportation Management (SHA256) (Iterations: 999)

Speed.#1.........:  7068.1 kH/s (77.19ms) @ Accel:8 Loops:999 Thr:1024 Vec:1
Speed.#2.........:  2357.0 kH/s (232.94ms) @ Accel:8 Loops:999 Thr:1024 Vec:1
Speed.#*.........:  9425.1 kH/s

Hashmode: 20710 - sha256(sha256($pass).$salt)

Speed.#1.........:  1911.0 MH/s (74.26ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   767.1 MH/s (185.03ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  2678.0 MH/s

Hashmode: 20711 - AuthMe sha256

Speed.#1.........:  1905.7 MH/s (74.47ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   751.2 MH/s (189.06ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  2656.9 MH/s

Hashmode: 20800 - sha256(md5($pass))

Speed.#1.........:  6608.0 MH/s (85.95ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  2238.3 MH/s (254.00ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:  8846.3 MH/s

Hashmode: 20900 - md5(sha1($pass).md5($pass).sha1($pass))

Speed.#1.........:  6212.5 MH/s (91.46ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  2453.0 MH/s (231.75ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  8665.5 MH/s

Hashmode: 21000 - BitShares v0.x - sha512(sha512_bin(pass))

Speed.#1.........:  1252.1 MH/s (56.57ms) @ Accel:8 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   465.9 MH/s (152.15ms) @ Accel:8 Loops:128 Thr:1024 Vec:1
Speed.#*.........:  1718.0 MH/s

Hashmode: 21100 - sha1(md5($pass.$salt))

Speed.#1.........: 11165.6 MH/s (50.72ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  4184.6 MH/s (135.46ms) @ Accel:16 Loops:512 Thr:1024 Vec:1
Speed.#*.........: 15350.2 MH/s

Hashmode: 21200 - md5(sha1($salt).md5($pass))

Speed.#1.........: 11583.1 MH/s (48.89ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  5442.1 MH/s (104.29ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 17025.2 MH/s

Hashmode: 21300 - md5($salt.sha1($salt.$pass))

Speed.#1.........:  7844.2 MH/s (72.35ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  4256.3 MH/s (133.39ms) @ Accel:32 Loops:256 Thr:1024 Vec:1
Speed.#*.........: 12100.5 MH/s

Hashmode: 21400 - sha256(sha256_bin($pass))

Speed.#1.........:  3844.9 MH/s (73.82ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:  1743.8 MH/s (163.08ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  5588.7 MH/s

Hashmode: 21500 - SolarWinds Orion (Iterations: 999)

Speed.#1.........:    64922 H/s (58.99ms) @ Accel:8 Loops:7 Thr:1024 Vec:1
Speed.#2.........:    37201 H/s (101.59ms) @ Accel:8 Loops:7 Thr:1024 Vec:1
Speed.#*.........:   102.1 kH/s

Hashmode: 21600 - Web2py pbkdf2-sha512 (Iterations: 999)

Speed.#1.........:  1201.6 kH/s (53.82ms) @ Accel:16 Loops:62 Thr:1024 Vec:1
Speed.#2.........:   585.0 kH/s (110.53ms) @ Accel:16 Loops:62 Thr:1024 Vec:1
Speed.#*.........:  1786.6 kH/s

Hashmode: 21700 - Electrum Wallet (Salt-Type 4) (Iterations: 1023)

Speed.#1.........:   783.1 kH/s (39.37ms) @ Accel:2 Loops:511 Thr:1024 Vec:1
Speed.#2.........:   422.7 kH/s (72.14ms) @ Accel:2 Loops:511 Thr:1024 Vec:1
Speed.#*.........:  1205.8 kH/s

Hashmode: 21800 - Electrum Wallet (Salt-Type 5) (Iterations: 1023)

Speed.#1.........:   808.7 kH/s (56.89ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#2.........:   548.3 kH/s (122.06ms) @ Accel:32 Loops:31 Thr:1024 Vec:1
Speed.#*.........:  1357.0 kH/s

Hashmode: 22000 - WPA-PBKDF2-PMKID+EAPOL (Iterations: 4095)

Speed.#1.........:  1004.8 kH/s (68.96ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#2.........:   459.1 kH/s (151.03ms) @ Accel:8 Loops:512 Thr:1024 Vec:1
Speed.#*.........:  1463.9 kH/s

Hashmode: 22001 - WPA-PMK-PMKID+EAPOL (Iterations: 0)

Speed.#1.........:   354.7 MH/s (0.00ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:   204.1 MH/s (0.00ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:   558.8 MH/s

Hashmode: 22100 - BitLocker (Iterations: 1048576)

Speed.#1.........:     3866 H/s (70.23ms) @ Accel:1 Loops:4096 Thr:1024 Vec:1
Speed.#2.........:     1641 H/s (165.53ms) @ Accel:1 Loops:4096 Thr:1024 Vec:1
Speed.#*.........:     5506 H/s

Hashmode: 22200 - Citrix NetScaler (SHA512)

Speed.#1.........:  2760.3 MH/s (51.30ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#2.........:  1298.4 MH/s (109.25ms) @ Accel:8 Loops:256 Thr:1024 Vec:1
Speed.#*.........:  4058.7 MH/s

Hashmode: 22300 - sha256($salt.$pass.$salt)

Speed.#1.........:  7613.9 MH/s (74.55ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  3720.4 MH/s (152.84ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 11334.3 MH/s

Hashmode: 22301 - Telegram Mobile App Passcode (SHA256)

Speed.#1.........:  7628.2 MH/s (74.41ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#2.........:  3495.9 MH/s (162.62ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1
Speed.#*.........: 11124.1 MH/s

Hashmode: 22400 - AES Crypt (SHA256) (Iterations: 8191)

Speed.#1.........:   635.5 kH/s (27.01ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   331.6 kH/s (51.31ms) @ Accel:32 Loops:64 Thr:1024 Vec:1
Speed.#*.........:   967.2 kH/s

Hashmode: 22500 - MultiBit Classic .key (MD5)

Speed.#1.........:  1050.4 MH/s (67.50ms) @ Accel:16 Loops:64 Thr:1024 Vec:1
Speed.#2.........:   467.2 MH/s (151.91ms) @ Accel:16 Loops:64 Thr:1024 Vec:1
Speed.#*.........:  1517.6 MH/s

Hashmode: 22600 - Telegram Desktop App Passcode (PBKDF2-HMAC-SHA1) (Iterations: 3999)

Speed.#1.........:   291.4 kH/s (59.24ms) @ Accel:8 Loops:128 Thr:1024 Vec:1
Speed.#2.........:   168.4 kH/s (102.46ms) @ Accel:8 Loops:128 Thr:1024 Vec:1
Speed.#*.........:   459.8 kH/s

Hashmode: 99999 - Plaintext

Speed.#1.........:   106.9 GH/s (20.89ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#2.........: 56593.6 MH/s (39.74ms) @ Accel:32 Loops:1024 Thr:1024 Vec:1
Speed.#*.........:   163.5 GH/s
