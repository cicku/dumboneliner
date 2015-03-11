# dumboneliner
We are noobs, we prefer one-line solution!

# Steamcmd 来战：

我 OSX 不服没有 console 的痛苦，特此来战：

0. 请找到系统终端，在“其他”里面。
1. 输入

mkdir ~/steamcmd && cd ~/steamcmd && curl -O http://media.steampowered.com/client/installer/steamcmd_osx.tar.gz && tar -xvzf steamcmd_osx.tar.gz

2. ./steamcmd.sh +login 用户名 +licenses_print +quit > licenses.txt

替换用户名为你的 steam 登录名，输入完2命令后记得等3秒到5秒，然后输入你的密码。（steamcmd.sh 不支持 +password，要不就更方便了）

3. 如果没有意外，已经输出了。

4. 格式其实很简单，截取一部分给大家：

 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:35:42 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Feb 28 20:51:38 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:35:47 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar  3 12:43:41 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Sat Nov  1 11:52:41 2014 in "RU", Guest Pass
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:24:16 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Jan  6 13:25:01 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:01:50 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar  3 08:31:18 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:35:55 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 18 07:57:28 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Jan 14 17:42:09 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Feb  5 10:13:23 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:31:22 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Feb 20 13:14:53 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:35:46 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Jan 17 13:42:41 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Feb  2 17:24:06 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Feb 13 18:46:04 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Sat Feb 28 20:51:38 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:36:22 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Feb 14 09:48:22 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:45:39 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Jan  6 13:22:19 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:35:19 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:47:57 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:48:14 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:06:04 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Jan  7 11:23:57 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:46:08 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 20:48:58 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Feb 27 21:15:18 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Sat Feb 14 17:40:08 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:53:08 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Nov 24 15:43:59 2014 in "-", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:24:55 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Oct 14 02:12:47 2014 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:25:49 2015 in "CN", Credit Card
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:26:01 2015 in "CN", Credit Card
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:52:35 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan  8 20:31:16 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan  8 20:31:13 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:34:24 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan  8 20:31:41 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan  8 20:31:04 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 20:46:39 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Feb 26 21:46:57 2015 in "CN", Split
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:48:44 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:49:12 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:24:42 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:03:59 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:48:57 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Feb  2 17:36:40 2015 in "CN", Credit Card
 - State   : Active( flags 0 ) - Purchased : Mon Nov 24 15:43:56 2014 in "-", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 14:34:50 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Nov 24 15:43:53 2014 in "-", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 18 10:23:25 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Mon Jan  5 09:10:59 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Mon Feb  9 16:43:47 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Feb 18 07:57:28 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:39:58 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 16:04:46 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:31:36 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Jan  5 09:10:25 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Jan  5 09:10:29 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Jan  5 09:10:38 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Feb 14 09:50:21 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Mon Feb  2 17:41:41 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Feb  3 10:31:14 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Jan 17 20:20:31 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 14:30:05 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 14:31:40 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 16 08:49:22 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Jan 21 12:39:15 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 15:02:21 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 15:03:12 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:39:58 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 14:43:50 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:54:33 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:49:52 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 14:36:20 2014 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:22:39 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 14:59:00 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 20:47:08 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:05:35 2014 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Jan  5 09:10:22 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:23:16 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:21:18 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Feb 17 21:09:37 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan 16 06:58:23 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:47:03 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:14:54 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Jan  5 20:34:30 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 14:33:07 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:04:25 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Nov 22 22:04:32 2014 in "RU", Guest Pass
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:23:45 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Feb 27 21:15:18 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Feb 17 21:09:37 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Feb 27 21:15:18 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:24:29 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Jan 21 10:26:10 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Jan 28 06:51:19 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Jan 20 13:26:57 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 14:36:03 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 11:44:49 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Feb 27 21:15:18 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:29:16 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:29:30 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Jan  5 09:11:36 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Feb 14 10:37:24 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 18:43:36 2015 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Thu Feb  5 10:13:23 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Feb  3 10:39:06 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:40:01 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:49:12 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:41:09 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri May 16 13:43:17 2014 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 14:34:08 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Jan  5 09:11:33 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Feb  2 17:42:06 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan  8 20:30:49 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Feb 14 10:37:24 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Tue Feb 17 21:09:37 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:49:41 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:25:40 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 15:41:42 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:35:45 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:39:58 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:06:48 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 11:47:12 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:14:09 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:54:45 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:15:31 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:46:49 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 18:24:47 2015 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:26:11 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  8 13:46:53 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Feb 27 21:15:18 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 23:36:32 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:35:54 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:48:41 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jun  5 10:04:36 2014 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:50:08 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 11:46:45 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan  8 20:31:44 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:25:19 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Sep  5 06:33:59 2014 in "CN", AliPay
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:29:40 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Oct 25 19:37:12 2014 in "CN", AliPay
 - State   : Active( flags 0 ) - Purchased : Thu Jan  8 16:20:07 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:25:30 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:49:02 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 21:20:10 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Mon Nov 24 15:44:05 2014 in "-", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Feb  5 10:41:03 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Feb 18 14:53:59 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:21:57 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 29 23:25:38 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:01:54 2015 in "CN", Credit Card
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:05:03 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:01:19 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Jan 21 12:39:52 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Jan  7 11:22:05 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 20:49:12 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Nov 23 12:09:51 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar  3 07:23:01 2015 in "US", Wallet
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:25:19 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Oct 10 18:07:31 2014 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Sun Nov 23 12:10:02 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Jan  7 11:22:57 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Nov 23 12:07:53 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Feb 13 20:30:06 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Sun Nov 23 12:10:42 2014 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Oct 15 23:36:39 2014 in "CN", AliPay
 - State   : Active( flags 0 ) - Purchased : Sat Dec 20 15:51:01 2014 in "CN", AliPay
 - State   : Active( flags 0 ) - Purchased : Tue Feb  3 10:31:54 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 21:50:00 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:36:23 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Nov 16 18:20:16 2014 in "RU", Guest Pass
 - State   : Active( flags 0 ) - Purchased : Sat Jan 17 13:43:34 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Mon Feb 16 22:02:29 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:55:16 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Feb  3 10:32:28 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Jan  6 18:49:44 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Sat Jan 10 12:51:10 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Feb 27 17:13:29 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Feb  3 10:31:37 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Mar  4 14:08:58 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Feb 27 21:15:18 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Feb 27 17:13:29 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Sun Dec 28 16:56:01 2014 in "CN", AliPay
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 09:04:27 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:36:21 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:39:00 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:25:03 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Feb  3 10:32:05 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:53:59 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:54:10 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:02:14 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:24:31 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:52:55 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sun Mar  1 20:48:04 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan  9 13:36:20 2015 in "JP", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Jan 21 12:39:26 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Oct 17 09:34:18 2014 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 15:06:49 2015 in "RU", Guest Pass
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:39:58 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Mar  6 13:07:29 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:38:46 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:03:46 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 12:42:57 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Tue Jan 13 13:47:18 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Jan 13 13:47:46 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Dec 30 11:37:02 2014 in "CN", AliPay
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 16:03:20 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:55:02 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 11 10:34:42 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:38:31 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Jan 13 13:48:40 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 18:23:08 2015 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Mon Mar  2 13:53:45 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 14:39:25 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:01:39 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 11:45:52 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Jan 21 12:40:05 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan  8 20:32:37 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 18:02:30 2015 in "AU", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 11:45:41 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 11:46:57 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Mar  6 13:06:57 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Jan 13 13:48:09 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:29:57 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:09:41 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Jan 15 21:35:54 2015 in "US", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Feb  2 17:45:56 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Jan 21 09:48:06 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 11:47:32 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Feb  2 17:42:22 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:07:09 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Mon Feb  2 17:45:38 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Wed Feb 25 13:10:30 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Mar 10 11:46:14 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 15:55:56 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Tue Feb  3 10:32:17 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Thu Feb  5 14:23:28 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 14:49:43 2015 in "CN", CD Key
 - State   : Active( flags 0 ) - Purchased : Sat Jan 17 11:11:56 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Fri Jan 30 21:20:10 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Sat Feb 14 10:37:24 2015 in "CN", Wallet
 - State   : Active( flags 0 ) - Purchased : Wed Feb 18 07:57:28 2015 in "CN", PayPal
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:46:30 2015 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:50:33 2015 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:51:54 2015 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:53:34 2015 in "CN", Complimentary
 - State   : Active( flags 0 ) - Purchased : Wed Mar 11 12:54:15 2015 in "CN", Complimentary

可以看到最后一栏都是购买途径，可以看出楼主的比较复杂，试了一次支付宝，被限制了一周，从此告别
别问我为什么。

有的 ID 比如 218，是起源SDK，实在找不到看这个：
https://developer.valvesoftware.com/wiki/Steam_Application_IDs

或者去 steamdb 自己找。
------------------------------------------------------------我听够了！------------------------------------------------------------

1. 查看国区命令：cat licenses.txt | egrep 'State.*CN' | wc -l

例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*CN' | wc -l
     1520
这个1520就是数量，你的肯定和我的不一样。

2. 查看E区命令：cat licenses.txt | egrep 'State.*RU' | wc -l

例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*RU' | wc -l
       8

我有E区我自豪！不过别太多就是了...

3. 查看澳区：cat licenses.txt | egrep 'State.*AU' | wc -l

例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*AU' | wc -l
       1

我也不知道我买了什么...

4. 查看日区：cat licenses.txt | egrep 'State.*JP' | wc -l

例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*JP' | wc -l
       14

同上，不知道为啥有日区的东西...

5. 没区域的：cat licenses.txt | egrep 'State.*\"-' | wc -l
例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*\"\-' | wc -l
       8

同上，不知道买了啥奇葩。

------------------------------------------------------------折腾------------------------------------------------------------

1.  输出每个游戏信息(忽略 packageID)：

cat licenses.txt | awk '/State.*RU/{x=NR+2}(NR<=x){print}'  | sed '1s/\,/ ||/' | egrep -v '\-\-|License'

2. 三行1输出E区游戏详细信息(别的区自行替换RU为CN)：
cat licenses.txt | egrep 'State.*RU' -b2 |  egrep -v '\-\-|License' | awk '1;!(NR%3){print "\n----------分割线----------\n";}'

cat licenses.txt | egrep 'State.*RU' -b2 | sed '1s/\,/ ||/' | egrep -v '\-\-|License' | awk '1;!(NR%3){print "\n----------萌之分割线----------\n";}'

perl -ne '$s=1 if /State/; if($s){push @R,$_; $s++ if /Active.*RU/; if(/Apps/){print "@R\n-------我是分割线，我很萌-------\n" if $s>1; @R=""; $s=0;}}' licenses.txt
