---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
widget1:
  title: "Open</br>Source"
  url: 'https://fastmath-scidac.llnl.gov/software-catalog.html'
  video: '<a href="#" data-reveal-id="videoModal1"><img src="images/FASTMath_logo2.png" width="302" height="182" alt=""/></a>'
  text: '<ul><li>Numerically Rigorous.</li><li>Community Adopted.</li><li>Fully Supported.</li><li>Proven Results.</li></ul>'
widget2:
  title: "Ease of Use</br>&nbsp;"
  url: 'https://xsdk.info'
  text: '<a href="http://spack.io"><ul><li>Easy Download.</li><li>Easy Configure & Install.</li><li>Easy Dependencies.</li><li>Easy Update.</li></ul></a>'
  video: '<a href="#" data-reveal-id="videoModal2"><img src="images/xsdk_logo5.png" width="302" height="150" alt=""/></a>'
widget3:
  title: "Enhanced</br>Productivity"
  url: 'https://bssw.io'
  text: '<ul><li>Development Resources.</li><li>Shared Know-How.</li><li>Common Tools.</li><li>Training.</li></ul>'
  video: '<a href="#" data-reveal-id="videoModal3"><img src="images/bssw_wide_trans.png" width="302" height="182" alt=""/></a>'
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
  url: https://bssw.io/pages/receive-our-email-digest 
  text: How can I get involved?
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

# Placeholder for Lois' Content

[//]: # (The stuff below is defining div elements that match the video links above)
[//]: # (Because div elements themselves don't render, this stuff produces no output)
[//]: # (but does provide the target for the video links)

<div id="videoModal1" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/LBfxK59byxU?start=19" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
<div id="videoModal2" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/AgELh5xW-lQ?start=24" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="videoModal3" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/5waBynVgxuc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
