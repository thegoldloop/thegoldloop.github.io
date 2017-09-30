---
layout: default
title: Contact Us
---

<section class="uk-section uk-section-default uk-section-xsmall">
  <h1>Talk to Us</h1>
  <form class="uk-form-stacked" method="POST" action="https://formspree.io/support@thegoldloop.com">
    <!-- TODO 
    <input type="hidden" name="_next" value="//site.io/thanks.html" />
    <input type="hidden" name="_subject" value="New submission!" />
    -->
    <div class="uk-margin">
      <label class="uk-form-label" for="form-stacked-text">Name</label>
      <div class="uk-form-controls">
        <input class="uk-input" type="text" name="name" placeholder="Your name"/>
      </div>
    </div>
    <div class="uk-margin">
      <label class="uk-form-label" for="form-stacked-text">E-Mail</label>
      <div class="uk-form-controls">
        <input class="uk-input" type="email" name="email" placeholder="Your e-mail address"/>
      </div>
    </div>
    <div class="uk-margin">
      <label class="uk-form-label" for="form-stacked-text">Message</label>
      <div class="uk-form-controls">
        <textarea class="uk-textarea" name="message" placeholder="Your message"></textarea>
      </div>
    </div>
    <div class="uk-margin">
      <input type="submit" value="SEND" class="uk-button uk-button-primary"/>
    </div>
  </form>
</section>