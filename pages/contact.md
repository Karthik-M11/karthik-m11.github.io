---
layout: post
title: Contact
permalink: /contact/
---

<form class="contact-form" action="https://formspree.io/f/xykbrjpz" method="POST">
  <div class="form-field">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required>
  </div>

  <div class="form-field">
    <label for="email">Email</label>
    <input type="email" id="email" name="email" required>
  </div>

  <div class="form-field form-field--full">
    <label for="subject">Subject</label>
    <input type="text" id="subject" name="subject" required>
  </div>

  <div class="form-field form-field--full">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="8" required></textarea>
  </div>

  <button type="submit">Send Message</button>
</form>
