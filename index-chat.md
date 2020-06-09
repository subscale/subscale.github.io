---
layout: default
title: Subscale
search: exclude
permalink: /index-chat/
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---
<div class="row">
  
  <div class="col m7 s12" id="hero">
    <div class="row">
      <h1>We're Hiring</h1>
      <p>
        Subscale is a well funded <b>remote-first</b> company reinventing <b>rapid manufacturing of precision parts</b>. Here you will solve challenging problems that have never been solved before, with the autonomy to use whatever methods you think best.
      </p>
      <div class="joblist">
        <h3>Simulation Engineers</h3>
        <p>Good simulation is the foundation for intelligent manufacturing. Subscale's GPU-accelerated geometry and physics code will simulate millions of manufacturing strategies and select the best one. Multidisciplinary background a must. </p><p>Passionate about two or more of the following:</p>
        <ul class="browser-default">
          <li>Computational geometry</li>
          <li>Finite element analysis</li>
          <li>Manufacturing simulation</li>
          <li>C++ and CUDA experience</li>
        </ul>
        <h3>Optimization Engineers</h3>
        <p>The customer's design file must be analyzed to create a manufacturing plan. Generate a plan within the constraints provided by the simulator. Over time, improve tolerances and reduce costs by a few percent every month forever. </p>
        <ul class="browser-default">
          <li>Machine Learning</li>
          <li>Convex Optimization</li>
          <li>Reinforcement Learning</li>
        </ul>
        <h3>Automation Engineers</h3>
        <p>Material handling, assembly, and fabrication challenges. Quantity one automation requires a whole new mindset based on computer vision and sensors, including failsafes at every step. Rapid timelines means it’s faster to modify ordinary machines than to order specialized automated systems, despite the custom mechanical, electrical, and software.</p>
        <ul class="browser-default">
          <li>Machine vision</li>
          <li>Mechanical engineering</li>
          <li>Networking and microcontrollers</li>
          <li>Closed loop control</li>
          <li>Sensor Fusion</li>
        </ul>
        <h3>Full Stack Engineers</h3>
        <p>Build the factory management system integrated with the customer website. Graphics background a plus. User interface challenges include GD&T. Transparency and product quality the guiding principles, standards such ISO/AS/ITAR a must.</p>
      </div><!-- .joblist -->
      
  </div>
</div>

<div class="col m5 s12">
  <div id="formwrap" data-aos="fade-up">
      <div class="row">
        <h2>We’re building something revolutionary.</h2>
        <p>Contact us if you want to learn more.</p>
      </div>
      <form
        action="https://formspree.io/xbjolyeq"
        method="POST"
      >
      <div class="row">
        <div class="input-field col s12">
        <label for="FNAME" class="">
          Your email:</label>
          <input type="text" name="_replyto" id="FNAME">
      </div>
         <div class="input-field col s12">
        <label for="MESSAGE" class="">
          Your message:
        </label>
          <textarea name="message" id="MESSAGE" class="materialize-textarea"></textarea>
        </div>
        <button id="mc-embedded-subscribe" type="submit" class="btn center-align">Send</button>
        </div>
      </form>

</div>
</div>
<script>
  window.intercomSettings = {
    app_id: "xg935s5s",
    name: "<%= current_user.name %>", // Full name
    email: "<%= current_user.email %>", // Email address
    created_at: "<%= current_user.created_at.to_i %>" // Signup date as a Unix timestamp
  };
</script>

<script>
// We pre-filled your app ID in the widget URL: 'https://widget.intercom.io/widget/xg935s5s'
(function(){var w=window;var ic=w.Intercom;if(typeof ic==="function"){ic('reattach_activator');ic('update',w.intercomSettings);}else{var d=document;var i=function(){i.c(arguments);};i.q=[];i.c=function(args){i.q.push(args);};w.Intercom=i;var l=function(){var s=d.createElement('script');s.type='text/javascript';s.async=true;s.src='https://widget.intercom.io/widget/xg935s5s';var x=d.getElementsByTagName('script')[0];x.parentNode.insertBefore(s,x);};if(w.attachEvent){w.attachEvent('onload',l);}else{w.addEventListener('load',l,false);}}})();
</script>