# MyAdguardDNSFilter
My AdGuard DNS Filter List

# How to Use

DNS Filter List「PCAndPhone.txt」のリンクをAdguardに読み込みます
![image](https://github.com/kozv/MyAdguardDNSFilter/assets/86694578/72f8f15f-c581-43d5-8f79-b7ef69e27752)
![image](https://github.com/kozv/MyAdguardDNSFilter/assets/86694578/b573b315-01d2-4bd5-adc3-d85be23a374a)

# How To Get Raw List URL !


# 検索結果からも非表示にする

ブロックしたサイト群を検索結果から消すには、Googleの拡張機能[uBlacklist](https://chrome.google.com/webstore/detail/pncfbmialoiaghdehhbnbhkkgmjanfhe)を使います。uBlockListの非表示するサイトのリストに、ブロックしたサイト群を追加します。そのままでは記述のルールが異なるため読み取りません。ChatGPTで成形します。
    ![image](https://github.com/kozv/MyAdguardDNSFilter/assets/86694578/b18bd1b5-a318-475e-90ff-d5e78f93a888)

「||」をすべて「*://*.」に置き換えてください。
「^」をすべて「/*」に置き換えてください
!で始まる行を削除してください
