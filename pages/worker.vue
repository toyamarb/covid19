<template>
  <div class="Worker">
    <page-header class="mb-3">
      {{ $t('企業の皆様・はたらく皆様へ') }}
    </page-header>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1017/kj00021586.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{
            $t(
              '新型コロナウイルスの感染防止の観点からテレワーク導入を検討されている事業者の皆様へ'
            )
          }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '厚生労働省では、テレワークに関連する情報を一元化した『テレワーク総合ポータルサイト』を設け、テレワークに関する相談窓口、企業の導入事例紹介などテレワークの導入・活用に向けた各種情報を掲載していますので、参考にしてください。'
          )
        }}
      </p>
    </StaticCard>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1401/kj00021578.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{ $t('観光関連団体・事業者の皆様へ') }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '新型コロナウイルス感染症は、風邪や季節性インフルエンザ対策と同様にお一人お一人の咳エチケットや手洗いなどの実施がとても重要です。感染症対策に努めていただくようお願いいたします。'
          )
        }}
      </p>
    </StaticCard>
    <StaticCard>
      <h3>
        <a
          href="https://www.hataraku.metro.tokyo.jp/kansensyo/index.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{
            $t(
              ' 新型コロナウイルス感染症の拡大防止の観点からの個人事業税の申告期限の延長について'
            )
          }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '令和元年中の事業の所得に係る個人事業税の申告期限についても、同様に令和2年4月16日（木）まで延長することといたしましたのでお知らせします。'
          )
        }}
      </p>
    </StaticCard>

    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1107/kj00021713.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{
            $t(
              '新型コロナウィルス感染症の影響により納税が困難な方に対する県税における猶予制度 '
            )
          }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '新型コロナウィルス感染症に納税者（ご家族を含む。）がり患された場合のほか、新型コロナウィルス感染症に関連するなどして以下のようなケースに該当する場合は、猶予制度がありますので、富山県総合県税事務所にご相談ください（徴収の猶予：地方税法第15条）'
          )
        }}
      </p>
    </StaticCard>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1705/kj00021633.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{ $t('新型コロナウイルス感染症に関する情報（廃棄物関係） ') }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '新型コロナウイルス感染症に関する情報（廃棄物関係）については、関連ファイル等でご確認ください。'
          )
        }}
      </p>
    </StaticCard>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1211/kj00012035-002-01.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{ $t(' 介護サービス事業者向け情報（共通）') }}</a
        >
      </h3>
      <p>
        {{ $t('厚生労働省より事務連絡がありましたので、お知らせします。') }}
      </p>
    </StaticCard>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1209/kj00021543.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{ $t('新型コロナウイルスに関する通知等 ') }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '厚生労働省から各種事務連絡が発出されていますので、ご確認ください。'
          )
        }}
      </p>
    </StaticCard>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1207/kj00021396.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{ $t('新型コロナウイルス感染症への対応について ') }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '旅館業、住宅宿泊事業者及び食品等事業者の皆様は適切な対応をよろしくお願いいたします。'
          )
        }}
      </p>
    </StaticCard>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1301/kj00021653.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{
            $t(
              '事業者の皆様・働く皆様へ（金融・経営・雇用関係－新型コロナウイルス感染症対策） '
            )
          }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '県の制度融資に「新型コロナウイルス感染症対策枠」をご用意しています。'
          )
        }}
      </p>
    </StaticCard>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.toyama.jp/cms_sec/1611/kj00021682.html"
          target="_blank"
          rel="noopener noreferrer"
          >{{
            $t(
              '農林漁業者の皆様へ（金融関係-新型コロナウイルス感染症対策）（農林水産部） '
            )
          }}</a
        >
      </h3>
      <p>
        {{
          $t(
            '農林漁業経営の維持安定が困難な農林漁業者を対象に、農林漁業セーフティネット資金の貸付限度額の引上げ、貸付当初5年間の実質無利子化などの特例措置が行われていますのでご案内いたします'
          )
        }}
      </p>
    </StaticCard>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { MetaInfo } from 'vue-meta'
import StaticCard from '@/components/StaticCard.vue'
import PageHeader from '@/components/PageHeader.vue'

export default Vue.extend({
  components: {
    PageHeader,
    StaticCard
  },
  head(): MetaInfo {
    return {
      title: this.$t('企業の皆様・はたらく皆様へ') as string
    }
  }
})
</script>
