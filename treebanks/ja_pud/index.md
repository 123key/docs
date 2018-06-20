---
layout: base
title:  'UD_Japanese-PUD'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD Japanese PUD

Language: [Japanese](../ja/overview/ja-hub.html) (code: `ja`)<br/>
Family: Japanese

This treebank has been part of Universal Dependencies since the UD v2.1 release.

The following people have contributed to making this treebank part of UD: Hans Uszkoreit, Vivien Macketanz, Aljoscha Burchardt, Kim Harris, Katrin Marheinecke, Slav Petrov, Tolga Kayadelen, Mohammed Attia, Ali Elkahky, Zhuoran Yu, Emily Pitler, Saran Lertpradit, Atsuko Shimada, Anna Trukhina, Martin Popel, Daniel Zeman, Hiroshi Kanayama.

Repository: [UD_Japanese-PUD](https://github.com/UniversalDependencies/UD_Japanese-PUD)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udja_pud)

License: CC BY-SA 3.0

Genre: news, wiki

Questions, comments?
General annotation questions (either Japanese-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_Japanese-PUD/issues).
If you want to collaborate, please contact [zeman&nbsp;(æt)&nbsp;ufal&nbsp;•&nbsp;mff&nbsp;•&nbsp;cuni&nbsp;•&nbsp;cz].
Development of the treebank happens directly in the UD repository, so you may submit bug fixes as pull requests against the dev branch.

| Annotation | Source |
|------------|--------|
| Lemmas | not available |
| UPOS | annotated manually in non-UD style, automatically converted to UD |
| XPOS | not available |
| Features | annotated manually in non-UD style, automatically converted to UD |
| Relations | annotated manually in non-UD style, automatically converted to UD |

## Description

This is a part of the Parallel Universal Dependencies (PUD) treebanks created
for the [CoNLL 2017 shared task on Multilingual Parsing from Raw Text to
Universal Dependencies](http://universaldependencies.org/conll17/).




There are
1000 sentences in each language, always in the same order. (The sentence
alignment is 1-1 but occasionally a sentence-level segment actually consists
of two real sentences.) The sentences are taken from the news domain (sentence
id starts in ‘n’) and from Wikipedia (sentence id starts with ‘w’). There are
usually only a few sentences from each document, selected randomly, not
necessarily adjacent. The digits on the second and third position in the
sentence ids encode the original language of the sentence. The first 750
sentences are originally English (01). The remaining 250 sentences are
originally German (02), French (03), Italian (04) or Spanish (05) and they
were translated to other languages via English. Translation into German,
French, Italian, Spanish, Arabic, Hindi, Chinese, Indonesian, Japanese,
Korean, Portuguese, Russian, Thai and Turkish has been provided by DFKI and
performed (except for German) by professional translators. Then the data has
been annotated morphologically and syntactically by Google according to Google
universal annotation guidelines; finally, it has been converted by members of
the UD community to UD v2 guidelines.

Additional languages have been provided (both translation and native UD v2
annotation) by other teams: Czech by Charles University, Finnish by University
of Turku and Swedish by Uppsala University.

The entire treebank is labeled as test set (and was used for testing in the
shared task). If it is used for training in future research, the users should
employ ten-fold cross-validation.


## Acknowledgments

# Statistics of UD Japanese PUD

## POS Tags

[ADJ](ja_pud-pos-ADJ.html) – [ADP](ja_pud-pos-ADP.html) – [ADV](ja_pud-pos-ADV.html) – [AUX](ja_pud-pos-AUX.html) – [CCONJ](ja_pud-pos-CCONJ.html) – [DET](ja_pud-pos-DET.html) – [NOUN](ja_pud-pos-NOUN.html) – [NUM](ja_pud-pos-NUM.html) – [PART](ja_pud-pos-PART.html) – [PRON](ja_pud-pos-PRON.html) – [PROPN](ja_pud-pos-PROPN.html) – [PUNCT](ja_pud-pos-PUNCT.html) – [SCONJ](ja_pud-pos-SCONJ.html) – [SYM](ja_pud-pos-SYM.html) – [VERB](ja_pud-pos-VERB.html)

## Features

[Case](ja_pud-feat-Case.html) – [Form](ja_pud-feat-Form.html) – [Number](ja_pud-feat-Number.html) – [Person](ja_pud-feat-Person.html) – [Polarity](ja_pud-feat-Polarity.html) – [Tense](ja_pud-feat-Tense.html) – [VerbForm](ja_pud-feat-VerbForm.html) – [Voice](ja_pud-feat-Voice.html)

## Relations

[acl](ja_pud-dep-acl.html) – [advcl](ja_pud-dep-advcl.html) – [advmod](ja_pud-dep-advmod.html) – [amod](ja_pud-dep-amod.html) – [aux](ja_pud-dep-aux.html) – [case](ja_pud-dep-case.html) – [cc](ja_pud-dep-cc.html) – [ccomp](ja_pud-dep-ccomp.html) – [compound](ja_pud-dep-compound.html) – [cop](ja_pud-dep-cop.html) – [csubj](ja_pud-dep-csubj.html) – [dep](ja_pud-dep-dep.html) – [det](ja_pud-dep-det.html) – [fixed](ja_pud-dep-fixed.html) – [iobj](ja_pud-dep-iobj.html) – [mark](ja_pud-dep-mark.html) – [nmod](ja_pud-dep-nmod.html) – [nsubj](ja_pud-dep-nsubj.html) – [nummod](ja_pud-dep-nummod.html) – [obj](ja_pud-dep-obj.html) – [obl](ja_pud-dep-obl.html) – [punct](ja_pud-dep-punct.html) – [root](ja_pud-dep-root.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 1000 sentences and 26818 tokens.</li>
</ul>

<ul>
<li>This corpus contains 25817 tokens (96%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus does not contain words with spaces.</li>
</ul>

<ul>
<li>This corpus contains 38 types of words that contain both letters and punctuation. Examples: 、と, ドナルド・トランプ, B.C, 、という, 、を, G.D.P, H​e​r​F​a​t​h​e​r​D​i​d​n​'​t​L​i​k​e​M​e​A​n​y​w​a​y, Thought'YaKnew, Z.A, Zettel’sTraum, 、の, 」な, ウォルト・ディズニー, エル・グレコ, オート・ガロンヌ, オードリー・ヘプバーン, カサ・サンタ・マルタ, カステルフランコ・ヴェネト, サン・ゴーダン, シガー・ロス, シー・オブ・ジ・アンティレス, ジョン・ディ・ドメニコ, スティーラーズ・ホイール, ストレンジャー・シングズ, トーキング・デッド, ド・ゴール, ハーバード・ビジネス・スクール, バハ・カリフォルニヤ, ヒラリー・クリントン, フェデリコ・フェリーニ, フランツ・ヨーゼフ, プンタ・デル・エステ, プンタ・ラサ, マラー/サド, メラニア・トランプ, ラッセ・ハルストレム, ル・コント, ルーカス・クラナッハ</li>
</ul>

<ul>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 15 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>SYM</a>, <a>VERB</a></li>
<li>This corpus does not use the following tags: INTJ, X</li>
</ul>

<ul>
<li>This corpus contains 19 word types tagged as particles (PART): 、の, か, かい, かどうか, さ, とともに, と共に, に, において, における, にとって, の, ん, 最大, 最高, 第, 紀元前, 約, 翌</li>
</ul>

<ul>
<li>This corpus contains 26 lemmas tagged as pronouns (PRON): あなた, いずれ, かれら, ここ, これ, これら, そこ, その他, それ, それぞれ, それら, どこ, どちら, どれ, みなさん, よそ, 君たち, 彼, 彼ら, 彼女, 我々, 皆, 私, 私たち, 私達, 誰</li>
</ul>

<ul>
<li>This corpus contains 4 lemmas tagged as determiners (DET): あの, この, その, どの</li>
</ul>

<ul>
</ul>

<ul>
<li>This corpus contains 47 lemmas tagged as auxiliaries (AUX): *使役*, *可能*, ある, いく, いる, う, うる, おる, かける, かもしれる, くれる, させる, しまう, しめる, すぎる, する, せる, そうだ, た, たい, たら, たろ, だ, できる, でした, ない, なければ, なさる, なら, なる, べし, ます, やすい, ゆく, よい, ようだ, らしい, られる, れる, 出す, 化, 始める, 来る, 終える, 続ける, 良い, 行く</li>
</ul>

<ul>
<li>Out of the above, 17 lemmas occurred sometimes as AUX and sometimes as VERB: ある, いく, いる, かける, する, せる, できる, なさる, なる, ます, 出す, 化, 始める, 来る, 終える, 続ける, 行く</li>
</ul>

<ul>
<li>There are 2 <a href="../feat/VerbForm.html">(de)verbal forms:</a></li>
</ul>

<ul>
  <li>Fin
  <ul>
    <li>ADJ: ない, 低い, 素晴らしい, いい, 多い, 少ない, 弱い, 良い, 速い, 高い</li>
    <li>AUX: た, いる, ます, である, する, だ, う, ない, です, よう</li>
    <li>NOUN: よう</li>
    <li>VERB: ある, なる, いる, 思う, 言う, いう, 始まる, いえる, かかる, する</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Ger
  <ul>
    <li>ADJ: なく, なかっ, 上手く, 大きく, うまく, 余儀なく, 少なく, 広く, 著しく, 間違いなく</li>
    <li>ADP: で, に</li>
    <li>AUX: し, い, に, れ, まし, であっ, おり, だっ, られ, なかっ</li>
    <li>NOUN: やり方, 働き, 控えめ, 支え, 暮らし, 渡り, 買い物</li>
    <li>SCONJ: で</li>
    <li>VERB: し, あり, なっ, 述べ, 言っ, 受け, あっ, 語っ, なり, 戻っ</li>
  </ul>
  </li>
</ul>

<h3>Nominal Features</h3>




<ul>
  <li><a>Number</a></li>
</ul>

<ul>
  <li>Plur
    <ul>
      <li>NOUN: 自身</li>
      <li>PRON: 彼ら, これら, 私たち, それら, 私達, 我々, かれら, みなさん, 君たち, 皆</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Case</a></li>
</ul>

<ul>
  <li>Acc
    <ul>
      <li>ADP: を</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Advb
    <ul>
      <li>ADP: に, で, から, と, へ, について, により, に対する, より, によって</li>
      <li>AUX: に, で</li>
      <li>PART: において, における, にとって, と共に, とともに, に</li>
      <li>SCONJ: と</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Comp
    <ul>
      <li>ADP: と, に, という</li>
      <li>AUX: に</li>
      <li>SCONJ: と</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Gen
    <ul>
      <li>ADP: の</li>
      <li>AUX: の</li>
      <li>PART: の</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Nom
    <ul>
      <li>ADP: が</li>
    </ul>
  </li>
</ul>



<h3>Degree and Polarity</h3>



<ul>
  <li><a>Polarity</a></li>
</ul>

<ul>
  <li>Neg
    <ul>
      <li>AUX: ない, なかっ, ず, ん, なく, あり</li>
      <li>AUX-Fin: ない, ん, ず</li>
      <li>AUX-Ger: なかっ, ず, なく, あり</li>
      <li>NOUN: こと</li>
    </ul>
  </li>
</ul>


<h3>Verbal Features</h3>




<ul>
  <li><a>Tense</a></li>
</ul>

<ul>
  <li>Past
    <ul>
      <li>AUX: た, だ, たら</li>
      <li>AUX-Fin: た, だ</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Voice</a></li>
</ul>

<ul>
  <li>Cau
    <ul>
      <li>AUX: せ, せる, させ, させる, しめ</li>
      <li>AUX-Fin: せる</li>
      <li>AUX-Ger: せ, させ, しめ</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pass
    <ul>
      <li>AUX: れ, れる, られ, られる, れれ</li>
      <li>AUX-Fin: れる, られる</li>
      <li>AUX-Ger: れ, られ</li>
    </ul>
  </li>
</ul>


<h3>Pronouns, Determiners, Quantifiers</h3>






<ul>
  <li><a>Person</a></li>
</ul>

<ul>
  <li>1
    <ul>
      <li>NOUN: うち, 自分</li>
      <li>PRON: 私, 私たち, 我々, 私達</li>
    </ul>
  </li>
</ul>

<ul>
  <li>2
    <ul>
      <li>PRON: あなた, 君たち</li>
    </ul>
  </li>
</ul>

<ul>
  <li>3
    <ul>
      <li>NOUN: 自身, 自分, 自ら, やつ, 本人</li>
      <li>PRON: 彼, それ, 彼女, これ, 彼ら, そこ, これら, ここ, それら, かれら</li>
    </ul>
  </li>
</ul>




<h3>Other Features</h3>


<ul>
  <li><a>Form</a>
    <ul>
      <li>Adn
        <ul>
          <li>ADJ: 新しい, 高い, ない, 素晴らしい, 厳しい, 古い, 若い, 深い, いい, 低い</li>
          <li>AUX: な, た, する, いる, である, ない, れる, せる, だ, できる</li>
          <li>VERB: ある, なる, する, 使う, 含む, 得る, 持つ, 続く, 見る, いう</li>
        </ul>
      </li>
      <li>Irr
        <ul>
          <li>AUX: さ, い, だろ, し, ませ, であろ, でき, られ, おら, れ</li>
          <li>VERB: 知ら, 考え, 行わ, 信じ, 思わ, 使わ, し, でき, 呼ば, い</li>
        </ul>
      </li>
      <li>Real
        <ul>
          <li>ADJ: なけれ</li>
          <li>AUX: いれ, たら, であれ, なら, れれ</li>
          <li>VERB: なれ, やめれ, 見れ</li>
        </ul>
      </li>
      <li>Spcf
        <ul>
          <li>ADJ: 堅苦し</li>
          <li>AUX: べき</li>
          <li>NOUN: 高さ, 美しさ, 長さ</li>
          <li>VERB: 明るみ</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 1 lemmas as copulas (<a>cop</a>). Examples: だ.</li>
</ul>

<ul>
<li>This corpus uses 47 lemmas as auxiliaries (<a>aux</a>). Examples: た, する, だ, いる, れる, こと, ない, ます, ようだ, う, られる, せる, なる, おる, 来る, できる, たい, べし, 始める, かもしれる, さ, *可能*, しまう, なければ, 続ける, すぎる, たら, 化, いく, かける, くれる, させる, そうだ, でした, 出す, *使役*, うる, しめる, たろ, なさる, なら, やすい, ゆく, らしい, 終える, 良い, 行く.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB--NOUN-ADP(が) (183)</li>
      <li>VERB--NOUN-ADP(と)-ADP(は) (4)</li>
      <li>VERB--NOUN-ADP(など)-ADP(が) (2)</li>
      <li>VERB--NOUN-ADP(の)-ADP(が) (1)</li>
      <li>VERB--NOUN-ADP(は) (208)</li>
      <li>VERB--NOUN-ADP(より)-ADP(は) (1)</li>
      <li>VERB--PRON-ADP(が) (17)</li>
      <li>VERB--PRON-ADP(は) (65)</li>
      <li>VERB--PRON-ADP(も)-ADP(が) (1)</li>
      <li>VERB-Fin--NOUN-ADP(が) (57)</li>
      <li>VERB-Fin--NOUN-ADP(にとって)-ADP(は) (2)</li>
      <li>VERB-Fin--NOUN-ADP(は) (26)</li>
      <li>VERB-Fin--PRON-ADP(が) (2)</li>
      <li>VERB-Fin--PRON-ADP(は) (13)</li>
      <li>VERB-Ger--NOUN-ADP(が) (97)</li>
      <li>VERB-Ger--NOUN-ADP(だけ)-ADP(は) (1)</li>
      <li>VERB-Ger--NOUN-ADP(と)-ADP(は) (1)</li>
      <li>VERB-Ger--NOUN-ADP(など)-ADP(が) (1)</li>
      <li>VERB-Ger--NOUN-ADP(に関して)-ADP(は) (1)</li>
      <li>VERB-Ger--NOUN-ADP(の)-ADP(が) (1)</li>
      <li>VERB-Ger--NOUN-ADP(は) (141)</li>
      <li>VERB-Ger--NOUN-ADP(まで)-ADP(も)-ADP(が) (1)</li>
      <li>VERB-Ger--PRON-ADP(が) (11)</li>
      <li>VERB-Ger--PRON-ADP(と)-ADP(は) (1)</li>
      <li>VERB-Ger--PRON-ADP(の) (1)</li>
      <li>VERB-Ger--PRON-ADP(は) (66)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB--NOUN-ADP(など)-ADP(を) (1)</li>
      <li>VERB--NOUN-ADP(の)-ADP(を) (1)</li>
      <li>VERB--NOUN-ADP(を) (441)</li>
      <li>VERB--NOUN-ADP(を)-ADP(はじめ) (1)</li>
      <li>VERB--PRON (1)</li>
      <li>VERB--PRON-ADP(を) (11)</li>
      <li>VERB-Fin--NOUN-ADP(を) (19)</li>
      <li>VERB-Ger--NOUN-ADP(だけ)-ADP(を) (1)</li>
      <li>VERB-Ger--NOUN-ADP(など)-ADP(を) (1)</li>
      <li>VERB-Ger--NOUN-ADP(の)-ADP(を) (1)</li>
      <li>VERB-Ger--NOUN-ADP(を) (227)</li>
      <li>VERB-Ger--NOUN-ADP(を)-ADP(も) (1)</li>
      <li>VERB-Ger--PRON-ADP(を) (7)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
      <li>VERB--NOUN-ADP(だけ)-ADP(に) (1)</li>
      <li>VERB--NOUN-ADP(に) (260)</li>
      <li>VERB--NOUN-ADP(に)-ADP(は) (35)</li>
      <li>VERB--NOUN-ADP(に)-ADP(も) (6)</li>
      <li>VERB--NOUN-ADP(のみ)-ADP(に) (2)</li>
      <li>VERB--NOUN-ADP(まで)-ADP(に) (1)</li>
      <li>VERB--PRON-ADP(に) (13)</li>
      <li>VERB--PRON-ADP(に)-ADP(も) (1)</li>
      <li>VERB-Fin--NOUN-ADP(に) (35)</li>
      <li>VERB-Fin--NOUN-ADP(に)-ADP(は) (10)</li>
      <li>VERB-Fin--NOUN-ADP(に)-ADP(も) (1)</li>
      <li>VERB-Fin--PRON-ADP(に) (3)</li>
      <li>VERB-Fin--PRON-ADP(に)-ADP(は) (1)</li>
      <li>VERB-Ger--NOUN-ADP(に) (141)</li>
      <li>VERB-Ger--NOUN-ADP(に)-ADP(しか) (1)</li>
      <li>VERB-Ger--NOUN-ADP(に)-ADP(は) (16)</li>
      <li>VERB-Ger--NOUN-ADP(まで)-ADP(に) (1)</li>
      <li>VERB-Ger--PRON-ADP(に) (6)</li>
      <li>VERB-Ger--PRON-ADP(に)-ADP(は) (2)</li>
      <li>VERB-Ger--PRON-ADP(に)-ADP(も) (1)</li>
    </ul>
  </li>
</ul>




<h3>Relations Overview</h3>

<ul>
<li>This corpus does not use relation subtypes.</li>
<li>The following 14 relation types are not used in this corpus at all: <a>xcomp</a>, <a>vocative</a>, <a>expl</a>, <a>dislocated</a>, <a>discourse</a>, <a>appos</a>, <a>clf</a>, <a>conj</a>, <a>flat</a>, <a>list</a>, <a>parataxis</a>, <a>orphan</a>, <a>goeswith</a>, <a>reparandum</a></li>
</ul>
