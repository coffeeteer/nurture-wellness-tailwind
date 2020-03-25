<template>
  <div>
    <div class="max-w">
      <!-- Banner Image -->
      <img src="/../img/fontana-yoga.jpg" class="home-img z-0" />
      <!-- Flexbox sm info cards-->
      <div class="flex justify-between z-2" id="home-flex-div">
        <div
          class="max-w-2xl rounded overflow-hidden shadow-lg border-black content-center bg-white ml-10"
        >
          <div
            class="text-2xl font-hairline m-6 p-6"
          >A Collaborative Effort by Talented Local Healing Practitioners to Create a Nurturing Space.</div>
        </div>
        <div
          class="box-border h-32 w-100 rounded shadow-lg bg-green-500 shadow-lg border-black mr-10"
        >
          <div class="text-3xl font-hairline m-6 p-6 pb-1">
            <span>
              <i class="fas fa-users"></i>
            </span> Meet Our Practitioners
          </div>
        </div>
      </div>
    </div>
    <!-- Full width info panel -->
    <div class="max-w-sm w-full lg:max-w-full lg:flex border-black bg-gray-400">
      <div class="max-w-sm w-full lg:max-w-full lg:flex">
        <div class="p-6 w-56 justify-center items-center content-center mx-20">
          <div
            class="content-center border-r border-b border-l border-gray-400 lg:border-l-0 lg:border-t lg:border-gray-400 bg-white rounded-b lg:rounded-b-none lg:rounded-r p-4 flex flex-col justify-between leading-normal"
          >
            <h1
              class="font-semibold text-center text-2xl justify-center items-center"
            >Welcome to Nurture Wellness Studio</h1>
            <p class="text-center text-md mx-w">
              Located in Bryson City, NC and dedicated to serving the people and visitors to our community and
              surrounding area; this beautiful space offers private and group yoga classes, many styles of massage, acupuncture,
              and specialty workshops.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template> 

<style>
.home-img {
  margin-top: -167px;
  z-index: -1;
  position: relative;
}

#home-flex-div {
  margin-top: -90px;
}
</style>