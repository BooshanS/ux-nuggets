<section class="card-container">
  <div class="card-header-and-body">
    <div class="image-seperator">
      <div class="card-header">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" class="circle-icon">
            <circle cx="12" cy="12" r="12" fill="#D9D9D9"/>
          </svg>
          <h2 class="app-name">Duolingo</h2>
         <svg xmlns="http://www.w3.org/2000/svg" width="6" height="6" viewBox="0 0 6 6" fill="none">
            <circle cx="3" cy="3" r="3" fill="#D9D9D9"/>
          </svg>
          <h2 class="date-published">Feb 2023</h2>
      </div>
      <div class="header-action">
          <span class="expand-button">Expand</span>
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" class="icon-image">
  <path d="M11.9999 6.34315L11.9999 17.6569M11.9999 17.6569L17.4093 12.2474M11.9999 17.6569L6.54498 12.202" stroke="#575A69" stroke-width="2"/>
</svg>
      </div>
      <section class="card-body">
        <div class="card-body-text">
          <h3 class="streak-header">We've frozen your streaks</h3>
          <p class="streak-description">Duolingo automatically applies a 2-day "streak freeze", so if you churn quickly, you don't lose your progress.</p>
        </div>
        <div class="features-container">
          <div class="feature">Progressive Disclosure</div>
          <div class="feature">Goal Gradient Effect</div>
          <div class="feature">Peak-end Rule</div>
        </div>
      </section>
    </div>
    <div class="image-container">
      <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/707fdb8fca583aee7c1a3a9fdd2336e5d68d49415f853c675a0b86d773eabcab?apiKey=a4a8825dec6c482fb8bbca31dccafd54&" class="main-image" alt="" />
    </div>
  </div>
  <footer class="card-footer">
    <svg xmlns="http://www.w3.org/2000/svg" width="21" height="20" viewBox="0 0 21 20" fill="none" class="search-icon">
  <path d="M10.0834 18.125C5.37508 18.125 1.54175 14.2917 1.54175 9.58334C1.54175 4.87501 5.37508 1.04167 10.0834 1.04167C14.7917 1.04167 18.6251 4.87501 18.6251 9.58334C18.6251 14.2917 14.7917 18.125 10.0834 18.125ZM10.0834 2.29167C6.05841 2.29167 2.79175 5.56667 2.79175 9.58334C2.79175 13.6 6.05841 16.875 10.0834 16.875C14.1084 16.875 17.3751 13.6 17.3751 9.58334C17.3751 5.56667 14.1084 2.29167 10.0834 2.29167Z" fill="#65697E"/>
  <path d="M18.8333 18.9583C18.675 18.9583 18.5166 18.9 18.3916 18.775L16.725 17.1083C16.4833 16.8667 16.4833 16.4667 16.725 16.225C16.9666 15.9833 17.3666 15.9833 17.6083 16.225L19.275 17.8917C19.5166 18.1333 19.5166 18.5333 19.275 18.775C19.15 18.9 18.9916 18.9583 18.8333 18.9583Z" fill="#65697E"/>
</svg>
    <p class="founder-text">Found by <span class="founder-name">Booshan</span></p>
  </footer>
</section>


<style>
  .card-container {
    
    display: inline-flex;
    max-width: 41.875rem;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
  }
  .card-header-and-body{
    position:relative;
    display: flex;
    padding: 2.5rem 0.5rem 0.5rem 0.5rem;
    flex-direction: column;
    align-items: flex-start;
    gap: 1.5rem;
    border-radius: 3.5rem;
    border: 1px solid #F0F0F0;
    background: #FFF;
    box-shadow: 0px 1.674px 1.595px 0px rgba(0, 0, 0, 0.01), 0px 3.804px 3.623px 0px rgba(0, 0, 0, 0.01), 0px 6.621px 6.306px 0px rgba(0, 0, 0, 0.01), 0px 10.518px 10.017px 0px rgba(0, 0, 0, 0.01), 0px 16.229px 15.456px 0px rgba(0, 0, 0, 0.02), 0px 25.324px 24.118px 0px rgba(0, 0, 0, 0.02), 0px 42.041px 40.039px 0px rgba(0, 0, 0, 0.02), 0px 84px 80px 0px rgba(0, 0, 0, 0.03);
      }
  .card-footer{
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }
  .founder-text{
    color: #65697E;
    font-family: Inter;
    font-size: 1rem;
    font-style: normal;
    font-weight: 500;
    line-height: 1.625rem; /* 162.5% */
  }
  .founder-name{
    color: #65697E;
    font-family: Inter;
    font-size: 1rem;
    font-style: normal;
    font-weight: 700;
    line-height: 1.625rem;
  }
  .search-icon{
    width: 1.25rem;
    height: 1.25rem;
    flex-shrink: 0;
  }
  .image-seperator{
    display: flex;
    padding: 0rem 2.125rem;
    flex-direction: column;
    align-items: flex-start;
    gap: 1.25rem;
    align-self: stretch;
  }
  .card-header{
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }
  .image-container{
    display: flex;
    max-width: 40.8125rem;
    padding: 0rem 11.1875rem 3.125rem 11.1875rem;
    justify-content: center;
    align-items: center;
    border-radius: 3.5rem;
    background: #FF7061;
  } 
  .image-container img{
    max-width: 18.4375rem;
    max-height: 38.375rem;
    flex-shrink: 0;
    border-radius: 1rem;
    background: url(https://cdn.builder.io/api/v1/image/assets/TEMP/707fdb8fca583aee7c1a3a9fdd2336e5d68d49415f853c675a0b86d773eabcab?apiKey=a4a8825dec6c482fb8bbca31dccafd54&), lightgray 50% / cover no-repeat;
  }
  .circle-icon{
    width: 1.5rem;
    height: 1.5rem;
    fill: #D9D9D9;
  }
  .circle-icon-small{
    width: 0.375rem;
    height: 0.375rem;
    fill: #D9D9D9;
  }
  .app-name{
    color: #65697E;
    font-family: Inter;
    font-size: 1rem;
    font-style: normal;
    font-weight: 600;
    line-height: 1.625rem; /* 162.5% */
  }
  .date-published{
    color: #9599AC;
    font-family: Inter;
    font-size: 1rem;
    font-style: normal;
    font-weight: 600;
    line-height: 1.625rem; /* 162.5% */
    letter-spacing: 0.16rem;
    text-transform: uppercase;
  }
  .header-action{
    display: flex;
    padding: 0.5625rem 0.5625rem 0.5625rem 0.9375rem;
    justify-content: flex-end;
    align-items: flex-start;
    position: absolute;
    right: 2rem;
    top: 2rem;
    border-radius: 4.0625rem;
    border: 1px solid rgba(53, 56, 70, 0.10);
}
  .expand-button{
    color: #575A69;
    font-family: Inter;
    font-size: 1rem;
    font-style: normal;
    font-weight: 600;
    line-height: 1.625rem; /* 162.5% */
  }
  .streak-header{
    align-self: stretch;
    color:#353846;
    font-family: Inter;
    font-size: 1.5rem;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    letter-spacing: -0.015rem;
  }
  .streak-description{
    align-self: stretch;
    color: #575A69;
    font-family: Inter;
    font-size: 1rem;
    font-style: normal;
    font-weight: 500;
    line-height: 1.625rem; /* 162.5% */
  }
  .icon-image{
    width: 1.5rem;
    height: 1.5rem;
  }
  .card-body{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 1.5rem;
    align-self: stretch;
  }
  .card-body-text{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 0.75rem;
    align-self: stretch;
  }
  .features-container{
    display: flex;
    align-items: flex-start;
    align-content: flex-start;
    gap: 0.5rem;
    align-self: stretch;
    flex-wrap: wrap;
  }
  .feature{
    display: flex;
    padding: 0.25rem 1rem;
    justify-content: center;
    align-items: center;
    gap: 0.5rem;
    border-radius: 4.0625rem;
    border: 1px solid rgba(160, 160, 160, 0.16);
    background: rgba(178, 178, 178, 0.16);
    color: #575A69;
    font-family: Inter;
    font-size: 0.75rem;
    font-style: normal;
    font-weight: 600;
    line-height: 1.625rem; /* 216.667% */
  }
</style>