<script>
  import closeIcon from '../../icons/close'
</script>

<style>
  .close-button {
    padding: 0.25rem;
    background: var(
      --onboard-close-button-background,
      var(--onboard-gray-100, var(--gray-100))
    );
    border-radius: 40px;
    color: var(
      --onboard-close-button-color,
      var(--onboard-gray-400, var(--gray-400))
    );
  }

  .close-icon {
    width: 24px;
  }
</style>

<div class="flex justify-center items-center pointer">
  <div class="close-button flex justify-center items-center">
    <div class="close-icon flex items-center">{@html closeIcon}</div>
  </div>
</div>
