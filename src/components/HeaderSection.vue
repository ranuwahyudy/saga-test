<template>
  <!-- HEADER -->
  <header class="bg-primary-gray">
    <nav
      class="container navbar max-w-[1240px] m-auto relative flex flex-row justify-between"
    >
      <a href="/" class="nav-brand self-center w-[150px] h-[37px]">
        <img src="../assets/img/Logo-MAXLIFE.svg" alt="Logo MAXlife" />
      </a>

      <!-- Toggle button -->
      <button
        class="toggle-button text-[21px] bg-transparent border-none absolute left-0 my-[-3px] mx-2.5 py-0.5 px-1.5 hidden focus:outline-none"
      >
        <img src="../assets/img/menu.svg" alt="Menu Icon" />
      </button>

      <!-- Collapse on toggle button click -->
      <div class="self-center">
        <ul class="navbar-nav my-[54px]">
          <a
            href="#"
            class="nav-link m-[30px] text-primary-black not-italic font-bold text-base ml-0"
            >Max for Dogs</a
          >
          <a
            href="#"
            class="nav-link m-[30px] text-primary-black not-italic font-bold text-base"
            >Max for Cats</a
          >
          <a
            href="#"
            class="nav-link m-[30px] text-primary-black not-italic font-bold text-base"
            >Forum</a
          >
          <a
            href="#"
            class="nav-link m-[30px] text-primary-black not-italic font-bold text-base"
            >Vet Talk</a
          >
          <a
            href="#"
            class="nav-link m-[30px] text-primary-black not-italic font-bold text-base"
            >Max Share</a
          >
          <a
            href="#"
            class="nav-link m-[30px] text-primary-black not-italic font-bold text-base mr-20"
            >Contact Us</a
          >
          <a
            href="#"
            class="btn-primary inline-block text-primary-white bg-primary-blue not-italic font-bold text-sm leading-6 pt-3.5 px-8 pb-[15px] rounded-[10px]"
            >Join us</a
          >
        </ul>
      </div>
    </nav>
  </header>
  <!-- END HEADER -->
</template>
