---
title: Chord Health
layout: page
description: San Diego spinal chord health.
---

<!-- Chord Health Landing Page -->
<header id="chord-health">
  <div class="container">
    <div class="intro-text">
      <h1 class="intro-heading">World-Renowned Spine Treatment</h1>
      <h2 class="intro-lead-in">ON DEMAND</h2>
      <a href="#location-content" class="page-scroll btn btn-xl">Learn More</a>
    </div>
  </div>
</header>
<section id="location-content">
  <div class="container">
    <div class="row">
      <div class="col-lg-7">
        <h2 class="section-heading">Nothing is More Expensive Than Your Time</h2>
        <h4 class="subheading">Get Better, Faster with Chord Health</h4>
        <p class="text-muted">Instead of paying ridiculous out-of-pocket costs for therapy (high deductibles, co-pays, co-insurances, etc.) and traveling to and from physical therapy, why not access treatment when it's convenient for YOU?</p>
        <p class="text-muted">Our high-quality conservative care is prescribed by a doctor, saves time and money, and can be completed from the comfort of your own home. Though our delivery approach is novel, our content is based on the proven guidelines published by world-renowned governing bodies in healthcare.</p>
        <img src="/uploads/APS-logo.png" alt="aps logo">
        <img src="/uploads/AAOS-logo.png" alt="aaos logo">
        <img src="/uploads/apta-logo.png" alt="apta logo">
        <img src="/uploads/Acp-logo.png" alt="acp logo">
        <a href="#chord-health-form" class="page-scroll btn btn-xl">Get a Free Doctor Consultation</a>
      </div>
      <div class="col-lg-5">
        <img src="/uploads/chord-health-ipad.png" alt="chord health ipad image">
      </div>
    </div>
    <div class="row" id="chord-health-form">
      <form name="chord-health-form" netlify-honeypot="surname" action="/chordhealth-thank-you/" netlify>
          <!-- Netlify honeypot field -->
          <p class='hidden'>
            <label>Don’t fill this out: <input name='surname'></label>
          </p>
        <div class="col-lg-6">
          <!-- Standard form fields -->
          <div class="control-group form-group">
            <!-- Name field -->
            <label for="name">Your Name</label>
            <input type="text" name="name" id="name" class="form-control" required>
            <!-- Email field -->
            <label for="email">Your Email Address</label>
            <input type="email" name="email" id="email" class="form-control" required>
            <!-- Phone field -->
            <label for="phone">Your Phone Number</label>
            <input type="phone" name="phone" id="phone" class="form-control" required>
            <!-- DOB field -->
            <label for="dob">Your Date of Birth</label>
            <input type="date" name="DOB" id="dob" class="form-control" required>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="control-group form-group">
            <!-- Select field -->
            <label for="source">How Did You Hear About Chord Health?</label>
            <select name="source" id="source" class="form-control" required>
              <option value="">--Please Choose an Option--</option>
              <option value="doctor-referral">Doctor Referral</option>
              <option value="facebook">Facebook</option>
              <option value="other">Other</option>
            </select>
            <!-- Textarea -->
            <label for="condition">Tell Us About Your Condition</label>
            <textarea name="condition" id="condition" class="form-control" maxlength="2000" rows="6" required></textarea>
            <!-- Submit button -->
            <input type="submit" value="Schedule Your Call" class="btn btn-xl">
          </div>
        </div>
      </form>
    </div>
  </div>
</section>
