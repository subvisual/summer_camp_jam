<p class="Text">
  <slot />
</p>

<style>
  .Text {
    color: #111827;
    font-size: 12px;
    line-height: 14px;
    font-weight: 500;
  }

  @media screen and (min-width: 1024px) {
    .Text {
      font-size: 14px;
    }
  }
</style>
