---
transition: fade-out
---

<div class="w-full h-full flex justify-center items-center relative">
  <img class="w-full h-full object-contain" src="/images/login/01.png">
  <div class="absolute left-9 top-[30px]">
    <Mark type="circle" :at="1" width="270" height="300" top="48" />
  </div>
  <div v-click="2" class="absolute bottom-5 left-20">
    登入帳號密碼開始使用
  </div>
</div>

---
transition: fade-out
---

<div class="w-full h-full flex justify-center items-center relative">
  <img class="w-full h-full object-contain" src="/images/login/02.png">
  <div class="absolute left-12 top-[50px]">
    <Mark type="circle" :at="1" width="240" height="270" top="48" />
  </div>
  <div v-click="2" class="absolute bottom-0 left-12">
    若有開啟二次驗證則需要
    <br />
    透過驗證應用程式輸入驗證碼
    <br/>
    例如：Google Authenticator
  </div>
</div>