<script setup></script>

<template>
  <div class="flex flex-col items-start justify-between gap-y-8 sm:gap-y-20 p-10 sm:p-12">
    <div class="flex flex-col gap-y-8">
      <slot name="icon"></slot>
      <h1
        class="text-very-light-gray text-4xl font-big-shoulders-display uppercase"
      >
        <slot name="header"></slot>
      </h1>
      <p class="text-transparent-white text-[15px] font-lexend-deca">
        <slot name="body"> </slot>
      </p>
    </div>
    <button
      class="bg-very-light-gray border border-very-light-gray rounded-3xl p-2 px-6 text-sm font-lexend-deca hover:bg-inherit hover:text-very-light-gray"
    >
      Learn More
    </button>
  </div>
</template>
