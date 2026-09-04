---
layout: page
title: "Contact"
permalink: /contact/
description: "Get in touch with KidsGift.in."
---

Spotted a broken link, an outdated price, or have a gift guide you'd like to see? Send a note.

<form class="contact-form" action="mailto:hello@kidsgift.in" method="post" enctype="text/plain" style="display:grid; gap:1rem; max-width:480px; margin-top:1.5rem;">
  <div>
    <label for="name" style="font-weight:600; font-size:0.9rem; display:block; margin-bottom:0.35em;">Name</label>
    <input type="text" id="name" name="name" required style="width:100%; padding:0.7rem 0.85rem; border:1px solid var(--border); border-radius:8px; font-family:inherit;">
  </div>
  <div>
    <label for="email" style="font-weight:600; font-size:0.9rem; display:block; margin-bottom:0.35em;">Email</label>
    <input type="email" id="email" name="email" required style="width:100%; padding:0.7rem 0.85rem; border:1px solid var(--border); border-radius:8px; font-family:inherit;">
  </div>
  <div>
    <label for="message" style="font-weight:600; font-size:0.9rem; display:block; margin-bottom:0.35em;">Message</label>
    <textarea id="message" name="message" rows="4" required style="width:100%; padding:0.7rem 0.85rem; border:1px solid var(--border); border-radius:8px; font-family:inherit;"></textarea>
  </div>
  <button type="submit" class="btn btn-cta" style="justify-self:start;">Send message</button>
</form>

<p style="margin-top:1.5rem; font-size:0.9rem;">Note: a plain mailto form like this opens the visitor's own email app — reliable, but not ideal on every device. If you want submissions to reach you without that, swap this for a free service like <a href="https://formspree.io" target="_blank" rel="noopener">Formspree</a> later; the README covers how.</p>
