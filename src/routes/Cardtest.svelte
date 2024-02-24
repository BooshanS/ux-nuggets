<script>
  // Svelte script content here
</script>

<section class="notification-container">
  <header class="notification-header">
    <div class="notification-info">
      <div class="logo-placeholder"></div>
      <h1 class="notification-title">Duolingo</h1>
      <time class="notification-time">Feb 2023</time>
    </div>
    <div class="notification-expand">
      <span class="expand-text">Expand</span>
      <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/1fbefa473907d2188fc43e3221a8024cbb09958295eeb26b5aeb09b6cbad37cc?apiKey=a4a8825dec6c482fb8bbca31dccafd54&" alt="Example image" class="notification-image" />
    </div>
  </header>
  <div class="notification-body">
    <h2 class="notification-main-text">We've frozen your streaks</h2>
    <p class="notification-description">Duolingo automatically apply a 2-day "streak freeze", so if you churn quickly, you don't lose your progress.</p>
    <div class="notification-tags">
      <div class="tag">Progressive Disclosure</div>
      <div class="tag">Goal Gradient Effect</div>
      <div class="tag">Peak-end Rule</div>
    </div>
  </div>
  <footer class="notification-footer">
    <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/707fdb8fca583aee7c1a3a9fdd2336e5d68d49415f853c675a0b86d773eabcab?apiKey=a4a8825dec6c482fb8bbca31dccafd54&" alt="Duolingo logo" class="notification-logo"/>
  </footer>
  <aside class="user-info">
    <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/9ee1f9594b20753a559d1f90f263c5f053ad695915657939905be04b7833d696?apiKey=a4a8825dec6c482fb8bbca31dccafd54&" alt="" class="user-avatar"/>
    <div class="user-discovery">Found by <span class="user-name">Booshan</span></div>
  </aside>
</section>

<style>
  .notification-container {
    display: flex;
    max-width: 669px;
    flex-direction: column;
    border: 1px solid #f0f0f0;
    box-shadow: 0px 1.674px 1.595px rgba(0, 0, 0, 0.01), 0px 3.804px 3.623px rgba(0, 0, 0, 0.01), 0px 6.621px 6.306px rgba(0, 0, 0, 0.01), 0px 10.518px 10.017px rgba(0, 0, 0, 0.01), 0px 16.229px 15.456px rgba(0, 0, 0, 0.02), 0px 25.324px 24.118px rgba(0, 0, 0, 0.02), 0px 42.041px 40.039px rgba(0, 0, 0, 0.02), 0px 84px 80px rgba(0, 0, 0, 0.03);
    border-radius: 56px;
    background-color: #fff;
    padding: 40px 8px 8px;
  }
  .notification-header {
    display: flex;
    justify-content: space-between;
    padding: 0 16px 0 34px;
  }
  .notification-info {
    display: flex;
    gap: 8px;
    align-items: center;
  }
  .logo-placeholder {
    background-color: #d9d9d9;
    border-radius: 50%;
    width: 24px;
    height: 24px;
  }
  .notification-title {
    font-family: Inter, sans-serif;
    color: #65697e;
  }
  .notification-time {
    font-family: Inter, sans-serif;
    color: #9599ac;
    letter-spacing: 2.56px;
    text-transform: uppercase;
    flex-grow: 1;
  }
  .notification-expand {
    display: flex;
    align-items: center;
    gap: 3px;
  }
  .expand-text {
    font-family: Inter, sans-serif;
    color: #575a69;
  }
  .notification-image {
    width: 24px;
    aspect-ratio: 1.33;
  }
  .notification-main-text {
    margin-top: 18px;
    font: 700 24px Inter, sans-serif;
    color: #353846;
  }
  .notification-description {
    margin-top: 12px;
    font-weight: 500;
    font-family: Inter, sans-serif;
    color: #65697e;
  }
  .notification-tags {
    display: flex;
    gap: 8px;
    margin-top: 24px;
    font-size: 12px;
    color: #575a69;
  }
  .tag {
    justify-content: center;
    border-radius: 65px;
    border: 1px solid rgba(160, 160, 160, 0.16);
    background-color: rgba(178, 178, 178, 0.16);
    font-family: Inter, sans-serif;
    padding: 4px 16px;
  }
  .notification-footer, .user-info {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 24px;
  }
  .notification-logo, .user-avatar {
    width: 295px;
    aspect-ratio: 0.75;
  }
  .user-discovery {
    display: flex;
    align-items: center;
    color: #65697e;
    font-family: Inter, sans-serif;
    gap: 8px;
  }
  .user-name {
    font-weight: 700;
    color: rgba(101, 105, 126, 1);
  }
</style>