---
layout: archive
title: "Opportunities"
permalink: /opportunities/
author_profile: true
---

I welcome inquiries from students interested in research at the intersection of cybersecurity, artificial intelligence, computer networks, and data science. Availability changes with project timelines and funding, so please contact me for the current status.

<div class="opportunity-status">
  <span class="status-dot" aria-hidden="true"></span>
  <div>
    <strong>Current status: inquiries welcome</strong>
    <p>Openings are confirmed individually according to project fit, academic level, and funding availability.</p>
  </div>
</div>

Undergraduate research
======

Suitable for UFU students interested in scientific initiation, final projects, software development, experiments, or research data analysis.

Master's and doctoral research
======

Prospective graduate students should review the admission process of UFU's Graduate Program in Computer Science and contact me with a short description of their background and research interests.

Topics of interest
======

- Intrusion detection and security analytics
- Malware and malicious-content analysis
- Cyber threat intelligence
- Artificial intelligence for cybersecurity
- Security of IoT and cyber-physical systems
- Network monitoring and incident response

How to get in touch
======

Use the button below with the subject **Prospective student (Interesse em orientação)**. Please include your academic level, CV, availability, and the topic that interests you.

<button type="button" class="btn btn--info" id="prospective-student-contact">Send me an email</button>

<script>
(function () {
  var button = document.getElementById("prospective-student-contact");
  if (!button) return;

  button.addEventListener("click", function () {
    var address = String.fromCharCode(109, 105, 97, 110, 105, 64, 117, 102, 117, 46, 98, 114);
    var subject = encodeURIComponent("Prospective student (Interesse em orientação)");
    window.location.href = "mailto:" + address + "?subject=" + subject;
  });
})();
</script>
