<script>
  import Broadcast from "$lib/icons/Broadcast.svelte";
  import Checkmark from "$lib/icons/Checkmark.svelte";
  import Heart from "$lib/icons/Heart.svelte";
  import Image from "$lib/icons/Image.svelte";
  import Map from "$lib/icons/Map.svelte";
  import Marginalia from "$lib/icons/Marginalia.svelte";
  import Rocket from "$lib/icons/Rocket.svelte";
  import Star from "$lib/icons/Star.svelte";
  import User from "$lib/icons/User.svelte";
  import Burgir from "$lib/icons/burgir.svelte";
</script>

<!-- 1st container -->
<div class=" flex place-content-center w-screen bg-[#ff8482]">
  <div class=" lg:w-[calc(100%-270px)] w-[calc(100%-30px)]">
    <!-- Nav -->
    <div class=" h-[80px] grid content-center w-full">
      <!-- Mobile -->
      <div class="flex w-full lg:hidden">
        <h3
          class=" grow font-Alfo h-full text-white text-[40px] leading-[48px]"
        >
          LOGO
        </h3>
        <div class="grid content-center h-full grow place-content-end">
          <Burgir />
        </div>
      </div>
      <!-- Desktop -->
      <div class="hidden w-full lg:flex">
        <h3
          class=" grow font-Alfo h-full text-white text-[40px] leading-[48px]"
        >
          LOGO
        </h3>
        <div class="grid content-center h-full grid-flow-col text-center">
          <div class="m-4 text-white">Portfolio</div>
          <div class="m-4 text-white">Contact</div>
        </div>
        <div class="grid content-center h-full grow place-content-end">
          <Burgir />
        </div>
      </div>
    </div>
    <!-- Mobile -->
    <div class="block w-full lg:hidden">
      <h5 class=" text-white font-[20px]">Delectus instructior</h5>
      <h2 class=" font-Alfo text-[56px] text-white">
        Vide legim- us consec- tetuer
      </h2>
      <input
        type="text"
        placeholder="Email"
        class=" p-4 h-[48px] w-full border-[1px] border-[#DADADA] rounded-[4px] mb-6"
      />
      <button
        class=" w-1/2 h-[48px] bg-white border-[2px] border-black rounded-[4px]"
        >Submit</button
      >
      <Image />
    </div>
    <!-- Desktop -->
  </div>
</div>

<!-- 2nd container -->
<div class=" flex place-content-center w-screen bg-[#fff2dd]">
  <div class=" lg:w-[calc(100%-270px)] w-[calc(100%-30px)]">
    <!-- Mobile -->
    <div class="w-full">
      <h5 class="mt-16 text-[#be6361] text-[20px] leading-6">Mel solum</h5>
      <h3 class="mt-4 text-[#333333] font-Alfo text-[40px] leading-[48px]">
        Mazim iudico
      </h3>
      <table class="mt-6">
        <tbody>
          <tr>
            <td class="grid content-start m-1"> <Heart /></td>
            <td class="text-[#333333] text-[16px] leading-6"
              >Bonorum minimum et sit tritani te, qui feugait electram</td
            >
          </tr>
          <tr>
            <td class="grid content-start m-1"> <Star /></td>
            <td class="text-[#333333] text-[16px] leading-6"
              >Cum ei assum tation homero mel corpora consectetuer</td
            >
          </tr>
          <tr>
            <td class="grid content-start m-1"> <Rocket /></td>
            <td class="text-[#333333] text-[16px] leading-6"
              >At per assum dicit verterem veri eripuit honestatis</td
            >
          </tr>
          <tr>
            <td class="grid content-start m-1"> <Broadcast /></td>
            <td class="text-[#333333] text-[16px] leading-6"
              >Lorem deterruisset ea vis expetenda has ex</td
            >
          </tr>
          <tr>
            <td class="grid content-start m-1"> <User /></td>
            <td class="text-[#333333] text-[16px] leading-6"
              >Usu eu hinc lorem inciderint minim movet quodsi</td
            >
          </tr>
        </tbody>
      </table>
      <button
        class=" w-1/2 mt-8 h-[48px] border-[2px] text-[#be6361] border-[#be6361] border-opacity-[31.58%] rounded-[4px]"
        >Get started</button
      >
      <img
        src="..\..\marginalia-coming-soon.svg"
        class="w-full scale-100"
        alt=""
      />
    </div>
    <!-- Desktop -->
  </div>
</div>

<!-- 3rd container -->
<div
  class=" flex place-content-center w-screen bg-[#3D201F] bg-cover bg-center"
  style="background-image: url('https://cdn.discordapp.com/attachments/1039638156837924915/1160602369487274014/Bitmap.png?ex=6535422f&is=6522cd2f&hm=744f6c8a24cd2449ed86fa1e137d1052a3025b856aec5da0fdeda8f5aa8d2db6&');  height: 448px"
>
  <div class=" w-full h-full bg-[#3D201F] bg-opacity-50">
    <div class=" lg:w-[calc(100%-270px)] w-[calc(100%-30px)]">
      <!-- Mobile -->
      <div class=" grid justify-center content-center h-[448px] w-full">
        <h5 class="   text-center text-[20px] text-white leading-6">
          Eos lobortis inimicus
        </h5>
        <h3
          class=" m-6 ml-0 mr-0 text-center text-[40px] text-white leading-[48px]"
        >
          Pro ad ubique erroribus in modo mutat sed
        </h3>
        <div class="flex place-content-center">
          <button
            class=" w-1/2 h-[48px] bg-white border-[2px] border-black rounded-[4px]"
            >Try now</button
          >
        </div>
      </div>
      <!-- Desktop -->
    </div>
  </div>
</div>

<!-- 4nd container -->
<div class=" flex place-content-center w-screen bg-[#fff2dd]">
  <div class=" lg:w-[calc(100%-270px)] w-[calc(100%-30px)]">
    <!-- Mobile -->
    <div class="w-full">
      <img
        src="..\..\marginalia-online-shopping.svg"
        class="w-full scale-100"
        alt=""
      />
      <h5 class="-mt-5 text-[#be6361] text-[20px] leading-6">Ei vix quot</h5>
      <h3 class="mt-4 text-[#333333] font-Alfo text-[40px] leading-[48px]">
        Suscipit natum
      </h3>

      <!-- table of content -->
      <div class="flex">
        <table class="w-1/2 mt-6 mb-8">
          <tbody class="w-full">
            <!-- row 1 -->
            <tr class="flex w-full mb-5 place-content-center">
              <td class="flex grow">
                <div class="grid content-start m-[6px] mr-4"><Checkmark /></div>
                <div class="text-[#333333] text-[16px] leading-6">
                  Usu vitae
                </div>
              </td>
            </tr>
            <!-- row 2 -->
            <tr class="flex w-full mb-5 place-content-center">
              <td class="flex grow">
                <div class="grid content-start m-[6px] mr-4"><Checkmark /></div>
                <div class="text-[#333333] text-[16px] leading-6">
                  Quidam officiis
                </div>
              </td>
            </tr>
            <!-- row 3 -->
            <tr class="flex w-full mb-5 place-content-center">
              <td class="flex grow">
                <div class="grid content-start m-[6px] mr-4"><Checkmark /></div>
                <div class="text-[#333333] text-[16px] leading-6">
                  Vel tollit
                </div>
              </td>
            </tr>
            <!-- row 4 -->
            <tr class="flex w-full place-content-center">
              <td class="flex grow">
                <div class="grid content-start m-[6px] mr-4"><Checkmark /></div>
                <div class="text-[#333333] text-[16px] leading-6">
                  Nihil tantas
                </div>
              </td>
            </tr>
          </tbody>
        </table>

        <table class="w-1/2 mt-6">
          <tbody class="w-full">
            <!-- row 1 -->
            <tr class="flex w-full mb-5 place-content-center">
              <td class="flex grow">
                <div class="grid content-start m-[6px] mr-4"><Checkmark /></div>
                <div class="text-[#333333] text-[16px] leading-6">
                  Decore ut
                </div>
              </td>
            </tr>
            <!-- row 2 -->
            <tr class="flex w-full mb-5 place-content-center">
              <td class="flex grow">
                <div class="grid content-start m-[6px] mr-4"><Checkmark /></div>
                <div class="text-[#333333] text-[16px] leading-6">
                  Similique sea ei
                </div>
              </td>
            </tr>
            <!-- row 3 -->
            <tr class="flex w-full mb-5 place-content-center">
              <td class="flex grow">
                <div class="grid content-start m-[6px] mr-4"><Checkmark /></div>
                <div class="text-[#333333] text-[16px] leading-6">Indoctum</div>
              </td>
            </tr>
            <!-- row 4 -->
            <tr class="flex w-full place-content-center">
              <td class="flex grow">
                <div class="grid content-start m-[6px] mr-4"><Checkmark /></div>
                <div class="text-[#333333] text-[16px] leading-6">
                  Platonem eos
                </div>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- Desktop -->
  </div>
</div>

<!-- Nav -->
<div class=" flex place-content-center w-screen bg-[#BE6361]">
  <div class=" lg:w-[calc(100%-270px)] w-[calc(100%-30px)]">
    <!-- Mobile -->
    <div class="w-full">
      <div class="flex place-content-center">
        <h3
          class="mt-44 mb-12 text-white text-center tracking-wide font-Alfo text-[40px] leading-[48px]"
        >
          Timeam scriptorem
        </h3>
      </div>
      <!-- office container -->
      <div
        class=" w-full place-content-center mb-4 h-[112px] bg-white border-[#E5E5E5] flex grid-flow-col"
        style="box-shadow: 0px 2px 8px 0px #0000001A;
        border-radius: 1px;"
      >
        <div
          class="grid h-full ml-8 mr-8 place-content-center justify-items-center"
        >
          <Map />
        </div>
        <div class="grow place-content-start">
          <div class="mt-5">
            <h4 class="text-2xl leading-10">Office</h4>
            <p class=" text-[16px] text-[#33333380]">
              Mel erat timeam, 123 45-67
            </p>
          </div>
        </div>
      </div>
      <!-- call us container -->
      <div
        class=" w-full place-content-center mb-4 h-[112px] bg-white border-[#E5E5E5] flex grid-flow-col"
        style="box-shadow: 0px 2px 8px 0px #0000001A;
        border-radius: 1px;"
      >
        <div
          class="grid h-full ml-8 mr-8 place-content-center justify-items-center"
        >
          <Map />
        </div>
        <div class="grow place-content-start">
          <div class="mt-5">
            <h4 class="text-2xl leading-10">Call us</h4>
            <p class=" text-[16px] text-[#33333380]">+1 234 567 89 00</p>
          </div>
        </div>
      </div>
      <!-- write us container -->
      <div
        class=" w-full place-content-center mb-4 h-[112px] bg-white border-[#E5E5E5] flex grid-flow-col"
        style="box-shadow: 0px 2px 8px 0px #0000001A;
        border-radius: 1px;"
      >
        <div
          class="grid h-full ml-8 mr-8 place-content-center justify-items-center"
        >
          <Map />
        </div>
        <div class="grow place-content-start">
          <div class="mt-5">
            <h4 class="text-2xl leading-10">Write us</h4>
            <p class=" text-[16px] text-[#333333]">info@gmail.com</p>
          </div>
        </div>
      </div>
      <h3 class=" mt-44 font-Alfo text-white text-[40px] leading-[48px]">
        LOGO
      </h3>
      <p class=" mt-4 mb-6 font-normal text-white text-[20px] leading-[32px]">
        Sit alii tantas viderer no. An mel nostrum appareat. Ad consul facilis
        est. Vix habeo scaevola percipitur ne, qui noster abhorreant ne.
      </p>
      <div class="flex h-7">
        <img class="mr-4" src="..\..\FB.svg" alt="" />
        <img class="mr-4" src="..\..\X.svg" alt="" />
        <img src="..\..\IG.svg" alt="" />
      </div>
      <div class="mt-24">
        <p class="mb-6 text-white">Habeo</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Scaevola</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Aliquam</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Noluisse</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Epicuri</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Detracto</p>
      </div>
      <div class="mt-16">
        <p class="mb-6 text-white">Indoctum</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Fierent</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Pericula</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Veniam</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Epicuri</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Mutat</p>
      </div>
      <div class="mt-16 mb-16">
        <p class="mb-6 text-white">Quaestio</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Erroribus</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Modus</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Volumus</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Abhorreant</p>
        <p class=" text-[#FFFFFF80] mb-2 font-normal">Mentitum</p>
      </div>
    </div>
    <!-- Desktop -->
  </div>
</div>

<!-- Nav -->
<div class=" flex place-content-center w-screen bg-[#A85756]">
  <div class=" lg:w-[calc(100%-270px)] w-[calc(100%-30px)]">
    <!-- Mobile -->
    <div class="w-full">
      <p class="text-base m-8 mb-4 font-normal text-center text-[#FFFFFF80]">
        © LOGO, 2019. All rights reserved. Created by Laaqiq.
      </p>
    </div>
    <!-- Desktop -->
  </div>
</div>
