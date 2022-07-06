<p class="Active">
  <slot />
</p>

<style>
  .Active {
    background: #d1fae5;
    font-weight: 600;
    font-size: 14px;
    line-height: 20px;
    color: #065f46;
    display: inline-block;
    border-radius: 130px;
    padding: 8px 8px 8px 8px;
  }

  @media screen and (min-width: 1024px) {
    .Active {
      font-size: 18px;
    }
  }
</style>
