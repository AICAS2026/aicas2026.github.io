---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "ha-long-bay.jpg"
widget1:
  title: "Ha Long Bay"
  url: '/'
  text: 'Ha Long Bay, famous for its emerald waters and towering limestone pillars, is a haven with the most stunning seascapes, a breathtaking natural wonder, a UNESCO World Heritage site, with about 2,000 islands and islets scattered across its vast expanse.'
  video: '<a href="https://youtu.be/0K7auiJFbyc" data-reveal-id="videoModal"><img src="/images/hon-chong-mai.jpg" width="302" height="182" alt=""/></a>'
widget2:
  title: "Important dates"
  url: '/submission'
  image: Pen-circling-calender-date.jpg
  text: '<em>Full-paper Submission: <span style="color: red;">April 07, 2026</span></em><br/><em>Notification of acceptance: <span style="color: red;">June 18, 2026</span></em> <br/>	<em>Camera-ready submission: <span style="color: red;">July 10, 2026</span></em><br/>	<em>Advance registration: <span style="color: red;">July 10, 2026</span></em><br/><br/>'
widget3:
  title: "Visa & Travel"
  url: 'https://www.vietnamairlines.com/nz/en/travel-information/travel-advice/for-flights-to-Vietnam'
  image: visa-travel.jpg
  text: 'Non-Vietnamese nationals are required to obtain a visa to enter Vietnam. Non-Vietnamese passengers can apply for a visa or an electronic visa (e-visa) to save time. Some nationalities can enter Vietnam without a visa under certain conditions.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://edas.info/N34921
  text: Submit your paper
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/0K7auiJFbyc" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div class="row t60 b20">
  <div class="small-12 columns">
    <h2>&#128204; News &amp; Highlights</h2>
    <ul>
      <li>[Jun 5, 2026] Paper acceptance notifications will be sent by <strong>June 18, 2026</strong>. Please check your registered email.</li>
      <li>[Jun 5, 2026] Camera-ready submission and advance registration deadline: <strong>July 10, 2026</strong>. Details on <a href="/registration/">registration page</a>.</li>
      <li>[Apr 7, 2026] Full-paper submission is now closed. Thank you to all authors who submitted!</li>
      <li>[Jan 15, 2026] <a href="/call-for-papers/">Call for Papers</a> is open. Submit via <a href="https://edas.info/N34921" target="_blank">EDAS</a>.</li>
    </ul>
  </div>
</div>

<div class="row t20 b60">
  <div class="small-12 columns">
    <h2 style="text-align: center;">Our Sponsors</h2>

    <p style="text-align: center; font-size: 1.1em; letter-spacing: 0.05em; color: #555; margin-bottom: 10px;">&#128142; Diamond</p>
    <div style="text-align: center; margin-bottom: 30px;">
      <a href="https://www.t-head.cn/" target="_blank" style="text-decoration: none; border: none; display: inline-block; margin: 0 20px; vertical-align: middle;">
        <img src="/images/sponsors/T-head.png" style="width: 220px; height: auto;"/>
      </a>
      <a href="https://www.ringconn.com/" target="_blank" style="text-decoration: none; border: none; display: inline-block; margin: 0 20px; vertical-align: middle;">
        <img src="/images/sponsors/RingConn.png" style="width: 220px; height: auto;"/>
      </a>
    </div>

    <p style="text-align: center; font-size: 1.1em; letter-spacing: 0.05em; color: #555; margin-bottom: 10px;">&#129353; Platinum</p>
    <div style="text-align: center; margin-bottom: 20px;">
      <a href="https://www.cadence.com/" target="_blank" style="text-decoration: none; border: none; display: inline-block; margin: 0 20px; vertical-align: middle;">
        <img src="/images/sponsors/cadence.jpg" style="width: 140px; height: auto;"/>
      </a>
    </div>

    <p style="text-align: center; margin-top: 10px;">
      <a href="/sponsors/" class="button small radius">View all sponsors &amp; become a sponsor</a>
    </p>
  </div>
</div>
