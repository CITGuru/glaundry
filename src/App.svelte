<script>
  export let name;
  import Pay from "./Pay.svelte";
</script>

<style>

</style>

<div id="logo-div">
  <img id="logo" src="./gl_logo.png" alt="logo" />
</div>
<div id="tagline">
  <div class="tagline-item" id="tagline-1">
    We pick up your laundry in Philadelphia, wash it, and bring it back.
  </div>
  <div class="tagline-item" id="tagline-2">Only $49/wk</div>
  <div class="tagline-item" id="tagline-3">
    Cancel or skip a week anytime without talking to a human.
  </div>
</div>
<div id="testimonials">
  <div class="testimonial testimonial-text" id="testimonial-1">
    Sixty three pounds of laundry delivered by GotLaundry. ...all sorted and
    folded. The pick-ups and drop-offs are always on time.
    <div class="trestimonial-text byline">- Chante M.</div>
  </div>
  <div class="testimonial testimonial-text" id="testimonial-1">
    I could have cried seeing all my clothes and linens folded and smelling so
    clean and fresh and good.
    <div class="testimonial-text byline">- Shawde M.</div>
  </div>
  <div class="testimonial testimonial-text" id="testimonial-1">
    Ray & Kia were super friendly and made me feel as though everything was
    taken care of , and trust me it was.
    <div class="testimonial-text byline">- Miss H</div>
  </div>
</div>
<div>
  <Pay />
</div>
