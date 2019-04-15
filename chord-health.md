---
title: Chord Health
layout: page
description: San Diego spinal chord health.
---

<!-- Chord Health Landing Page -->
<header id="chord-health">
  <div class="container">
    <div class="intro-text">
      <h1 class="intro-heading">Get A Healthier Spine</h1>
      <h2 class="intro-lead-in">On Your Schedule</h2>
      <a href="#location-content" class="page-scroll btn btn-xl">Learn More</a>
    </div>
  </div>
</header>
<section id="location-content">
  <div class="container">
    <div class="row">
      <div class="col-lg-7">
        <h2 class="section-heading">Nothing is More Expensive Than Your Time</h2>
        <h4 class="subheading">Chord Health</h4>
        <p class="text-muted">We believe that healthcare should be immediate, on your schedule, and add to your life ... not get in the way of it. Pain-free movement is something we take for granted until it’s taken away from us. It’s easy to forget that movement is how we interact with the world, interact with those we care for, and is the vehicle for new, exciting experiences.</p>
      </div>
      <div class="col-lg-5">
        <form name="chord-health-form" netlify>
          <!-- Netlify honeypot field -->
          <p class='hidden'>
            <label>Don’t fill this out: <input name='surname'></label>
          </p>
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
            <label for="dob">Your Phone Number</label>
            <input type="date" name="DOB" id="dob" class="form-control" required>
            <!-- Textarea -->
            <label for="condition">Tell Us About Your Condition</label>
            <textarea name="condition" id="condition" class="form-control" maxlength="2000" rows="8" cols="80" required></textarea>
            <!-- Submit button -->
            <input type="submit" value="Schedule Your Call" class="btn btn-xl">
          </div>
        </form>
      </div>
    </div>
  </div>
</section>
