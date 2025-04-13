<div class="flex flex-col justify-center items-center w-full h-full relative">
  <h1 class="title">那麼，有誰可以設定模型、代理呢？</h1>
</div>

---
transition: fade-out
---

<div class="w-full h-full flex justify-center items-center relative">
  <img class="w-full h-full object-contain" src="/images/manage/01.png">
  <Mark type="circle" :at="1" width="70" height="40" top="70" right="115" />
</div>

---
transition: fade-out
---

<div class="w-full h-full flex justify-center items-center relative">
  <img class="w-full h-full object-contain" src="/images/manage/02.png">
</div>
<div v-click class="absolute bottom-20 left-[400px]">
  透過建立群組來設定可操作範圍
</div>

---
transition: fade-out
---

<div class="w-full h-full flex justify-center items-center relative">
  <img class="w-full h-full object-contain" src="/images/manage/03.png">
  <Mark type="circle" width="70" height="40" top="70" right="115" />
</div>
<div v-click="2" class="absolute top-[320px] left-1/2">
  建立帳號來新增使用者
</div>

---
transition: fade-out
---

<div class="w-full h-full flex justify-center items-center relative">
  <img class="w-full h-full object-contain" src="/images/manage/04.png">
</div>
<Mark type="underline" :at="1" width="180" height="40" top="330" right="125" />
<div v-click class="absolute bottom-28 right-[110px]">
  選擇剛剛建立的群組來
  <br/>
  限制使用者可操作的範圍
</div>