<template>
  <div>
    <div class="footer container-xl width-full p-responsive" role="contentinfo">
      <div
        class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light"
      >
        <ul
          class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0"
        >
          <li class="mr-3 mr-lg-0">© 2020 CHRISTIAN MCCLELLAN.</li>
        </ul>

        <a
          aria-label="Homepage"
          title="GitHub"
          class="footer-octicon d-none d-lg-block mx-lg-4"
          href="https://github.com"
        >
          <svg
            height="24"
            class="octicon octicon-mark-github"
            viewBox="0 0 16 16"
            version="1.1"
            width="24"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
            ></path>
          </svg>
        </a>
        <ul
          class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0"
        >
          <li class="mr-3 mr-lg-0">
            <router-link to="about">About</router-link>
          </li>
        </ul>
      </div>
      <div class="d-flex flex-justify-center pb-6">
        <span class="f6 text-gray-light"></span>
      </div>
    </div>
  </div>
</template>

<style>
@media (min-width: 544px) .p-responsive {
  padding-right: 40px !important;
  padding-left: 40px !important;
}
.p-responsive {
  padding-right: 16px !important;
  padding-left: 16px !important;
}
.width-full {
  width: 100% !important;
}

.container-xl {
  max-width: 1280px;
}
.container-lg,
.container-xl {
  margin-right: auto;
  margin-left: auto;
}
.d-flex {
  display: flex !important;
}
.f6 {
  font-size: 12px !important;
}
.pt-6 {
  padding-top: 40px !important;
}
.pb-2 {
  padding-bottom: 8px !important;
}
.mt-6 {
  margin-top: 40px !important;
}
.position-relative {
  position: relative !important;
}
.flex-justify-center {
  justify-content: center !important;
}
.flex-wrap {
  flex-wrap: wrap !important;
}

.flex-row-reverse {
  flex-direction: row-reverse !important;
}
.border-gray-light {
  border-color: var(--color-border-secondary) !important;
}
.text-gray {
  color: var(--color-text-secondary) !important;
}
.border-top {
  border-top: 1px solid var(--color-border-primary) !important;
}
.d-flex {
  display: flex !important;
}
.list-style-none {
  list-style: none !important;
}
.mb-2 {
  margin-bottom: 8px !important;
}
.flex-justify-center {
  justify-content: center !important;
}
.flex-wrap {
  flex-wrap: wrap !important;
}

.col-12 {
  width: 100%;
}
ol,
ul {
  padding-left: 0;
  margin-top: 0;
  margin-bottom: 0;
}
.mr-3 {
  margin-right: 16px !important;
}
li {
  display: list-item;
  text-align: -webkit-match-parent;
}
.list-style-none {
  list-style: none !important;
}
ul {
  list-style-type: disc;
}
.f6 {
  font-size: 12px !important;
}
.text-gray {
  color: var(--color-text-secondary) !important;
}
a {
  color: var(--color-text-link);
  text-decoration: none;
}
a {
  background-color: initial;
}
a:-webkit-any-link {
  color: -webkit-link;
  cursor: pointer;
  text-decoration: underline;
}
.footer-octicon {
  color: var(--color-footer-invertocat-octicon);
}
.d-none {
  display: none !important;
}
a {
  color: var(--color-text-link);
  text-decoration: none;
}

a {
  background-color: initial;
}
</style>