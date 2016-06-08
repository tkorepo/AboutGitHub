# GitHubについて

## GitHubとは何か？

GitHubとは、バージョン管理システムをクラウド上に移し、リポジトリを一般にも公開可能としたWebサービスである。

GitHubで用いられているバージョン管理システムはgitである。gitとは、Linuxを開発したLinus Torvalds氏が開発した分散型バージョン管理システムである。そのgitをクラウド上に用意し、多くの人から利用してもらう、つまりgitのハブとなることをGitHubは目論んでいる。

## GitHubが生まれた背景

GitHubが生まれた背景には：

+ オープンソースの隆盛
+ Webサービスの隆盛
+ SNSの隆盛

といったものがからんでいる。

オープンソースの隆盛は、Linuxが頭角を現したころから顕著ではあるが、GitHubの核として利用されているgitもオープンソースであり、GitHubをメインリポジトリとしているオープンソースプロジェクトも数多くある。

Webサービスの隆盛により、スケール可能なインフラが安価に利用できるようになり、バージョン管理のような比較的かさばるものでも安価に利用できるようになった。

GitHubはSNS的な側面を持つ。ユーザのフォローやお気に入りといったSNS特有の仕組みが用意されている。

## GitHubの収益性

GitHubでは、誰にでも公開されるオープンソースプロジェクトならば無料で利用できる(無料でリポジトリを作れる)。逆にいうと、クローズドなリポジトリもあり、それについては利用者１人当たりいくら支払うということになっている。

![Pricing](images/pricing.jpg)

クローズドなリポジトリをわざわざカネを払ってまで利用するメリットとしては：

+ 遠隔地協業 + 独自インタフェース
+ 統合開発環境
+ デファクト化

といったものがあげられる。

gitはそもそもが分散型バージョン管理システムであり、遠隔地協業を前提としたツールではある。しかし、git単体では無愛想なコマンドラインインタフェースであり、それにかぶせるGUIも用意されているが、バージョン管理に特化していることもあり、総合的な遠隔地協業には荷が重い。その部分をGitHubが補うことで付加価値を提供している。

GitHubの有料コースでは、自動テストを含む継続的統合ツールなど、様々なツールが利用できる。それらを自前のサーバで維持するとなると、それなりにコストがかかる。

![Buisiness](images/business.jpg)

GitHubが広く使われるようになり、その作業フローがデファクト化している。そのため、人材確保目的にGitHubを採用することもあるようだ。

## GitHubの課題

GitHubの課題としては以下が考えられる。

+ 可用性
+ 多国語化
+ 他業種展開
+ 軋轢

GitHubが企業でも広く使われるようになり、可用性が問題となっている。GitHubのサービスが中断してしまうと企業活動まで中断してしまう可能性がある(有料サービスは可用性が高いらしいが)。GitHubも可用性の向上に努めているが、利用者側でも対策を立てておく必要がある。

GitHubは英語のサービスしかない。GitHubもご多分に漏れずUTF-8対応であるため、日本語などのドキュメントは表示可能ではある。しかし、次に述べる他業種展開を考えた上でも、メニューや説明文を多国語化したほうがいいだろう。

GitHubはソフトウェア開発プロジェクト以外でも使われることが多くなっている。バージョン管理が必要な書類を扱う業種ならば、GitHubを利用することも検討されるようになるだろう。ただし、GitHubは、基本的にテキストベースのサービスなので、より多様なフォーマットへの対応が望まれる。

他業種から利用される機会が増えるとともに軋轢も増えてきている。公開を望まないものが公開されるケースで、「GitHub大規模DDoS事件」という例がある。

## 参考資料

本家：[http://github.com](http://github.com)

Linus Torvalds氏のLinuxのページ：[https://github.com/torvalds/linux](https://github.com/torvalds/linux)

有料コース案内：[https://github.com/pricing](https://github.com/pricing)

ホワイトハウスがGitHub上に公開している資料：[https://github.com/WhiteHouse](https://github.com/WhiteHouse)

GitHub大規模DDoS事件：[http://www.itmedia.co.jp/enterprise/articles/1503/31/news047.html](http://www.itmedia.co.jp/enterprise/articles/1503/31/news047.html)
