# 目次
- [目次](#目次)
- [曲一覧](#曲一覧)
  - [進撃の巨人 JOY/DAM](#進撃の巨人-joydam)

# 曲一覧
## 進撃の巨人 [JOY](https://www.joysound.com/web/search/cross?keyword=進撃の巨人)/[DAM](https://www.clubdam.com/karaokesearch/?keyword=進撃の巨人)
- 悪魔の子[-4] [JOY](https://www.joysound.com/web/search/cross?keyword=悪魔の子)/[DAM](https://www.clubdam.com/karaokesearch/?keyword=悪魔の子) [JOY](intent://navigation?naviGrpId=908004&view=songDetails&acfm=songdetail_navi_app#Intent;scheme=xgi-js-spnavi;package=jp.co.xing.spnavi;end)/[DAM](intent://reserve/?reqno=134314#Intent;scheme=denmoku;package=jp.co.dkkaraoke.denmokumini01;end)

<form>
  <label for="answer">解答：</label><br>
  <input type="text" id="answer" name="answer" placeholder="解答を入力">
</form>

<p>下への表示：<span id="outputText"></span></p>
<script>
  const inputElement = document.getElementById('answer');
  const outputElement = document.getElementById('outputText');
  inputElement.addEventListener('input', () => {
    outputElement.textContent = inputElement.value;
  });
</script>