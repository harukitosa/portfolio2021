<template>
  <div class="wrapper">
    <div class="container m-auto md:p-20 p-4 pt-8">
      <div>
        <h1 class="text-4xl">
          Haruki Tosa
        </h1>
        <div>
          <p>2000/3/28</p>
          <p>Web developer</p>
          <p>Meiji University Department of Computer Science</p>
        </div>
        <div class="pt-20">
          <h2 class="text-3xl">
            contact
          </h2>
          <div>
            <a class="text-black" href="https://twitter.com/tosa_now"
              >- twitter</a
            >
          </div>
          <div>
            <a class="text-black" href="https://github.com/harukitosa"
              >- github</a
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
        <span>2020/10 ~ </span>
        <div class="text-gray-500 container pt-4 pb-8">
          学生でソフトウェア開発をしているエンジニアさんの時給を匿名で公開する掲示板サイト。<br />
          技能を持った学生が適切な給与かどうかを判断できる、
          インターンシップ、アルバイトを探している学生の意思決定の手助けになれるようなサイト運営を目指しています。
          インターンシップの情報や詳細はエンジニアの共有する文化のおかげで現在でも良質なブログ記事や情報を検索によって見つけることができます。
          その詳細な過去のブログに行き当たる前の、全体的な情報の俯瞰できる場になれたらと考えています。<br />
          1月にはインターンシップの口コミを投稿できるように機能追加をする予定です。
        </div>
        <a href="https://student-salary.com">
          <p class="pt-4 pb-2">Top</p>
          <img src="student-salary-1.png" alt="top" width="800" />
        </a>
        <p class="pt-4 pb-2">一覧画面</p>
        <img src="student-salary-2.png" alt="top" width="800" />

        <div class="pt-8">
          <p>使用技術</p>
          <p class="text-gray-500">Nuxt, Firestore, cloudfunction</p>
        </div>
      </div>
      <!-- works -->
    </div>
  </div>
</template>

<script></script>

<style scoped>
.wrapper {
  position: fixed;
  z-index: 10;
  box-sizing: border-box;
  border: solid 10px black;
  border-radius: 100px 0 100px 0;
  overflow-y: scroll;
  top: 5px;
  bottom: 5px;
  right: 5px;
  left: 5px;
}
</style>
