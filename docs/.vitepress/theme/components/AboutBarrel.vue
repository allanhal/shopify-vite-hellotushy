<template>
  <div class="about-allanhal">
    <div class="about-allanhal__heading">
      About the developers:
      <img class="allanhal-icon" src="/allanhal-icon.svg" alt="allanhal" />
    </div>

    <div class="about-allanhal__content">
      <p>
        Volt, a Vite plugin for Shopify development was developed by allanhal.<br />
        allanhal partners with brands to design, build, and optimize web experiences.
      </p>

      <p>
        <a href="https://allanhalny.com" target="_blank">Learn more about allanhal</a>
      </p>
    </div>
  </div>
</template>

<style scoped>
.about-allanhal {
  background-color: rgba(29, 29, 32, 0.7);
  border: 1px solid rgba(255, 255, 255, 0.7);
  border-radius: 20px;
  padding: 33px 40px 66px 26px;
  width: calc(100% - 48px);
  margin-left: auto;
  margin-right: auto;
}

.about-allanhal__heading {
  font-size: 18px;
  line-height: 1.45;
  margin-bottom: 30px;
  white-space: nowrap;
}

.allanhal-icon {
  display: block;
  margin-top: 8px;
  width: 111px;
}

.about-allanhal__content {
  font-size: 14px;
  line-height: 1.45;
  max-width: 460px;
}

.about-allanhal__content p + p {
  margin-top: 20px;
}

.about-allanhal__content a {
  text-decoration: underline;
  text-underline-offset: 2px;
  transition: color 0.2s;
}

.about-allanhal__content a:hover {
  color: var(--vp-c-brand-lighter);
}

@media (min-width: 680px) {
  .about-allanhal {
    width: calc(100% - 96px);
    max-width: 1152px;
    padding-bottom: 33px;
  }
}

@media (min-width: 960px) {
  .about-allanhal {
    padding: 36px 80px 20px;
    display: flex;
  }

  .about-allanhal__heading {
    margin-bottom: 0;
  }

  .about-allanhal__content {
    margin-left: 25%;
  }
}
</style>
