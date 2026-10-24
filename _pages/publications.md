---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="alert alert-info d-flex flex-column flex-md-row align-items-md-center justify-content-between p-4 mb-4 rounded shadow-sm" role="alert" style="border-left: 5px solid var(--global-theme-color);">
  <div class="mb-3 mb-md-0 pr-md-3">
    <h5 class="alert-heading font-weight-bold mb-1">
      <i class="ai ai-google-scholar mr-1"></i> Full &amp; Real-Time Publication List
    </h5>
    <p class="mb-0" style="font-size: 0.95rem;">
      This page highlights selected papers and preprints. Because I do not manually update the BibTeX archive for every publication, please visit my Google Scholar profile for my complete, most up-to-date list of papers and citation metrics.
    </p>
  </div>
  <div class="flex-shrink-0">
    <a href="https://scholar.google.com/citations?user={{ site.scholar_userid }}" target="_blank" rel="noopener noreferrer" class="btn btn-primary font-weight-bold px-3 py-2 text-center" style="white-space: normal;">
      View Full &amp; Up-to-Date Publications on Google Scholar ↗
    </a>
  </div>
</div>

<div class="publications">

{% bibliography %}

</div>
