# How to make scroll smoothly on your smart phone

## Problem
Only smart phone, scroll sometime becomes unsmooth.
It works fine on your Simulator on Chrome, but actual machine doesn't work.

## Solution
Write ` -webkit-overflow-scrolling: touch;` in your css.


---

# スマホでのスクロールがカタカタの時の対処法

## 課題
スマホのときのみ、スクロールがカタカタで慣性が働かない
シュミレーターではスムーズに動くが、実機ではうまくいかない

### 再現デバイス
- iPhone6S iOS 10 Safari

## 解決策
CSSに ` -webkit-overflow-scrolling: touch;` を指定する







