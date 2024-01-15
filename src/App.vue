<template>
  <div class="overall-container">
    <div class="header">
      <img class="homepage-logo" src="https://s3.amazonaws.com/deltax.testing/AllFiles/Uploads/Logos/839a7d59-9faa-474b-bee3-2909368d4ff8_jioCinema-primary_Scaled.png" alt="JioCinema Ads Logo">
      <div class="empty-space-header"></div>
      <button class="signin-button">Sign In</button>
    </div>
    <div class="container">
      <div class="row content-row">
        <div class="col-md-6 col-xs-12 order-2 order-md-1 content-group">
          <h3>Grow Your Business</h3>
          <h3>with JioCinema Ads</h3>
          <div class="pointers-homepage">
            <div class="pointer">
              <img src="https://i.imgur.com/OBisJ0I.png">
              <p>Effortlessly advertise your business with just a few taps!</p>
            </div>
            <div class="pointer">
              <img src="https://i.imgur.com/OBisJ0I.png">
              <p>AI Generated creatives & ad copies</p>
            </div>
            <div class="pointer">
              <img src="https://i.imgur.com/OBisJ0I.png">
              <p>AI-based optimization to remove any guesswork</p>
            </div>
          </div>
          <div class="button-group">
            <button class="primary-cta">Promote Your Business</button>
            <button class="secondary-cta">Join as an Agency</button>
          </div>
        </div>
        <div class="col-md-6 col-xs-12 order-1 order-md-2 image-container">
          <img src="https://s3.amazonaws.com/deltax.testing/JC_Homepage_image.webp" alt="Homepage image with ad preview">
        </div>
      </div>
    </div>
    <div class="footer">
      <p>Powered by</p>
      <img src="https://deltax.com/wp-content/uploads/2022/08/dx-white-horizontal.png" alt="DeltaX Logo">
    </div>
  </div>
</template>

<style>
* {
  font-family: 'Open Sans', sans-serif;
  text-align: left;
  color: #111111;
  box-sizing:border-box;
}
.header{
  display: flex;
  height: 72px;
  padding-top: 4px;
  padding-bottom: 4px;
  margin-left: 16px;
  margin-right: 16px;
  align-items: center;
}
.homepage-logo{
  height: 100%;
}
.empty-space-header{
  flex-grow: 1;
}
.signin-button{
  height: 40px;
  border-radius: 4px;
  font-family: 'Open Sans', sans-serif;
  font-size: 13px;
  font-weight: 600;
  padding-left: 24px;
  padding-right: 24px;
  background-color: #F8CCE8;
  border: 0;
  color: #111111;
}
.image-container{
  display: flex;
  align-items: center;
  justify-content: right;
  padding-top: 16px !important;
  padding-bottom: 32px !important;
}
.image-container img{
  max-width: 100%;
  max-height: 480px;
}
.content-group{
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-left: 16px !important;
  padding-bottom: 24px !important;
}
.content-group h3{
  font-family: 'Proxima Nova', 'Open Sans', sans-serif;
  font-size: 32px;
  font-weight: 700;
  margin-bottom: 0;
}
.pointer{
  display: flex;
  gap: 12px;
  align-items: center;
  margin-bottom: 12px;
}
.pointers-homepage{
  margin-top: 12px;
}
.pointer img{
  height: 20px;
}
.pointer p{
  font-family: 'Open Sans', sans-serif;
  font-size: 14px;
  margin: 0;
}
.button-group{
  display: flex;
  gap: 16px;
  margin-top: 16px;
}
.primary-cta{
  height: 48px;
  border-radius: 6px;
  font-family: 'Open Sans', sans-serif;
  font-size: 13px;
  font-weight: 600;
  justify-content: center;
  padding-left: 12px;
  padding-right: 12px;
  background-color: #D9008D;
  border: 0;
  color: white;
}
.secondary-cta{
  height: 48px;
  border-radius: 6px;
  font-family: 'Open Sans', sans-serif;
  font-size: 13px;
  font-weight: 600;
  justify-content: center;
  padding-left: 12px;
  padding-right: 12px;
  background-color: white;
  border: 1px solid #D9008D;
  color: #D9008D;
}
.footer{
  height: 40px;
  background-color: #111111;
  display: flex;
  gap: 8px;
  padding-top: 8px;
  padding-bottom: 8px;
  align-items: center;
  justify-content: center;
}
.footer p{
  font-family: 'Open Sans', sans-serif;
  font-size: 12px;
  color: #B1B1B1;
  margin-bottom: 0;
}
.footer img{
  height: 100%;
}
@media (min-width: 768px) {
  .overall-container{
    height: 100vh;
    display: flex;
    flex-direction: column;
  }
  .header{
    display: flex;
    height: 120px;
    padding-top: 16px;
    padding-bottom: 16px;
    margin-left: 40px;
    margin-right: 64px;
    justify-content: center;
    align-items: flex-start;
  }
  .empty-space-header{
    flex-grow: 1;
  }
  .signin-button{
    height: 40px;
    border-radius: 4px;
    font-family: 'Open Sans', sans-serif;
    font-size: 15px;
    font-weight: 600;
    padding-left: 24px;
    padding-right: 24px;
    background-color: #F8CCE8;
    border: 0;
    color: #111111;
    margin-top: 12px;
  }
  .container{
    flex-grow: 1;
  }
  .content-row{
    height: 100%;
  }
  .content-group{
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-left: 64px !important;
    padding-bottom: 56px !important;
  }
  .content-group h3{
    font-family: 'Proxima Nova', 'Open Sans', sans-serif;
    font-size: 44px;
    font-weight: 700;
  }
  .pointer{
    display: flex;
    gap: 12px;
    align-items: center;
    margin-bottom: 16px;
  }
  .pointers-homepage{
    margin-top: 16px;
  }
  .pointer img{
    height: 20px;
  }
  .pointer p{
    font-family: 'Open Sans', sans-serif;
    font-size: 16px;
    margin: 0;
  }
  .button-group{
    display: flex;
    gap: 24px;
    margin-top: 24px;
  }
  .primary-cta{
    height: 56px;
    border-radius: 8px;
    font-family: 'Open Sans', sans-serif;
    font-size: 15px;
    font-weight: 600;
    padding-left: 24px;
    padding-right: 24px;
    background-color: #D9008D;
    border: 0;
    color: white;
  }
  .secondary-cta{
    height: 56px;
    border-radius: 8px;
    font-family: 'Open Sans', sans-serif;
    font-size: 15px;
    font-weight: 600;
    padding-left: 24px;
    padding-right: 24px;
    background-color: white;
    border: 2px solid #D9008D;
    color: #D9008D;
  }
  .image-container{
    display: flex;
    align-items: center;
    justify-content: center;
    padding-bottom: 56px !important;
  }
  .image-container img{
    max-width: 90%;
    max-height: 600px;
  }
  .footer{
    height: 56px;
    background-color: #111111;
    display: flex;
    gap: 8px;
    padding-top: 16px;
    padding-bottom: 16px;
    align-items: center;
    justify-content: center;
  }
  .footer p{
    font-family: 'Open Sans', sans-serif;
    font-size: 12px;
    color: #B1B1B1;
    margin-bottom: 0;
  }
  .footer img{
    height: 100%;
  }
}
</style>
