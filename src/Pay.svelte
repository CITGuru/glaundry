<script>

</script>

<style>
  .example.example1 {
    background-color: #6772e5;
  }

  .example.example1 * {
    font-family: Roboto, Open Sans, Segoe UI, sans-serif;
    font-size: 16px;
    font-weight: 500;
  }

  .example.example1 fieldset {
    margin: 0 15px 20px;
    padding: 0;
    border-style: none;
    background-color: #7795f8;
    box-shadow: 0 6px 9px rgba(50, 50, 93, 0.06), 0 2px 5px rgba(0, 0, 0, 0.08),
      inset 0 1px 0 #829fff;
    border-radius: 4px;
  }

  .example.example1 .row {
    display: -ms-flexbox;
    display: flex;
    -ms-flex-align: center;
    align-items: center;
    margin-left: 15px;
  }

  .example.example1 .row + .row {
    border-top: 1px solid #819efc;
  }

  .example.example1 label {
    width: 15%;
    min-width: 70px;
    padding: 11px 0;
    color: #c4f0ff;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }

  .example.example1 input,
  .example.example1 button {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    outline: none;
    border-style: none;
  }

  .example.example1 input:-webkit-autofill {
    -webkit-text-fill-color: #fce883;
    transition: background-color 100000000s;
    -webkit-animation: 1ms void-animation-out;
  }

  .example.example1 .StripeElement--webkit-autofill {
    background: transparent !important;
  }

  .example.example1 .StripeElement {
    width: 100%;
    padding: 11px 15px 11px 0;
  }

  .example.example1 input {
    width: 100%;
    padding: 11px 15px 11px 0;
    color: #fff;
    background-color: transparent;
    -webkit-animation: 1ms void-animation-out;
  }

  .example.example1 input::-webkit-input-placeholder {
    color: #87bbfd;
  }

  .example.example1 input::-moz-placeholder {
    color: #87bbfd;
  }

  .example.example1 input:-ms-input-placeholder {
    color: #87bbfd;
  }

  .example.example1 button {
    display: block;
    width: calc(100% - 30px);
    height: 40px;
    margin: 40px 15px 0;
    background-color: #f6a4eb;
    box-shadow: 0 6px 9px rgba(50, 50, 93, 0.06), 0 2px 5px rgba(0, 0, 0, 0.08),
      inset 0 1px 0 #ffb9f6;
    border-radius: 4px;
    color: #fff;
    font-weight: 600;
    cursor: pointer;
  }

  .example.example1 button:active {
    background-color: #d782d9;
    box-shadow: 0 6px 9px rgba(50, 50, 93, 0.06), 0 2px 5px rgba(0, 0, 0, 0.08),
      inset 0 1px 0 #e298d8;
  }

  .example.example1 .error svg .base {
    fill: #fff;
  }

  .example.example1 .error svg .glyph {
    fill: #6772e5;
  }

  .example.example1 .error .message {
    color: #fff;
  }

  .example.example1 .success .icon .border {
    stroke: #87bbfd;
  }

  .example.example1 .success .icon .checkmark {
    stroke: #fff;
  }

  .example.example1 .success .title {
    color: #fff;
  }

  .example.example1 .success .message {
    color: #9cdbff;
  }

  .example.example1 .success .reset path {
    fill: #fff;
  }
</style>

<main>
  <section class="container-lg">
    <div class="cell example example1" id="example-1">
      <form>
        <fieldset>
          <div class="row">
            <label
              for="example1-name"
              data-tid="elements_examples.form.name_label">
              Name
            </label>
            <input
              id="example1-name"
              data-tid="elements_examples.form.name_placeholder"
              type="text"
              placeholder="Jane Doe"
              required=""
              autocomplete="name" />
          </div>
          <div class="row">
            <label
              for="example1-email"
              data-tid="elements_examples.form.email_label">
              Email
            </label>
            <input
              id="example1-email"
              data-tid="elements_examples.form.email_placeholder"
              type="email"
              placeholder="janedoe@gmail.com"
              required=""
              autocomplete="email" />
          </div>
          <div class="row">
            <label
              for="example1-phone"
              data-tid="elements_examples.form.phone_label">
              Phone
            </label>
            <input
              id="example1-phone"
              data-tid="elements_examples.form.phone_placeholder"
              type="tel"
              placeholder="(941) 555-0123"
              required=""
              autocomplete="tel" />
          </div>
        </fieldset>
        <fieldset>
          <div class="row">
            <div id="example1-card" />
          </div>
        </fieldset>
        <button type="submit" data-tid="elements_examples.form.pay_button">
          Pay $25
        </button>
        <div class="error" role="alert">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="17"
            height="17"
            viewBox="0 0 17 17">
            <path
              class="base"
              fill="#000"
              d="M8.5,17 C3.80557963,17 0,13.1944204 0,8.5 C0,3.80557963
              3.80557963,0 8.5,0 C13.1944204,0 17,3.80557963 17,8.5
              C17,13.1944204 13.1944204,17 8.5,17 Z" />
            <path
              class="glyph"
              fill="#FFF"
              d="M8.5,7.29791847 L6.12604076,4.92395924 C5.79409512,4.59201359
              5.25590488,4.59201359 4.92395924,4.92395924 C4.59201359,5.25590488
              4.59201359,5.79409512 4.92395924,6.12604076 L7.29791847,8.5
              L4.92395924,10.8739592 C4.59201359,11.2059049
              4.59201359,11.7440951 4.92395924,12.0760408 C5.25590488,12.4079864
              5.79409512,12.4079864 6.12604076,12.0760408 L8.5,9.70208153
              L10.8739592,12.0760408 C11.2059049,12.4079864
              11.7440951,12.4079864 12.0760408,12.0760408 C12.4079864,11.7440951
              12.4079864,11.2059049 12.0760408,10.8739592 L9.70208153,8.5
              L12.0760408,6.12604076 C12.4079864,5.79409512
              12.4079864,5.25590488 12.0760408,4.92395924 C11.7440951,4.59201359
              11.2059049,4.59201359 10.8739592,4.92395924 L8.5,7.29791847
              L8.5,7.29791847 Z" />
          </svg>
          <span class="message" />
        </div>
      </form>
      <div class="success">
        <div class="icon">
          <svg
            width="84px"
            height="84px"
            viewBox="0 0 84 84"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink">
            <circle
              class="border"
              cx="42"
              cy="42"
              r="40"
              stroke-linecap="round"
              stroke-width="4"
              stroke="#000"
              fill="none" />
            <path
              class="checkmark"
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M23.375 42.5488281 36.8840688 56.0578969 64.891932 28.0500338"
              stroke-width="4"
              stroke="#000"
              fill="none" />
          </svg>
        </div>
        <h3 class="title" data-tid="elements_examples.success.title">
          Payment successful
        </h3>
        <p class="message">
          <span data-tid="elements_examples.success.message">
            Thanks for trying Stripe Elements. No money was charged, but we
            generated a token:
          </span>
          <span class="token">tok_189gMN2eZvKYlo2CwTBv9KKh</span>
        </p>
        <a class="reset" href="#">
          <svg
            width="32px"
            height="32px"
            viewBox="0 0 32 32"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink">
            <path
              fill="#000000"
              d="M15,7.05492878 C10.5000495,7.55237307 7,11.3674463 7,16
              C7,20.9705627 11.0294373,25 16,25 C20.9705627,25 25,20.9705627
              25,16 C25,15.3627484 24.4834055,14.8461538 23.8461538,14.8461538
              C23.2089022,14.8461538 22.6923077,15.3627484 22.6923077,16
              C22.6923077,19.6960595 19.6960595,22.6923077 16,22.6923077
              C12.3039405,22.6923077 9.30769231,19.6960595 9.30769231,16
              C9.30769231,12.3039405 12.3039405,9.30769231 16,9.30769231
              L16,12.0841673 C16,12.1800431 16.0275652,12.2738974
              16.0794108,12.354546 C16.2287368,12.5868311 16.5380938,12.6540826
              16.7703788,12.5047565 L22.3457501,8.92058924
              L22.3457501,8.92058924 C22.4060014,8.88185624
              22.4572275,8.83063012 22.4959605,8.7703788 C22.6452866,8.53809377
              22.5780351,8.22873685 22.3457501,8.07941076 L22.3457501,8.07941076
              L16.7703788,4.49524351 C16.6897301,4.44339794
              16.5958758,4.41583275 16.5,4.41583275 C16.2238576,4.41583275
              16,4.63969037 16,4.91583275 L16,7 L15,7 L15,7.05492878 Z M16,32
              C7.163444,32 0,24.836556 0,16 C0,7.163444 7.163444,0 16,0
              C24.836556,0 32,7.163444 32,16 C32,24.836556 24.836556,32 16,32 Z" />
          </svg>
        </a>
      </div>

    </div>

  </section>
</main>
