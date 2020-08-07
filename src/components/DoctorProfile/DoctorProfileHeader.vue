<template>
  <div class="doctor-profile-header">
    <div class="doctor-profile-header__details">
      <div class="doctor-profile-header__details__info">
        <a href="#" class="back-home">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="22"
            height="19"
            viewBox="0 0 22 19"
          >
            <path
              id="icons8-home_1_"
              fill="#435f95"
              d="M12 2a1 1 0 0 0-.711.3L1.2 11.1a.5.5 0 0 0 .3.9H4v8a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-6h4v6a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-8h2.5a.5.5 0 0 0 .3-.9L12.717 2.3h-.006A1 1 0 0 0 12 2z"
              data-name="icons8-home (1)"
              transform="translate(-1 -2)"
            />
          </svg>
        </a>
        <div class="doctor-avatar">
          <picture>
            <source
              media="(min-width:650px)"
              srcset="@/assets/imgs/022e6373e30a59ec5ad1f10f2dc50555@3x.png"
            />
            <source
              media="(min-width:465px)"
              srcset="@/assets/imgs/022e6373e30a59ec5ad1f10f2dc50555@2x.png"
            />
            <img
              src="@/assets/imgs/022e6373e30a59ec5ad1f10f2dc50555.png"
              alt="Doctor"
              style="width:auto;"
            />
          </picture>
        </div>
        <div class="doctor-info">
          <h3 class="head">
            العيادة الشاملة
          </h3>
          <div class="name--specialist">
            <div class="name">
              <p>لـ د.هند الناهض</p>
            </div>
            <div class="specialist">
              مشغول بإستشارة
            </div>
          </div>
          <div class="rate">
            <img src="@/assets/imgs/filled-star.svg" alt="" />
            <img src="@/assets/imgs/filled-star.svg" alt="" />
            <img src="@/assets/imgs/filled-star.svg" alt="" />
            <img src="@/assets/imgs/filled-star.svg" alt="" />
            <img src="@/assets/imgs/star.svg" alt="" />
            <span>التقييم</span>
          </div>
        </div>
      </div>
      <div class="doctor-profile-header__details__logo">
        <picture>
          <source
            media="(min-width:650px)"
            srcset="@/assets/imgs/logo@3x.png"
          />
          <source
            media="(min-width:465px)"
            srcset="@/assets/imgs/logo@2x.png"
          />
          <img src="@/assets/imgs/logo.png" alt="Logo" style="width:auto;" />
        </picture>
      </div>
    </div>
    <div class="doctor-profile-header__navigation-hardware-test">
      <div class="navigation">
        <ul>
          <li>
            <a href="#" class="active">نبذه عن هند</a>
          </li>
          <li>
            <a href="#">متجر</a>
          </li>
          <li>
            <a href="#">برودكاست</a>
          </li>
          <li>
            <a href="#">كورسات</a>
          </li>
          <li>
            <a href="#">حجز عيادة (20 دينار كويتي)</a>
          </li>
        </ul>
      </div>
      <div class="hardware-test">
        <ul>
          <li>
            <a href="#">
              <div class="icon">
                <img src="@/assets/imgs/audio.png" alt="" />
              </div>
              <div class="status">
                <h6>تجربة الصوت</h6>
                <span>جيد جداً</span>
              </div>
            </a>
          </li>
          <li>
            <a href="#">
              <div class="icon">
                <img src="@/assets/imgs/camera.png" alt="" />
              </div>
              <div class="status">
                <h6>تجربة الكاميرا</h6>
                <span>لم تقم باختبارها</span>
              </div>
            </a>
          </li>
          <li>
            <a href="#">
              <div class="icon">
                <img src="@/assets/imgs/wifi.png" alt="" />
              </div>
              <div class="status">
                <h6>سرعة الإنترنت</h6>
                <span>٣٦ Mbps</span>
              </div>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
@import "@/assets/scss/colors";
@import "@/assets/scss/fonts";
.doctor-profile-header {
  .doctor-profile-header__details {
    height: 183px;
    background-color: $dark-slate-blue-three;
    padding: 0em 4.125em;
    display: flex;
    align-items: center;
    justify-content: space-between;
    &__info {
      display: flex;
      align-items: center;
      .back-home {
        margin-top: -22px;
      }
      .doctor-avatar {
        margin-right: 20px;
        margin-left: 14px;
        img {
          width: 79px;
          height: 79px;
          margin-top: -22px;
        }
      }
      .doctor-info {
        .head {
          font-size: 18px;
          font-weight: 800;
          font-stretch: normal;
          font-style: normal;
          letter-spacing: normal;
          text-align: right;
          font-family: $font-extra-bold;
          color: $white;
          margin: 0;
        }
        .name--specialist {
          display: flex;
          align-items: center;
          .name {
            p {
              font-size: 20px;
              font-weight: bold;
              font-stretch: normal;
              font-style: normal;
              letter-spacing: normal;
              text-align: right;
              color: $cloudy-blue;
              font-family: $font-bold;
              margin: 0;
              line-height: 0;
            }
          }
          .specialist {
            margin-right: 1.125em;
            min-width: 142px;
            height: 31px;
            border-radius: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            background-image: linear-gradient(
              121deg,
              #e83866 -28%,
              #e83866 -21%,
              #e57a3c 55%,
              #e57a3c 75%
            );
            font-size: 13px;
            font-weight: 800;
            font-stretch: normal;
            font-style: normal;
            line-height: 4.23;
            letter-spacing: normal;
            font-family: $font-extra-bold;
            color: $white;
          }
        }
        .rate {
          margin-top: 0.75em;
          display: flex;
          align-items: center;
          img {
            margin-left: 0.169em;
            flex-shrink: 0;
          }
          span {
            display: block;
            font-size: 13px;
            font-weight: normal;
            font-stretch: normal;
            font-style: normal;
            line-height: 0.92;
            letter-spacing: normal;
            text-align: right;
            color: $cloudy-blue;
            font-family: $font-regular;
            margin-right: 0.331em;
          }
        }
      }
    }
    &__logo {
      img {
        max-width: 247.1px;
        width: 100%;
        height: 73.7px;
      }
    }
  }
  .doctor-profile-header__navigation-hardware-test {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 92px;
    padding: 0em 4.125em;
    background-image: linear-gradient(
      80deg,
      $dark-slate-blue 11%,
      $dark-slate-blue-two 95%
    );
    .navigation {
      ul {
        padding: 0;
        margin: 0;
        display: flex;
        align-items: center;
        list-style: none;
        li {
          a {
            margin-left: 2.5em;
            font-size: 1.125em;
            font-weight: 800;
            font-stretch: normal;
            font-style: normal;
            letter-spacing: normal;
            font-family: $font-extra-bold;
            text-decoration: none;
            position: relative;
            color: $blue-grey;
            transition: 0.3s all;
            &:before {
              content: "";
              position: absolute;
              width: 0;
              background: #fff;
              bottom: -11px;
              height: 3px;
              border-radius: 20px;
              transition: 0.3s all;
            }
            &.active,
            &:hover {
              color: $white;
              &:before {
                width: 30px;
              }
            }
          }
        }
      }
    }
    .hardware-test {
      ul {
        list-style: none;
        padding: 0;
        margin: 0;
        display: flex;
        align-items: center;
        li {
          a {
            display: flex;
            align-items: center;
            margin-left: 3.063em;
            text-decoration: none;
            .icon {
              margin-left: 1.063em;
              img {
                width: 52px;
                height: 52px;
              }
            }
            h6 {
              margin: 0;
              font-size: 16px;
              font-weight: bold;
              font-stretch: normal;
              font-style: normal;
              letter-spacing: normal;
              text-align: right;
              color: $white;
              font-family: $font-bold;
            }
            span {
              font-size: 14px;
              font-weight: 500;
              font-stretch: normal;
              font-style: normal;
              letter-spacing: normal;
              color: $cloudy-blue;
              font-family: $font-medium;
            }
          }
          &:last-child {
            a {
              margin-left: 0;
            }
          }
        }
      }
    }
  }
}
</style>
