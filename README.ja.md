![Image text](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic/blob/main/pic/31.png)

[中国語/中文](README.md) | [英語/English](README.en.md)

# Plangothic Project

## 概要
Plangothic Project（プランゴシックプロジェクト、中国語：遍黑体项目）は、[源ノ角ゴシック](https://github.com/adobe-fonts/source-han-sans)の中国大陸版をベースに、CJK統合漢字拡張ブロックを補完するゴシック体フォントの作成を目指すプロジェクトです。2020年6月頃より開発されています。

## 収録範囲

当フォントは現在、CJK統合漢字拡張Bを除く全範囲をサポートしていますが、拡張C・D・E・Fは確認が不十分で、CJK統合漢字外のブロックは部分的にのみ実装されています。

## 主な開発メンバー
- 制作コア：[Fitzgerald](https://github.com/Fitzgerald-Porthmouth-Koenigsegg)、[Usagixineist](https://github.com/Usagixineist)、[La Striverage](https://github.com/Lastriverage)
- 共同制作：[Siphercase](https://github.com/Siphercase)、[KathrynCG](https://github.com/KathrynCG)、[Hulenkius](https://github.com/Hulenkius)、[Xiuer](https://github.com/Steve-Yuu)
- 技術協力：[0xAA55](https://github.com/0xAA55)、[Henry Chan](https://github.com/hfhchan)、[Baysoftware](https://github.com/yi-bai)、Eiso Chan、[SomeyaMako](https://github.com/SomeyaMako)

その他、これまでにご協力とご支援を頂いた方々にも、心より感謝を申し上げます。

## ライセンス
当フォントは源ノ角ゴシックの派生フォントであり、SIL Open Font Licenseのもとで提供されます。詳しくは[ライセンス](LICENSE.txt)をご覧ください。あなたは：

- 商用を含め無料で使用できます。その際、原作者への連絡や明記は必要はありません。
- フォントを自由に共有し、任意のソフトウェアやデバイスにインストールできます。
- さらに、改変または二次制作物を作成できます。ただし派生物に「Plangothic」「遍黑」の名称を再使用することはできません。また、派生物もSIL Open Font Licenseを継承する必要があります。

個人、企業、団体などが本フォントを使用、複製、修正、配布したり、本フォントに対してSIL Open Font Licenseの規定に該当する行為を行ったりした場合、使用、ダウンロード、またはライセンスの該当行為を行った当事者は、暗黙にSIL Open Font Licenseのすべての規定に同意したものとみなされます。

いかなる個人、企業、団体なども当フォントを有償で販売（フォント単体での販売、他のフォントとの抱き合わせ販売、フォントの使用に対する対価の要求等を含むが、これに限らない）してはなりません。あなたがこのフォントを有償で入手した場合、直ちに通報のうえ、必要に応じて司法当局にご相談ください。

## よくある質問
**Q1**：なぜPlangothicのフォントファイルは2つあるのですか？

**A1**：1フォントファイルあたりの最大グリフ数は65535に制限されていますが、CJK漢字の数はこれよりはるかに多いからです。

**Q2**：P1のfallback版とallideo版の違いは何ですか？

**A2**：fallback版は他の汎CJK書体をインストールしている方向けであり、未作成の漢字部分は表示されません。allideo版は、少ないファイル数で利用したいユーザー向けに、2フォントファイルのみですべてのCJK漢字をカバーできるよう、未作成の漢字を花園明朝（HanaMin）で置き換えたものです。どちらのファイルも、最新の進捗状況を反映しています。

**Q3**：なぜP1だけが2種類に分かれているのですか？

**A3**：P2に含まれる拡張Gと拡張Hの漢字は全て制作済みなので、区分する必要がないからです。

**Q4**：なぜこのプロジェクトにはURO（基本ブロック）と拡張Aの漢字が含まれていない（または少量含まれている）のですか？

**A4**：本プロジェクトの趣旨は「[源ノ角ゴシック](https://github.com/adobe-fonts/source-han-sans)ベースの補完」であるため、UROと拡張AのCJK漢字を表示したい場合は、そのまま源ノ角ゴシックを使用できます。本プロジェクトに含まれるまばらなUROと拡張Aの文字は、いずれもUnicodeでグリフ変更があったり、本プロジェクトの趣旨に合わない文字です。これらの漢字を追加する前には、他の主なフォントやUnicodeコード表のグリフと比較しています。

**Q5**：将来、他のウェイト（または他地域のグリフ）を追加する予定はありますか？

**A5**：このプロジェクトの作業量は膨大なため、その予定はありません。ご関心のある方は、各自で派生フォントを作成することができます。

**Q6**: なぜこのフォントに複雑なテキストレイアウト（CTL）がないのでしょうか？

**A6**: 当プロジェクトは、[綿雲飴里](https://github.com/MY1L)が開発した[Noto Unicode](https://github.com/MY1L/Unicode/tree/main/NotoUnicode)、あるいは[Unifont](https://unifoundry.com/unifont)と同じく、字形を表示するための補助フォントとして開発されており、組版への使用は想定していません。ご関心のある方は、各自で派生フォントを作成することができます。

## ご協力のお願い
「蹞歩を積まざれば、以って千里に至るなし」。Plangothicは時間のかかる地道なプロジェクトであり、あなたからのご支援を心よりお待ちしております。皆様からのご寄付は、当プロジェクトの発展に大変役立ちます。ご寄付以外にも、誤ったグリフのチェックや、見た目の悪いグリフの改善提案など、様々な形で貢献することも可能です。

寄付をする前に、以下の点にご注意ください。

- 寄付の前には、アカウント名をよく確認してください（Alipay：Fitzgerald K.、WeChat：蔽芪茢·茇䓮·蓲䒤菥。ユーザー名を変更した際はすぐに修正します）。不正なアカウントにより被った損害について、当プロジェクトは責任を負いかねます。
- 現在、ここが唯一の公式な寄付ページです。他のサイトで当プロジェクトへの寄付リンクを見かけた場合は、直ちに通報のうえ、必要に応じて司法当局にご相談ください。
- 当プロジェクトへのご寄付は、私たちの理念に賛同し、そのような形で私たちの発展を支援することを同意したものとみなされます。寄付者様からのご意見は真剣に検討させていただきますが、どれほどの寄付であれ、寄付者個人の意思で当プロジェクトの目的や公益性を改変することはできません。
- ご希望の方には、当プロジェクトにご協力いただいたお礼として、ご寄付いただいた時間と金額を明記したメッセージを残すことができます。
- 寄付金は全て個別に記録され、当プロジェクトのサポート費用などに使用されます。個人的な使用はされません。
- 上記の寄付方法は、中国大陸のユーザーにのみ適用されます。それ以外の場合は、[本リンク](https://paypal.me/fitzgeraldpk?country.x=C2&locale.x=zh_XC)を通じて直接ご寄付ください。なお、寄付の前にはアカウント名をよく確認してください（ユーザー名：@fitzgeraldpk、名前：于航。ユーザー名を変更した際はすぐに修正します）。不正なアカウントにより被った損害について、当プロジェクトは責任を負いかねます。
![Image text](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic/blob/main/pic/1650383987393.jpg)

## 連絡先
- GitHub：https://github.com/Fitzgerald-Porthmouth-Koenigsegg
- ツイッター：https://twitter.com/Fitzgerald_P_K_/
- グリフウィキ：http://zhs.glyphwiki.org/wiki/User:fitzgerald
- メール：374601620@qq.com、fitzgeraldkoenigsegg@gmail.com
- QQ: 374601620

## その他の説明
1. Plangothicの制作には、誰でも参加することができます。しかし、地域別字形、字形デザイン、ソフトウェアの使用、Unicodeなどについて一定の知識があることが条件です。この点についての詳細は、QQグループ[1135661191](https://jq.qq.com/?_wv=1027&k=xRTzFAfD)に参加してお問い合わせください。
2. 当プロジェクトは常に協力者を募集しています。ぜひ周りの方々にこのプロジェクトのことを広めてください。書体制作に詳しい方も大歓迎です。ぜひ現在のフォントを基によりよいフォントを作り上げましょう。上記の連絡先から作者にご連絡ください。Plangothicの発展は皆様のお力にかかっています。
3. 作者はプロのデザイナーではないため、構造が不格好であったり、追加した字に元と比べて違和感があったりするかもしれません。また、時間の制約のため、一部の文字の組み立てにぎこちなさが残っていることがありますが、「ないよりはまし」の精神でご了承ください。
4. **私は中国本土のユーザーで、このプロジェクトにはTelegram、Discordなどの海外ディスカッショングループはありません。海外ユーザーの皆様、ご迷惑をおかけして申し訳ありません！**
5. 本プロジェクトは、主に以下のツールまたはオープンソースフォントプロジェクトの一部またはすべてを使用、ないし参考にしています：
    - [源ノ角ゴシック](https://github.com/adobe-fonts/source-han-sans)
    - 他のNotoフォント
    - [上地宏一](https://twitter.com/kamichikoichi)氏による[グリフウィキ](https://glyphwiki.org/wiki/GlyphWiki:%e3%83%a1%e3%82%a4%e3%83%b3%e3%83%9a%e3%83%bc%e3%82%b8)とKAGE Engine
    - [すきまゴシック](https://oppekebekkanko.booth.pm/items/2117070)
    - [綿雲飴里](https://github.com/MY1L)氏による[Noto Unicode](https://github.com/MY1L/Unicode/tree/main/NotoUnicode)
    - [Chiron Hei HK（昭源黑體）](https://github.com/chiron-fonts/chiron-hei-hk)
    - [奈白不弍](https://github.com/Buernia)氏による[Zhudou-Sans（煮豆黑體）](https://github.com/Buernia/Zhudou-Sans)
    - [ChiuKong Gothic（秋空ゴシック）](https://github.com/ChiuMing-Neko/ChiuKongGothic)
    - [Nôm Na Tống](https://github.com/nomfoundation/font)
    - [魏安（Andrew West）](https://twitter.com/BabelStone)氏による[BabelStone Han](https://www.babelstone.co.uk/Fonts/index.html)
    - [白易](https://github.com/yi-bai)氏による[Zitools](https://zi.tools)
