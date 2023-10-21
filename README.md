# MyAdguardDNSFilter
My AdGuard DNS Filter List

# How to Use

DNS Filter List「PCAndPhone」をAdguardに読み込みます
![image](https://github.com/kozv/MyAdguardDNSFilter/assets/86694578/72f8f15f-c581-43d5-8f79-b7ef69e27752)
![image](https://github.com/kozv/MyAdguardDNSFilter/assets/86694578/b573b315-01d2-4bd5-adc3-d85be23a374a)

# How To Get Raw List URL !

DNS Filter List「PCAndPhone」のURLはGithub内のファイルをたどると見つかります
![image](https://github.com/kozv/MyAdguardDNSFilter/assets/86694578/c91be6b1-38c2-4c6d-a5c1-bb5eb1d28b16)
![image](https://github.com/kozv/MyAdguardDNSFilter/assets/86694578/24cfdbcd-0567-475b-a3fc-b1cd345f5b42)

# 検索結果からも非表示にする

ブロックしたサイト群を検索結果から消すには、Googleの拡張機能[uBlacklist](https://chrome.google.com/webstore/detail/pncfbmialoiaghdehhbnbhkkgmjanfhe)を使います。uBlockListの非表示するサイトのリストに、ブロックしたサイト群を追加します。Adguardとは記述のルールが異なるため、ファイル内のテキストをコピー＆ペーストをしても読み取りません。ChatGPTで成形します。

![image](https://github.com/kozv/MyAdguardDNSFilter/assets/86694578/b18bd1b5-a318-475e-90ff-d5e78f93a888)

「||」をすべて「*://*.」に置き換えてください。
「^」をすべて「/*」に置き換えてください
!で始まる行を削除してください
