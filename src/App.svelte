<script lang="ts">
  import TailwindCss from './TailwindCSS.svelte'
  import githubIcon from './assets/github.png'
  import qiitaIcon from './assets/qiita.png'
  import twitterIcon from './assets/twitter.png'
  import profileIcon from './assets/profile.png'
  import product1Icon from './assets/product1.png'
  import product2Icon from './assets/product2.png'
  import product3Icon from './assets/product3.png'
  import product4Icon from './assets/product4.png'
</script>

<TailwindCss />

<main>
  <header class="flex sticky top-0 z-50 h-12 bg-black justify-center items-center">
    <p class="text-white text-2xl">Rei Tamura's PortForio</p>
  </header>
  <!-- start main -->
  <div class="bg-gray-200 sm:py-12 py-6">
    <!-- start about -->
    <div class="bg-white flex sm:p-8 p-4 flex-col items-center sm:mb-12 sm:mx-10 mb-6 mx-5">
      <p class="text-2xl mb-2">自己紹介~About~</p>
      <div class="flex flex-col sm:flex-row items-center">
        <div class="sm:mr-16 mb-3 sm:mb-0">
          <img src={profileIcon} alt="profile" class="rounded-full h-[160px] w-[160px] flex items-center justify-center"/>
        </div>
        <div class="flex flex-col justify-center">
          <p class="sm:text-xl text-lg mb-1">名前：田村　黎</p>
          <p class="sm:text-xl text-lg mb-1">学歴：千葉工業大学工学部未来ロボティクス学科</p>
          <p class="sm:text-xl text-lg mb-1">職歴：フルスタックエンジニア四年目</p>
          <p class="sm:text-xl text-lg mb-1">16Personalities：討論者（ENTP-A / ENTP-T）</p>
          <p class="sm:text-xl text-lg mb-1">趣味：ラーメン巡り、ランニング、バドミントン、アニメ鑑賞</p>
        </div>
      </div>
    </div>
    <!-- end about -->
    <!-- start skill -->
    <div class="bg-white flex sm:p-8 p-4 flex-col items-center sm:mb-12 sm:mx-10 mb-6 mx-5">
      <p class="text-2xl mb-4">技術要素~Skill~</p>
        <div class="flex flex-col sm:flex-row items-center sm:w-[820px] w-full">
          <div class="border-solid border-4 border-blue-400 p-6 sm:h-[300px] sm:w-[400px] w-full sm:mr-8 mb-12">
            <p class="text-xl text-center mb-6 mt-[-40px] sm:mx-20 mx-12 bg-white">フロントエンド</p>
            <p class="text-xl">HTML：業務経験3年半</p>
            <p class="text-xl ">CSS：業務経験3年半</p>
              <p class="text-l text-gray-800">・Sass：業務経験半年</p>
            <p class="text-xl">JavaScript：業務経験3年半</p>
              <p class="text-l text-gray-800">・React：業務経験2年半</p>
              <p class="text-l text-gray-800">・Vue：業務経験半年</p>
              <p class="text-l text-gray-800">・Svelte：独学で勉強中</p>
              <p class="text-l text-gray-800">・React Native：独学で勉強中</p>
          </div>
          <div class="border-solid border-4 border-blue-400 p-6 sm:h-[300px] sm:w-[400px] w-full mb-12">
            <p class="text-xl text-center mb-6 mt-[-40px] sm:mx-20 mx-12 bg-white">バックエンド</p>
            <p class="text-xl">Java：業務経験2年半</p>
            <p class="text-l text-gray-800">・Play Framework：業務経験2年半</p>
            <p class="text-l text-gray-800">・Spring Framework：業務経験半年</p>
            <p class="text-xl">Python：業務経験半年</p>
              <p class="text-l text-gray-800">・Django：業務経験半年</p>
              <p class="text-l text-gray-800">・Flask：独学で勉強中</p>
            <p class="text-xl">Rust：独学で勉強中</p>
          </div>
        </div>
        <div class="flex flex-col sm:flex-row items-center sm:w-[820px] w-full">
          <div class="border-solid border-4 border-blue-400 p-6 sm:h-[300px] sm:w-[400px] w-full sm:mr-8 mb-12">
            <p class="text-xl text-center mb-6 mt-[-40px] sm:mx-20 mx-12 bg-white">その他</p>
            <p class="text-xl">DB・SQL：業務経験3年半</p>
            <p class="text-l text-gray-800">・MySQL：業務経験2年半</p>
            <p class="text-l text-gray-800">・DynamoDB：業務経験1年</p>
            <p class="text-l text-gray-800">・PosgleSQL：業務経験半年</p>
            <p class="text-l text-gray-800">・Oracle DataBase：社内研修で学習</p>
          <p class="text-xl">Unity：独学で勉強中</p>
            <p class="text-xl">Google Analytics、Git、Dockerを業務で使用経験あり</p>
          </div>
          <div class="border-solid border-4 border-blue-400 p-6 sm:h-[300px] sm:w-[400px] w-full mb-12">
            <p class="text-xl text-center mb-6 mt-[-40px] sm:mx-20 mx-12 bg-white">資格</p>
            <p class="text-xl">・Java SE 8 Programmer II</p>
            <p class="text-xl">・ORACLE MASTER Bronze Oracle Database 12c</p>
            <p class="text-xl">・Google アナリティクス個人認定資格</p>
          </div>
        </div>
    </div>
    <!-- end skill -->
    <!-- start product -->
    <div class="bg-white flex sm:p-8 p-4 flex-col items-center sm:mx-10 mx-5">
      <p class="text-2xl mb-4">製作物~Product~</p>
      <div class="sm:flex">
        <div class="border-solid border-4 border-blue-400 p-6 sm:w-[380px] w-full sm:mr-8 mb-8">
          <p class="text-xl text-center mb-2">Omomuki Shorts</p>
          <p class="text-xl">使用技術：React、AWS Amplify</p>
          <p class="text-xl">技術選定・要件詰め・開発業務を担当</p>
        </div>
        <div class="p-2 sm:w-[380px] w-full mb-8">
          <img src={product1Icon} alt="Omomuki Shorts" />
        </div>
      </div>
      <div class="sm:flex">
        <div class="border-solid border-4 border-blue-400 p-6 sm:w-[380px] w-full sm:mr-8 mb-8">
          <p class="text-xl text-center mb-2">PortForio</p>
          <p class="text-xl">使用技術：Svelte、vite</p>
        </div>
        <div class="p-2 sm:w-[380px] w-full mb-8">
          <img src={product2Icon} alt="PortForio" />
        </div>
      </div>
      <div class="sm:flex">
        <div class="border-solid border-4 border-blue-400 p-6 sm:w-[380px] w-full sm:mr-8 mb-8">
          <p class="text-xl text-center mb-2">Strelka Blog</p>
          <p class="text-xl">使用技術：Gatsby</p>
        </div>
        <div class="p-2 sm:w-[380px] w-full mb-8">
          <img src={product3Icon} alt="StrelkaBlog" />
        </div>
      </div>
      <div class="sm:flex">
        <div class="border-solid border-4 border-blue-400 p-6 sm:w-[380px] w-full sm:mr-8 mb-8">
          <p class="text-xl text-center mb-2">フォトマ（開発途中）</p>
          <p class="text-xl">使用技術：React Native、Flask、Docker、OpenCV</p>
        </div>
        <div class="p-2 sm:w-[380px] w-full mb-8">
          <img src={product4Icon} alt="PhotoMa" />
        </div>
      </div>
    </div>
    <!-- end product -->
  </div>
  <!-- end main -->
  <footer class="flex sticky bottom-0 h-12 bg-black items-center">
    <p class="text-white sm:ml-6 ml-3 text-2xl">Contact</p>
    <p class="text-white sm:ml-4 ml-2">rei0420.run@gmail.com</p>
    <a class="sm:ml-4 ml-3 w-6" href="https://twitter.com/ReiTamura0420">
      <img src={twitterIcon} alt="twitter"/>
    </a>
    <a class="ml-2 w-6" href="https://github.com/reitamura0420">
      <img src={githubIcon} alt="github" />
    </a>
    <a class="ml-2 w-6" href="https://qiita.com/ReiTamura">
      <img src={qiitaIcon} alt="qiita" />
    </a>
  </footer>
</main>