---
layout: page
title: "Submit a Tip"
subtitle: "Have information about the Mantello administration? We want to hear from you."
permalink: /submit-tip/
---

If you have a document, source, lead, or eyewitness account related to Mayor Mantello or her administration, use the form below. We review every submission.

Your name and contact information are for our use only and will never be published without your explicit permission. If you want to remain anonymous, you may leave those fields blank — though a contact method helps us follow up if we need more detail.

<div class="tip-form">
  <form action="https://formspree.io/info@themantellorecord.com" method="POST">
    <input type="hidden" name="_subject" value="New tip — The Mantello Record">

    <div class="form-group">
      <label for="name">Your Name (optional)</label>
      <input type="text" id="name" name="name" placeholder="Anonymous is fine">
    </div>

    <div class="form-group">
      <label for="email">Email Address (optional)</label>
      <input type="email" id="email" name="email" placeholder="So we can follow up if needed">
    </div>

    <div class="form-group">
      <label for="tip-type">Type of Tip</label>
      <select id="tip-type" name="tip-type">
        <option value="">Select one...</option>
        <option value="document">Document or Record</option>
        <option value="eyewitness">Eyewitness Account</option>
        <option value="news-link">News Link or Article</option>
        <option value="source-lead">Source or Lead</option>
        <option value="other">Other</option>
      </select>
    </div>

    <div class="form-group">
      <label for="message">Your Tip</label>
      <textarea id="message" name="message" placeholder="Describe what you know, saw, or have. Include links, dates, and names where you can."></textarea>
    </div>

    <button type="submit" class="form-submit">Submit Tip</button>
  </form>

  <p class="form-note">We do not publish names without permission. We do not share submissions with third parties. If you have sensitive documents, contact us first before uploading anything anywhere.</p>
</div>
