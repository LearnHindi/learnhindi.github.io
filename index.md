---
layout: minimal
title: "Barhakhari - Guide for Nepali Alphabets"
#permalink: /marketing/
---

<head>
  <link rel="icon" href="/favicon.png" type="image/png">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
</head>

<style>
  /* General reset */
  body {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    color: #fff;
    overflow-x: hidden;
  }

  /* Full-page background */
  .background-image {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('/back.jpg');
    background-size: cover;
    background-position: center;
    z-index: -2;
  }

  /* Blur overlay */
  .blur-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    background-color: rgba(0, 0, 0, 0.1);
    z-index: -1;
  }

  /* Top-right buttons */
  .top-right-buttons {
    position: absolute;
    top: 20px;
    right: 5px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 1px;
  }

  .button-link {
    background-color: clear;
    color: #fff;
    padding: 5px 15px;
    border: none;
    border-radius: 8px;
    font-size: 0.8em;
    font-weight: 600;
    cursor: pointer;
    text-decoration: none;
    transition: transform 0.3s, opacity 0.3s;
  }

  .button-link:hover {
    transform: scale(1.1);
    opacity: 0.9;
  }

  /* Main container */
  .content-container {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 20px;
  }

  /* Left half with mobile screenshot */
  .left-half {
    flex: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    animation: fadeIn 1s ease-in-out;
  }

  .left-half img {
    width: 100%;
    max-width: 1000px;
    height: auto;
    max-height: 2000px;
    border-radius: 15px;
    transition: transform 0.3s;
  }

  .left-half img:hover {
    transform: scale(1.05);
  }

  /* Right half with text and button */
  .right-half {
    flex: 1;
    padding: 20px;
    text-align: left;
    animation: slideIn 1s ease-in-out;
  }

  .title {
    font-size: 3em;
    font-weight: 700;
    margin-bottom: 20px;
  }

  .description {
    font-size: 1.5em;
    font-weight: 400;
    margin-bottom: 20px;
    line-height: 1.6;
  }

  .additional-info {
    font-size: 1.2em;
    font-weight: 400;
    margin-bottom: 30px;
  }

  /* App Store button and contact label container */
  .app-store-container {
    margin-top: 20px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
  }

  .app-store-button {
    display: inline-block;
    width: 250px;
    height: 70px;
    background-image: url('/appstore.png');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
    border-radius: 12px;
    text-indent: -9999px;
    transition: transform 0.3s, opacity 0.3s;
  }

  .app-store-button:hover {
    transform: scale(1.1);
    opacity: 0.9;
  }

  .contact-label {
    margin-top: 30px;
    font-size: 1em;
    color: #fff;
    background-color: rgba(0, 0, 0, 0.0);
    padding: 0px 0px;
  }

  .contact-label b {
    font-weight: 700;
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .content-container {
      flex-direction: column;
    }

    .left-half, .right-half {
      flex: none;
      width: 100%;
      text-align: center;
    }

    .left-half img {
      max-width: 300px;
    }

    .right-half {
      padding: 0;
    }

    .app-store-container {
      align-items: center;
    }
  }

  /* Animations */
  @keyframes fadeIn {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

  @keyframes slideIn {
    from {
      transform: translateY(30px);
      opacity: 0;
    }
    to {
      transform: translateY(0);
      opacity: 1;
    }
  }
</style>

<div class="background-image"></div>
<div class="blur-overlay"></div>

<!-- Top-right Buttons -->
<div class="top-right-buttons">
  <a href="faq" class="button-link">FAQs</a>
  <a href="https://barhakhari.github.io/privacy-policy/" class="button-link">Privacy Policy</a>
</div>

<div class="content-container">
  <!-- Left half with mobile screenshot -->
  <div class="left-half">
    <img src="/mock.png" alt="Mobile Screenshot">
  </div>

  <!-- Right half with text and button -->
  <div class="right-half">
    <div class="title">Introducing Barhakhari - Guide for Nepali alphabets</div>
    <div class="description">
      "Empowering young minds to trace the roots of our language, one Nepali letter at a time."
    </div>
    <div class="additional-info">
      This app will guide children to write Nepali Vowels, Consonants, Numbers, and Barhakhari.
    </div>
    <!-- App Store Button and Contact Label -->
    <div class="app-store-container">
      <a href="https://apps.apple.com/us/app/barhakhari/id6740243356" class="app-store-button" target="_blank" aria-label="Download on the App Store"></a>
      <div class="contact-label">
        Contact us: <b>barhakharinepal@gmail.com</b>
      </div>
    </div>
  </div>
</div>
