<script>
  import { GradientHeading } from "@skeletonlabs/skeleton";
</script>

<section
  class="overflow-hidden bg-[url('/CTA_photo.jpg')] bg-cover bg-center bg-no-repeat "
>
  <div class="bg-black/75 px-16 py-16">
    <div class="max-w-full text-center">
      <GradientHeading
        tag="h1"
        direction="bg-gradient-to-r"
        from="from-primary-500"
        to="to-accent-500"
        class="text-3xl md:text-6xl"
        >Рекламное агентство <br /> в Дагестане с 2007 года
      </GradientHeading>

      <span
        class=" hidden max-w-sm tracking-wide leading-none text-sm font-medium text-gray-200 md:mt-6 md:block sm:text-lg md:max-w-full"
      >
        Помогаем в развитии малому и крупному бизнесу. <br />
        Доводим ваши идеи до клиентов.
        <span />
      </span>
      <div class="mt-4 sm:mt-8">
        <a
          href="/gallery"
          class="inline-flex items-center rounded-full bg-indigo-700 px-8 py-3 shadow-lg transition hover:bg-indigo-600 focus:outline-none focus:ring"
        >
          <span class="text-white text-sm font-medium"> Посмотреть Работы </span>

          <svg
            class="ml-3 h-5 w-5"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M17 8l4 4m0 0l-4 4m4-4H3"
            />
          </svg>
        </a>
      </div>
    </div>
  </div>
</section>
