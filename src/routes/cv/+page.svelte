<script>
	import "../../app.css";
</script>
<svelte:head>
	<title>履歴書</title>
	<meta name="description" content="履歴書作ってみる" />
</svelte:head>

<div class="flex">
     <div class="w-full mx-auto bg-white p-14 rounded-md shadow-md relative">
          <!-- 画像 -->
          <div class="border w-[104px] h-[132px] absolute right-20 bg-slate-100"></div>

          <!-- 履歴書本体 -->
          <div class="page-1 w-[595px] h-[842px] border font-serif">

               <!-- ヘッダー的なやつ -->     
               <div>     
                    <div class="w-[450px] flex justify-between items-end">
                         <h3 class="text-2xl pl-2">履歴書</h3>
                         <p class="text-xs">年<span class="px-6">月</span>日現在</p>
                    </div>
                    <div class="border-t-2 border-l-2 border-r-2 border-black  w-[450px] flex">
                         <div class="w-[370px]">
                              <div class="border-b border-r border-black pl-1 text-xs py-1">ふりがな</div>
                              <div class="border-b border-r border-black pl-1 py-4 text-sm">氏 名</div>
                         </div>
                         <div class="border-b border-black w-[80px] flex justify-center items-center text-sm">男・女</div>
                    </div>

                    <div class="border-l-2 border-r-2 border-b border-black w-[450px] text-xs flex justify-between">
                         <p class="pl-1 py-1">生年月日</p>
                         <p class="pl-1 py-1">　年　　　月　　　日生（満　　　歳）</p>
                    </div>
                    <div class="flex border-l-2 border-r-2 border-black">
                         <p class="w-[450px] pl-1 py-1 text-xs">ふりがな</p>
                         <p class="border-l border-t-2 border-black w-[145px] pl-1 py-1 text-xs">電話</p>
                    </div>
                    <div class="flex border-l-2 border-t border-b border-r-2 border-black">
                         <p class="w-[450px] pl-1 py-1 text-xs leading-6">現住所（〒　　　-　　　　）<br>　ああ　　　　　</p>
                         <p class="border-l border-black w-[145px] pl-1 py-1 text-xs leading-6">E-mail<br>b</p>
                    </div>
                    <div class="flex border-b border-l-2 border-r-2 border-black">
                         <p class="w-[450px] pl-1 py-1 text-xs">ふりがな</p>
                         <p class="border-l border-black w-[145px] pl-1 py-1 text-xs">電話</p>
                    </div>
                    <div class="flex border-l-2 border-r-2 border-black">
                         <p class="border-b-2 border-black w-[450px] pl-1 py-1 text-xs leading-6">連絡先（〒　　　-　　　　）<br>　ああ　　　　　</p>
                         <p class="border-b-2 border-l border-black w-[145px] pl-1 py-1 text-xs leading-6">E-mail<br>b</p>
                    </div>
               </div>


          </div>
     </div>
</div>
