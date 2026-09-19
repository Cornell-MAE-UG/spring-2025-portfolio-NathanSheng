---
layout: default
title: Nathan Sheng - Resume
permalink: /cv/
---

## Curriculum Vitae

[Download my CV]({{ "/assets/CV.pdf" | relative_url }}?v=20260918) in PDF format.

**Email:** [nxs2@cornell.edu](mailto:nxs2@cornell.edu) &nbsp;&nbsp; **Phone:** 607 333 8131

<div class="resume-page">
  <object
    class="resume-pdf"
    data="{{ '/assets/CV.pdf' | relative_url }}?v=20260918#view=FitH"
    type="application/pdf"
    aria-label="Nathan Sheng's resume"
  >
    <p>
      Your browser cannot display the embedded PDF.
      <a href="{{ '/assets/CV.pdf' | relative_url }}?v=20260918">Open or download my resume</a>.
    </p>
  </object>

</div>

<style>
  .resume-page {
    margin: 1.5rem 0;
  }

  .resume-pdf {
    display: block;
    width: 100%;
    height: calc(100vh - 12rem);
    min-height: 700px;
    border: 1px solid rgba(0, 0, 0, 0.15);
    border-radius: 0.25rem;
  }

  @media (max-width: 767px) {
    .resume-pdf {
      min-height: 600px;
    }
  }
</style>
