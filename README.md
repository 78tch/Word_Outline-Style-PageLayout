# Word_Outline-Style-PageLayout
Word を使いこなす  
1. 画面の構成を整える（「ナビゲーション」、「スタイル」作業ウィンドウを常時表示する  
2. アウトラインを使う（章立てして推敲する）  
3. スタイルを使う（書式を一括指定して統一感を出す）  
4. ページレイアウトを使いこなす（余白や、１ページあたりの行数や行間幅を制御する）  
5. 「行と行の間隔」の調整方法  
6. 指定すべき設定の一覧
  
## 1.作業ウィンドウ
1-1.  「表示 -> 表示 -> ナビゲーション ウィンドウ」にチェックを入れる。「ナビゲーション」作業ウィンドウが画面左側に吸着するのを確認。  
1-2.  「ホーム -> スタイル（スタイルギャラリー）」の右下の矢印マークをクリック。「スタイル」作業ウィンドウが画面右側に吸着するのを確認。吸着しない場合、タイトルバーをダブルクリック。  
  
## 2.アウトライン
2-1.  「ナビゲーション」作業ウィンドウが画面左側に吸着しているか確認。「表示 -> ナビゲーション ウィンドウ」にチェックを入れる。  
2-2. 編集画面を「アウトライン表示」にする。「表示 -> アウトライン」  
2-3. 「アウトラインレベル」には、「レベル１～レベル９、本文」の10種類ある。  
2-4. レベルを付ければ、「レベル上げ・下げ」「上・下へ移動」「折り畳み・展開」ができる  
2-5. 各レベルは、上から「編（部）・章・節・項・目」といった、論文の形式・章立てに対応させる。「編（部）」は無い場合も多い。  
2-6. 「章立て」を「レベル」付けにより階層化・構造化するのは、「見出し」のみである。  
2-7. アウトラインによって階層化・構造化された「見出し」の下に、「本文」を書いていく。  
2-8. 「見出し」を「折り畳み・展開」して俯瞰し、「レベル上げ・下げ」して同一階層の話題の大きさを揃え、「上・下へ移動」して話題の流れを読みやすく調整する。  
  
## 3.スタイル
3-1. 「スタイル」作業ウィンドウを常に出す設定にする。「ホーム -> スタイル（スタイルギャラリー）」  
3-2. よく使うスタイルは「見出し１」、「見出し２」、「表題」、「標準」  
3-3. 「スタイル」の種類には、「段落」（改行マーク）、「文字」（a）、「リンク（段落と文字）」（改行マークa）、「表」、「リスト」の５種類ある。  
3-4. よく使うスタイルを自分好みに設定変更し、他の文書でも使うと、複数の文書で統一感を出せる。  
3-5. 段落スタイルが有効な範囲は「段落」であり、通常Enterでは実は「改行」ではなく「改段落」をしている。「段落」スタイルを適用すると、その段落全体がその書式になる。いっぽう、「文字」スタイルは、選択した文字だけに範囲限定して適用できる。これを組み合わせて、「やろうと思えば適用範囲の限定もできる段落スタイル」が「リンクスタイル」である。  
3-6. 「スタイル」に含められる設定には、「スタイルの変更」ウィンドウの左下にある「書式」ボタンから、フォント（日本語用のフォント、英数字用のフォント、サイズ、文字飾り）、段落（配置、アウトラインレベル、段落前後の間隔、行間）などがあるので、確認すること。  
  
## 4.ページレイアウト（1ページの行数は何で決まるか）
4-1. 「レイアウト -> ページ設定」で、「行数」と「行送り（1行の背の高さ）」が設定できる。「行間」も、「行と行のあいだの隙間」という意味ではなく、「行高」の意味なので、混同しないこと。  
4-2. 「行数」または「行送り」を変更すると、印刷可能領域に収まるように、もう一方が自動調整される。  
4-3. デフォルトでA4縦の印刷可能領域は「縦232mm × 横150mm」である。A4用紙サイズ「縦297mm × 横210mm」、余白「上35mm、下・右・左30mm」より。  
4-4. デフォルト設定では、「行数」36、「行送り」18ptとなっている。「1pt」は「1/72inch」であり、「約0.3528mm」なので、648pt x 0.3528 = 228.6144mm で、ほぼ印刷可能領域と一致する。  
4-5. 実験１：下余白を3mm増やしても行数は変わらないが、4mm増やすと1行あふれて35行になる。(232-3=229、232-4=228)（36x18x0.3528=228.6144）  
4-6. 実験２：下余白を2mm減らしても行数は変わらないが、3mm減らすと1行収まって37行になる。（232+2=234、232+3=235）（37x18x0.3528=234.9648）  　
4-7. 実験３：「ページ設定」で「行数」を試しに「1」にしてみると、「行送り」は「657.6pt」となる。657.6pt = 657.6x0.3528mm = 232.00128mm で、ほぼ印刷可能領域の232mmと一致する。  
4-8. 「行送り」＜「フォントサイズ」になるような書式設定をしてしまうと、1行で2行分の行送りが設定されてしまい、思ったようなレイアウトにならない。この場合、①1行の背の高さに収まる「フォントサイズ」に小さくするか、②フォントサイズが1行に収まるまで「行送り」を増やすと、正常な行送りに戻る。  
  
## 5.「行と行の間隔」の調整方法
ひとくちに「行と行の間隔」と言っても、設定には３種類あることを知らなければならない。  
5-1.行送りした時（１文が１行に収まらず次の行にわたる場合や、「Shift + Enter」（編集記号は下矢印）を入力した時に、各行の行の高さ。
5-2.段落の前。「Enter」を入力した時（一般に「改行」と呼ばれているが、正しくは「改段落」である）に、新しい段落の１行目の上だけに設けられる間隔。
5-3.段落の後ろ。「Enter」を入力した時に、前の段落の最後の行の下だけに設けられる間隔。
5-4.前の段落と、後ろの段落が、同一のスタイルを設定してある場合にだけ、指定した間隔を開けない、という設定もできる。

## 6.指定すべき設定の一覧
以上から、特に指定するべき設定は、

