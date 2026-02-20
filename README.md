# 目次
- [目次](#目次)
- [曲一覧](#曲一覧)
  - [進撃の巨人 JOY/DAM](#進撃の巨人-joydam)

# 曲一覧
## 進撃の巨人 [JOY](https://www.joysound.com/web/search/cross?keyword=進撃の巨人)/[DAM](https://www.clubdam.com/karaokesearch/?keyword=進撃の巨人)
- 悪魔の子[-4] [JOY](https://www.joysound.com/web/search/cross?keyword=悪魔の子)/[DAM](https://www.clubdam.com/karaokesearch/?keyword=悪魔の子) [JOY](intent://navigation?naviGrpId=908004&view=songDetails&acfm=songdetail_navi_app#Intent;scheme=xgi-js-spnavi;package=jp.co.xing.spnavi;end)/[DAM](intent://reserve/?reqno=134314#Intent;scheme=denmoku;package=jp.co.dkkaraoke.denmokumini01;end)

<label for="keywordInput">合言葉：</label>
<input type="text" id="keywordInput" placeholder="例：こんにちは">

<p id="resultMessage" style="color: red; font-weight: bold;"></p>

<script>
  const inputElement = document.getElementById('keywordInput');
  const resultMessage = document.getElementById('resultMessage');

  // 文字が入力されるたびにチェックを実行
  inputElement.addEventListener('input', () => {
    // 入力された文字を取得
    const text = inputElement.value;

    // 「if文」を使って、入力内容が特定のものかチェックする
    if (text === 'こんにちは') {
      // 「こんにちは」と完全に一致したときの表示
      resultMessage.textContent = 'ご挨拶ありがとうございます！';
      
    } else if (text === 'シークレット') {
      // 「シークレット」と完全に一致したときの表示
      resultMessage.textContent = '🎉 秘密のメッセージを発見しました！';
      
    } else {
      // どのキーワードにも一致しない場合は、表示を消す（空文字にする）
      resultMessage.textContent = '';
    }
  });
</script>