<template>
  <div class="hero min-h-screen">
    <div class="flex-col hero-content">
      <div class="flex-col flex lg:flex-row-reverse">
        <img
          src="../assets/HealthyFit Cover COMINGSOON Mockup2.jpg"
          class="max-w-xs md:max-w-lg rounded-lg shadow-2xl self-start"
        />
        <div>
          <h1 class="text-5xl font-bold mb-8">
            A Curated Toolset For Your FitHealthy™ Journey
          </h1>
          <div class="my-4">
            <p class="my-2">
              <Icon
                name="mdi:tools"
                size="3em"
                class="bg-base-200 rounded-full p-2"
              />
              Best-of-breed tools for maximizing your well-being and fitness.
            </p>

            <p class="my-2">
              <Icon
                name="twemoji:star"
                size="3em"
                class="bg-base-200 rounded-full p-2"
                color="orange"
              />
              Curated from a wide-range of experts, described in an easy to
              absorb way.
            </p>
            <p class="my-2">
              <Icon
                name="twemoji:open-book"
                size="3em"
                class="bg-base-200 rounded-full p-2"
                color=""
              />
              50 chapters covering health, fitness and productivity.
            </p>
            <p class="my-2">
              <Icon
                name="mdi:plus"
                size="3em"
                class="bg-base-200 rounded-full p-2"
                color="red"
              />
              Now with added Bonus Toolset!
            </p>
          </div>
          <div>
            <div class="join me-2">
              <button class="btn btn-success join-item" disabled>
                Buy Now
              </button>
              <div class="join-item btn btn-neutral" disabled>$19.99</div>
            </div>
            <button class="btn btn-outline" disabled>Read a chapter</button>
          </div>
        </div>
      </div>

      <div class="flex align-center justify-center mt-4">
        <div class="md:grid-cols-3 grid-cols-1 grid gap-2">
          <div class="card w-md-96 w-70 bg-base-100 shadow-xl">
            <div class="card-body">
              <h2 class="card-title">Wow!!</h2>
              <div class="rating rating-sm">
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                  checked
                />
              </div>
              <p class="italic">
                "It's the equivalent of hundreds of great podcast episodes and
                productivity books distilled into one short, amazing,
                extraordinary read!"
              </p>
              <p class="text-sm">
                - Not said by Tony Robbins, but only because he hasn't read it
                yet
              </p>
            </div>
          </div>
          <div class="card w-md-96 w-70 bg-base-100 shadow-xl">
            <div class="card-body">
              <h2 class="card-title">My son rocks!</h2>
              <div class="rating rating-sm">
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                  checked
                />
              </div>
              <p class="italic">
                "I loved every part of it! (Except for the part about porn. Did
                not enjoy that part.)"
              </p>
              <p class="text-sm">- Mum</p>
            </div>
          </div>
          <div class="card w-md-96 w-70 bg-base-100 shadow-xl">
            <div class="card-body">
              <h2 class="card-title">Hmm...</h2>
              <div class="rating rating-sm">
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                  checked
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
                <input
                  type="radio"
                  name="rating-6"
                  class="mask mask-star-2 bg-orange-400"
                />
              </div>
              <p>
                "It sounds kinda interesting, but no way I'd pay for that!!"
              </p>
              <p class="text-sm">- Random guy on the street</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- <div>Chapter List</div> -->
</template>

<script setup></script>
