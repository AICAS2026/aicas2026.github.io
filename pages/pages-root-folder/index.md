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
  text: '<em>Full-paper Submission: <span style="color: red;">March 22, 2026</span></em><br/><em>Notification of acceptance: <span style="color: red;">June 18, 2026</span></em> <br/>	<em>Camera-ready submission: <span style="color: red;">July 10, 2026</span></em><br/>	<em>Advance registration: <span style="color: red;">July 10, 2026</span></em><br/><br/>'
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
