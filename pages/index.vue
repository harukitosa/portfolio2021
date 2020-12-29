<template>
  <div class="wrapper pt-12 text-black">
    <div class="container m-auto md:p-20 p-4 pt-8 ">
      <div>
        <h1 class="text-4xl">
          Haruki Tosa
        </h1>
        <div>
          <p>2000/3/28</p>
          <p>Web developer</p>
          <p>Meiji University Department of Computer Science</p>
        </div>
        <div class="pt-20 text-gray-600" style="max-width:600px;">
          何かを作るのと、何かについて話すことが大好きです。<br />
          一人でほっといても永遠に喋り続けます<br />
          特にWebの技術について学んだり、開発したり、遊んだりするのが好きです。<br />
          ブランコに乗ることが好きです。<br />
          抹茶のハーゲンダッツが好きです。<br />
          読む予定のない本を買うことが好きです<br />
          物語の中に出てくる夏休みが好きです。<br />
          数式を書いたり問題を解いたりするのが好きです<br />
          新しいものが好きです。<br />
        </div>
        <div class="pt-20 text-lg">
          <h2 class="text-3xl">
            link
          </h2>
          <div>
            <a
              class="text-black hover:text-blue-400"
              href="https://twitter.com/tosa_now"
              >- twitter</a
            >
          </div>
          <div>
            <a
              class="text-black hover:text-blue-400"
              href="https://github.com/harukitosa"
              >- github</a
            >
          </div>
          <div>
            <a
              class="text-black hover:text-blue-400"
              href="https://harukitosa.com"
              >- blog</a
            >
          </div>
          <div>
            <a
              class="text-black hover:text-blue-400"
              href="https://zenn.dev/tosa"
              >- zenn</a
            >
          </div>
        </div>
      </div>

      <!-- works -->
      <div class="pt-40">
        <h2 class="text-3xl">Works</h2>
      </div>

      <div>
        <h2 class="text-3xl">StudentSalary</h2>
        <span>2020/10 ~ </span><br />
        <span
          ><a
            class="text-black hover:text-blue-400 text-lg"
            href="https://student-salary.com"
            >https://student-salary.com</a
          ></span
        >
        <div
          class="text-gray-600 container pt-4 pb-8"
          style="max-width: 800px;"
        >
          学生でソフトウェア開発をしているエンジニアさんの時給を匿名で公開する掲示板サイト。<br />
          技能を持った学生が適切な給与かどうかを判断できる、
          インターンシップ、アルバイトを探している学生の意思決定の手助けになれるようなサイト運営を目指しています。
          インターンシップの情報や詳細はエンジニアの共有する文化のおかげで現在でも良質なブログ記事や情報を検索によって見つけることができます。
          その詳細な過去のブログに行き当たる前の、全体的な情報の俯瞰できる場になれたらと考えています。<br />
          1月にはインターンシップの口コミを投稿できるように機能追加をする予定です。
        </div>
        <p class="pt-4 pb-2">Top</p>
        <img src="student-salary-1.png" alt="top" width="800" />
        <p class="pt-4 pb-2">一覧画面</p>
        <img src="student-salary-2.png" alt="top" width="800" />

        <div class="pt-8">
          <p>使用技術</p>
          <p class="text-gray-600">Nuxt, Firestore, cloudfunction</p>
        </div>
      </div>

      <div class="pt-12">
        <h2 class="text-3xl">きみの宗教.com</h2>
        <span>2020/10 ~ </span><br />
        <span
          ><a
            class="text-black hover:text-blue-400 text-lg"
            href="https://xn--w8j6c4b707y4gk.com/"
            >https://きみの宗教.com/</a
          ></span
        >
        <div
          class="text-gray-600 container pt-4 pb-8"
          style="max-width: 800px;"
        >
          誰でも気軽に教祖になれる！をキャッチコピーに作成したアイデアドリブンのサイト<br />
          TwitterOGPによるアプリケーション制作がは流行したいたため、何か作ってみたいと思い作成。<br />
          将来的に改修or撤収予定<br />
          個人的には宗教法人が設立できる作業までネット上でできたらなと思っていますが、開発者本人が設立したことがないためその辺りのドメイン知識がある方がいましたらご連絡ください。
        </div>
        <a href="https://xn--w8j6c4b707y4gk.com/">
          <p class="pt-4 pb-2">Top</p>
          <img src="kimi-syukyou.png" alt="top" width="800" />
        </a>

        <div class="pt-8">
          <p>使用技術</p>
          <p class="text-gray-600">Nuxt, Firestore</p>
        </div>
      </div>
      <!-- works -->

      <!-- skill -->
      <div class="pt-20">
        <h2 class="text-3xl">Skill</h2>
        <span class="text-xl">- language</span>
        <div class="text-lg">
          Go, PHP, Ruby, Dart, Javascript, C, C++
        </div>

        <span class="text-xl">- framework</span>
        <div class="text-lg">
          Gin, Echo, Ruby on Rails, Laravel, Vue, React, Flutter
        </div>

        <div class="pt-4 text-gray-600">
          アーキテクチャなどを考えるのが好きです。<br />
          何を作るか？なぜ作るか？何を使ってつくるのか？<br />
          なぜその設計なのか？を考えるよう心がけています。<br />
          新しいものが大好きなので技術のキャッチアップも意識的に行っています。<br />
          学習方針としてはまず動かすそれから仕組みを学ぶです。<br />
          情報技術は範囲が広いため興味を持った部分以外は必要呼び出しで学習していきたいと考えています。
        </div>
      </div>
      <!-- skill -->

      <!-- intern -->
      <div class="pt-20">
        <h2 class="text-3xl">Intern</h2>
        <div>
          <div>
            <p>- CyberAgent 2days</p>
            <p>- Mercari Online Summer Internship for Gophers 2020</p>
            <p>- DMM guild</p>
            <p>- 株式会社ゆめみ</p>
          </div>
        </div>
      </div>
      <!-- intern -->

      <!-- intern -->
      <div class="pt-20">
        <h2 class="text-3xl">WorksExperience</h2>
        <div>
          <div>
            <p>- Monokrom</p>
          </div>
        </div>
      </div>
      <!-- intern -->

      <!-- contact -->
      <div class="pt-20">
        <h2 class="text-2xl">Contact</h2>
        TwitterのDMでお待ちしています
      </div>
      <!-- contact -->
    </div>
  </div>
</template>

<script></script>

<style scoped>
.wrapper {
  position: fixed;
  z-index: 10;
  box-sizing: border-box;
  border: solid 7px black;
  border-radius: 100px 0 0 0;
  overflow-y: scroll;
  top: 5px;
  bottom: 5px;
  right: 5px;
  left: 5px;
}
</style>
