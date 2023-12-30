<template>
  <header class="flex flex-col lg:flex-row gap-8 items-center">
    <img src="/images/logo.jpeg" class="w-full lg:w-1/2" alt="">
    <div class="px-6 md:pr-8 lg:pr-10 xl:pr-16">
      <UiTypographyH1>Wakandan Dollar - <br  /><span class="poppins">The Cryptocurrency to Unite the world.</span></UiTypographyH1>
      <UiTypographyP class="mt-4">Wakanda is a legendary place of goodness that all aspire to journey to, sometimes also called “the country of life.” <br  />Wakanda, it is one of the most technologically advanced nations on Earth, known for its rich deposits of the element vibranium.<br  />Wakandan Dollar is the native currency of the Wakandan Kingdom which is built on two Blockchain Network: the Binance Smart Chain and the Solana chain.</UiTypographyP>
    </div>
  </header>
  <div class="flex gap-5 py-20 justify-center px-6">
    <NuxtLink to="https://t.me/wakandandollarportal" class="group px-5 py-3 text-white bg-purple-700 hover:bg-purple-500 font-medium text-base 2xl:text-lg justify-center duration-300 ease-in-out rounded-full outline-none focus:outline-none flex items-center gap-4">
      <IconsTelegram class="w-7 h-7 text-white " />
      <UiTypographyP>Follow on Telegram</UiTypographyP>
    </NuxtLink>
    <NuxtLink to="https://twitter.com/wakandandollar/" class="group px-5 py-3 text-white bg-purple-700 hover:bg-purple-500  font-medium text-base 2xl:text-lg justify-center duration-300 ease-in-out rounded-full outline-none focus:outline-none flex items-center gap-4">
      <IconsTwitter class="w-7 h-7 text-white" />
      <UiTypographyP>Follow on Twitter</UiTypographyP>

    </NuxtLink>
  </div>
  <section class="px-6 max-w-7xl mx-auto pb-20 flex flex-col lg:flex-row gap-8 items-center lg:divide-x divide-purple-500">
    <div class="lg:w-1/2">
      <UiTypographyH2 class="wakanda">Mission and vision statement</UiTypographyH2>
      <UiTypographyP class="mt-4">Our aim is to put artificial intelligence in its natural birth place, with other Wakandan utility, embracing the African and global cultures for peace and prosperity, unite all tribe and nations to fight inflations and create financial freedom, equality and soverienty in a thriving Wakanda ecosystem.</UiTypographyP>
    </div>
    <div class="lg:w-1/2">
      <img src="/images/01.jpeg" alt="">
    </div>
  </section>
  <section class="px-6 max-w-7xl mx-auto pb-20 flex flex-col lg:flex-row gap-8 items-center">
    <img class="lg:w-2/3" src="/images/03.jpeg" alt="">

    <div class="lg:w-1/2 lg:pl-8 text-center lg:text-left">
      <UiTypographyH2 class="wakanda">Tokenomics</UiTypographyH2>
      <UiTypographyP class="mt-4">Wakandan Dollar on Binance Smart Chain Network:<br  />
        7% Buy | 7% Sell <br  />
        Take Breakdown: 1% Auto Burn<br  />
        2% Liquidity<br  />
        3% Marketing and Development.<br  /><br  />
        1% Reward in 🚀 Coin Emoji.<br  />
        Liquidity Lock and Renounced and Immutable.<br  /><br />
        Wakanda Dollar on Solana CHain Network:<br  />
        0 Tax.<br  />
        Liquidity Burnt.<br  />
        Renounced and Immutable
      </UiTypographyP>
    </div>
  </section>
  <img src="/images/04.jpeg" alt="" class="mx-auto">
  <section class="px-6 max-w-7xl mx-auto py-20">
    <UiTypographyH2 class="wakanda text-center">Roadmap </UiTypographyH2>
    <ul class="grid lg:grid-cols-3 relative mt-16 lg:gap-8 gap-16">
      <li class="p-6 border border-purple-500 rounded-xl relative">
        <div class="px-4 py-2 rounded-full text-white bg-purple-700 absolute w-fit -top-7 lg:-top-8 right-1/3">
          <UiTypographyH2 class="wakanda">Phase <span class="poppins">1</span></UiTypographyH2>
        </div>
        <UiTypographyP class="mt-4">
            Token creation and deployment.<br  />
            Project awareness marketing.<br  />
            Stealth launch.<br  />
            Website.<br  />
            White paper.
          </UiTypographyP>
      </li>
      <li class="p-6 border border-purple-500 rounded-xl relative">
        <div class="px-4 py-2 rounded-full text-white bg-purple-700 absolute w-fit -top-7 lg:-top-8 right-1/3">
          <UiTypographyH2 class="wakanda">Phase <span class="poppins">2</span></UiTypographyH2>
        </div>
        <UiTypographyP class="mt-4">
          Launch on PancakeSwap.<br  />
          Bsc trending <br  />
          Epic marketing <br  />
          Airdrop<br  />
          AMA <br  />
          </UiTypographyP>
      </li>
      <li class="p-6 border border-purple-500 rounded-xl relative">
        <div class="px-4 py-2 rounded-full text-white bg-purple-700 absolute w-fit -top-7 lg:-top-8 right-1/3">
          <UiTypographyH2 class="wakanda">Phase <span class="poppins">3</span></UiTypographyH2>
        </div>
        <UiTypographyP class="mt-4">
          Partnership. <br  />
          Twitter space. <br  />
          Farm & Staking Pools. <br  />
          Utility. <br  />
          CMC/CG Listings. <br  />
          NFT Collection Launch. <br  />
          Influencers Campaign. <br  />
          </UiTypographyP>
      </li>
    </ul>
  </section>
  <img src="/images/05.jpeg" alt="" class="mx-auto">
  <div class="px-6 py-20">
    <UiTypographyP class="p-6 max-w-3xl mx-auto border border-purple-700 rounded-2xl"><strong>Disclaimer: </strong>Wakandan Dollar $WAKANDA coin has no association with Marvel comics, Black Panther or any associated enities. This token is simply paying homage to a meme with intention of uniting Africans and the World, By promoting and bringing awarness that africa is the Cradle of Civilization. <br />$WAKANDA is a meme coin with no intrinsic value or expectation of financial return. There is no formal team or roadmap. the coin is completely useless and for entertainment purposes only.</UiTypographyP>
  </div>

</template>
<style>
.poppins {
  font-family: 'Poppins', sans-serif;
}
</style>