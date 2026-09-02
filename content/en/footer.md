---
type: 'footer'
weight: 1
coffee: 2
params:
    headless: true
    target: 'https://github.com/foxihd/hugo-brewm'
---

**Impressum**


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

<br>

<audio id="startup-audio" src="D:\vandanswebbie\Vettis2cents\content\en" preload="auto"></audio>

<script>
  function playStartupAudio() {
    const audio = document.getElementById('startup-audio');
    if (audio) {
      audio.play().catch(error => {
        console.log("Autoplay prevented. Waiting for user interaction.");
      });
    }
    // Remove listeners so it only plays once
    document.removeEventListener('click', playStartupAudio);
    document.removeEventListener('keydown', playStartupAudio);
  }

  // Fallback for browser autoplay restrictions
  document.addEventListener('click', playStartupAudio);
  document.addEventListener('keydown', playStartupAudio);
</script>

<fieldset id=cookie-banner>
<legend>Cookie Banner</legend>
<div>
<span>We do not collect cookie</span>
<img id="no-cookie" alt="No Cookie for Cookie Monster" />
</div>
</fieldset>