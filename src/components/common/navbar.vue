<template>
  <nav class="nav navbar navbar-container">
    <div class="navbar__notifications--welcome-user">
      <div class="notifications">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="26.406"
          height="32.928"
          viewBox="0 0 26.406 32.928"
        >
          <path
            id="Path_995"
            fill="#1c3668"
            d="M27.105 20.451V15.2a9.9 9.9 0 0 0-8.252-9.754V3.65a1.65 1.65 0 0 0-3.3 0v1.8A9.9 9.9 0 0 0 7.3 15.2v5.248A4.952 4.952 0 0 0 4 25.105v3.3a1.651 1.651 0 0 0 1.65 1.65h5.182a6.6 6.6 0 0 0 12.741 0h5.182a1.651 1.651 0 0 0 1.65-1.65v-3.3a4.952 4.952 0 0 0-3.3-4.654zM10.6 15.2a6.6 6.6 0 1 1 13.2 0v4.951H10.6zm6.6 16.5a3.3 3.3 0 0 1-2.839-1.65h5.677a3.3 3.3 0 0 1-2.838 1.657zm9.9-4.951H7.3v-1.65a1.651 1.651 0 0 1 1.65-1.65h16.5a1.651 1.651 0 0 1 1.65 1.65z"
            data-name="Path 995"
            transform="translate(-4 -2)"
          />
        </svg>
      </div>
      <div class="welcome-user">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          width="60"
          height="60"
          viewBox="0 0 60 60"
        >
          <defs>
            <filter
              id="Ellipse_1"
              x="0"
              y="0"
              width="60"
              height="60"
              filterUnits="userSpaceOnUse"
            >
              <feOffset input="SourceAlpha" />
              <feGaussianBlur stdDeviation="2.5" result="blur" />
              <feFlood flood-opacity="0.161" />
              <feComposite operator="in" in2="blur" />
              <feComposite in="SourceGraphic" />
            </filter>
            <linearGradient
              id="linear-gradient"
              x1="0.186"
              y1="0.94"
              x2="0.87"
              y2="0.208"
              gradientUnits="objectBoundingBox"
            >
              <stop offset="0.067" stop-color="#e83866" />
              <stop offset="0.801" stop-color="#e57a3c" />
            </linearGradient>
          </defs>
          <g
            id="Group_1"
            data-name="Group 1"
            transform="translate(-255.5 -276.5)"
          >
            <g
              transform="matrix(1, 0, 0, 1, 255.5, 276.5)"
              filter="url(#Ellipse_1)"
            >
              <g
                id="Ellipse_1-2"
                data-name="Ellipse 1"
                transform="translate(7.5 7.5)"
                fill="#e9edf0"
                stroke="#a7b5d2"
                stroke-width="2"
              >
                <circle cx="22.5" cy="22.5" r="22.5" stroke="none" />
                <circle cx="22.5" cy="22.5" r="21.5" fill="none" />
              </g>
            </g>
            <path
              id="Path_994"
              data-name="Path 994"
              d="M15.669,2A13.71,13.71,0,0,0,2,15.669a13.275,13.275,0,0,0,3.554,9.159,13.627,13.627,0,0,0,19.274.82l.82-.82a13.622,13.622,0,0,0-.82-19.274A13.275,13.275,0,0,0,15.669,2Zm0,24.6a11.224,11.224,0,0,1-7.654-3,8.255,8.255,0,0,1,10.662-4.511A8.123,8.123,0,0,1,23.188,23.6a10.647,10.647,0,0,1-7.519,3ZM12.936,12.936A2.734,2.734,0,1,1,15.67,15.67a2.734,2.734,0,0,1-2.734-2.734Zm12.166,8.2A11.747,11.747,0,0,0,19.77,16.49a5.293,5.293,0,0,0-.547-7.655,5.537,5.537,0,0,0-7.655.41,5.589,5.589,0,0,0,0,7.245,11.747,11.747,0,0,0-5.331,4.648,10.936,10.936,0,1,1,18.864,0Z"
              transform="translate(270.001 291.001)"
              fill="url(#linear-gradient)"
            />
          </g>
        </svg>
        <span>
          مرحبآ بك
          <b>مالك محمد</b>
        </span>
      </div>
    </div>
    <div class="navbar__waiting-list">
      <div class="icon">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="16.989"
          height="17.01"
          viewBox="0 0 16.989 17.01"
        >
          <path
            id="arrow-right_2_"
            fill="#1d428b"
            d="M22.883 13.961a1.416 1.416 0 0 0-.3-.467L15.5 6.412a1.422 1.422 0 0 0-2.011 2.011l4.674 4.66H7.416a1.416 1.416 0 0 0 0 2.833h10.75l-4.674 4.66a1.422 1.422 0 1 0 2.008 2.011l7.082-7.082a1.464 1.464 0 0 0 .3-1.544z"
            data-name="arrow-right (2)"
            transform="translate(-6 -5.996)"
          />
        </svg>
      </div>
      <span>١٤ قائمة الإنتظار</span>
    </div>
  </nav>
</template>
<script>
export default {
  data: function() {
    return {};
  },
};
</script>
<style lang="scss" scoped>
@import "@/assets/scss/colors";
@import "@/assets/scss/fonts";
.navbar {
  background-color: $white;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0em 4.125em;
  box-shadow: 0 5px 86px 0 rgba(0, 0, 0, 0.05);
  height: 93px;
  &__notifications--welcome-user {
    display: flex;
    align-items: center;
    .welcome-user {
      display: flex;
      align-items: center;
      margin-right: 3.188em;
      span {
        color: $dark-slate-blue-two;
        font-family: $font-bold;
        font-size: 16px;
        font-weight: bold;
        font-stretch: normal;
        font-style: normal;
        line-height: 1.81;
        letter-spacing: normal;
        text-align: right;
        b {
          font-family: $font-extra-bold;
        }
      }
    }
  }
  &__waiting-list {
    display: flex;
    align-items: center;
    .icon {
      margin-left: 0.5em;
      svg {
        width: 1.063em;
        height: 1.063em;
      }
    }
    span {
      font-size: 1.25em;
      font-weight: 800;
      font-stretch: normal;
      font-style: normal;
      line-height: 2.75;
      letter-spacing: normal;
      text-align: right;
      color: $cobalt;
      font-family: $font-extra-bold;
    }
  }
}
</style>
