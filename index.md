---
layout: default
title: Demonstration Website
---

# Octi: Supplementary Demo

Octi is an LMS-integrated platform for collaborative writing analytics and feedback. Embedded with LTI, it combines two components within a privacy-by-design approach:

- **OctiPad**: a collaborative editor with structured workspaces for real-time group writing.
- **OctiFeedback**: a component that generates scheduled, text-based feedback on collaborative processes.

---

## System Overview

Octi is designed to support both instructional use and research-oriented data collection. In the research setting, learners collaborate in structured workspaces in OctiPad, while OctiFeedback provides scheduled text-based guidance aligned with the task and collaboration goals.

<section class="figure-grid" aria-label="System overview figure">
  <figure class="figure-card figure-wide">
    <img src="{{ '/assets/images/general/system-overview.png' | relative_url }}" alt="Placeholder figure: Octi system overview" loading="lazy" />
    <figcaption>
      <strong>Figure 1.</strong> Overview of Octi’s Moodle integration and data flow. The figure illustrates the two components, OctiPad and OctiFeedback, and their integration into a Moodle course. The arrows indicate the flow of data from the collaborative writing activity to the feedback generation and analytics processes.
    </figcaption>
  </figure>
</section>

---

## OctiPad and OctiFeedback in Moodle

<section id="octipad-feedback" class="figure-grid" aria-label="OctiPad and OctiFeedback in Moodle figure and video">
  <figure class="figure-card figure-half">
    <img src="{{ '/assets/images/general/octipad-octifeedback-moodle.png' | relative_url }}" alt="Placeholder figure: OctiPad and OctiFeedback in Moodle" loading="lazy" />
    <figcaption>
      <strong>Figure 2.</strong> Illustration of OctiPad and OctiFeedback embedded within a Moodle course. The figure shows how learners access the collaborative writing activity through the LMS, while the feedback component provides scheduled guidance based on interaction traces.
    </figcaption>
  </figure>
  <figure class="figure-card figure-half video-card"
        data-video-src="{{ '/assets/video/octipad-features-explained.mp4' | relative_url }}">
    <div class="video-thumb">
      <img src="{{ '/assets/images/general/octi-banner.png' | relative_url }}" alt="OctiPad walkthrough video thumbnail" />
      <div class="video-play-btn" aria-hidden="true">
        <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
          <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
          <polygon points="33,25 60,40 33,55" fill="white"/>
        </svg>
      </div>
    </div>
    <figcaption>
      <strong>Video 1.</strong> Walkthrough of OctiPad's core features (currently in German). || Later demonstration of a walkthrough through a moodle course with OctiPad and OctiFeedback, showing the student perspective and the feedback process.
    </figcaption>
  </figure>
</section>


## OctiPad in use

The following figures illustrate the collaborative editor in use, with structured workspaces that guide group activity and support real-time coordination. The screenshots are placeholders and will be replaced with research images.

<section id="octipad-figures" class="figure-grid" aria-label="OctiPad screenshots">
  <figure class="figure-card">
    <img src="{{ '/assets/images/octipad/octipad-workspace-areas.png' | relative_url }}" alt="Image of OctiPad workspace areas" loading="lazy" />
    <figcaption>
      <strong>Figure 2.</strong> OctiPad structured workspace layout.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/octipad/student-task.png' | relative_url }}" alt="image of OctiPad students' task overview" loading="lazy" />
    <figcaption>
      <strong>Figure 3.</strong> General idea and overview of the students' task.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholders/octipad-workspace-03.svg' | relative_url }}" alt="Image of the component within moodle" loading="lazy" />
    <figcaption>
      <strong>Figure 4.</strong> Appearance of the component within moodle.
    </figcaption>
  </figure>
</section>

<section id="octipad-video" class="figure-grid figure-grid-solo" aria-label="OctiPad video">
  <figure class="figure-card video-card"
          data-video-src="{{ '/assets/video/octipad-features-explained.mp4' | relative_url }}">
    <div class="video-thumb">
      <img src="{{ '/assets/video/octipad-banner.svg' | relative_url }}" alt="OctiPad walkthrough video thumbnail" />
      <div class="video-play-btn" aria-hidden="true">
        <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
          <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
          <polygon points="33,25 60,40 33,55" fill="white"/>
        </svg>
      </div>
    </div>
    <figcaption>
      <strong>Video 1.</strong> Walkthrough of OctiPad's core features (currently in German). || Later demonstration of a walkthrough through a moodle course with OctiPad and OctiFeedback, showing the student perspective and the feedback process.
    </figcaption>
  </figure>
</section>

<div class="callout">
  <div class="callout-title">Access</div>
  <p class="callout-text">
    OctiPad can be accessed as a standalone demonstration instance.
    The same editor can also be embedded into learning management systems via LTI. 
    Please note that the demonstration instance is not connected to a learning management system and does not provide any feedback messages.
  </p>
  <p class="callout-text callout-notice">
    This demo link is temporarily disabled to avoid revealing the authors' identities during peer review.
  </p>
  <p class="callout-actions">
    <a class="btn btn-primary btn-disabled" aria-disabled="true" tabindex="-1">Open OctiPad (Standalone) - disabled</a>
    <!-- <a class="btn btn-secondary" href="#octipad-figures">Jump to Figures</a> -->
  </p>
</div>

---

## OctiFeedback in use

OctiFeedback provides scheduled feedback aligned with collaborative processes. Indicators can be computed from interaction traces to represent, for example, activation of prior knowledge, coordination and organization, and individual and group contributions. The examples below illustrate how feedback messages are presented.

<section id="octifeedback-figures" class="figure-grid" aria-label="OctiFeedback screenshots">
  <figure class="figure-card">
    <img src="{{ '/assets/images/octipad/feedback-indicators.png' | relative_url }}" alt="Feedback indicators explained" loading="lazy" />
    <figcaption>
      <strong>Figure 5.</strong> An overview of the current feedback indicators for analyzis.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholders/octifeedback-02.svg' | relative_url }}" alt="Placeholder screenshot: OctiFeedback message example (2)" loading="lazy" />
    <figcaption>
      <strong>Figure 6.</strong> Example feedback message highlighting individual and group contributions (placeholder).
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholders/octifeedback-03.svg' | relative_url }}" alt="Placeholder screenshot: OctiFeedback message example (3)" loading="lazy" />
    <figcaption>
      <strong>Figure 7.</strong> Example feedback message related to activation of prior knowledge (placeholder).
    </figcaption>
  </figure>
</section>

<section id="octifeedback-video" class="figure-grid figure-grid-solo" aria-label="OctiFeedback video">
  <figure class="figure-card video-card"
          data-video-src="{{ '/assets/video/octipad-features-explained.mp4' | relative_url }}">
    <div class="video-thumb">
      <img src="{{ '/assets/images/octifeedback/octifeedback-banner.png' | relative_url }}" alt="OctiFeedback walkthrough video thumbnail" />
      <div class="video-play-btn" aria-hidden="true">
        <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
          <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
          <polygon points="33,25 60,40 33,55" fill="white"/>
        </svg>
      </div>
    </div>
    <figcaption>
      <strong>Video 1.</strong> Walkthrough of OctiFeedback's core features. || Later demonstration of a walkthrough through a moodle course with OctiPad and OctiFeedback, showing the student perspective and the feedback process.
    </figcaption>
  </figure>
</section>

<div class="callout">
  <div class="callout-title">Access</div>
  <p class="callout-text">
    OctiFeedback cannot be accessed as a standalone instance, because it depends on collaborative writing activity in multiple OctiPad workspaces within a course context (e.g., an LMS such as Moodle). Instead, a demonstration video is provided to illustrate how OctiFeedback appears and behaves when integrated into an actual course.
  </p>
  <p class="callout-actions">
    <a class="btn btn-primary" href="#octipad-feedback">Jump to Video</a>
  </p>
</div>

---

## Paper, citation, and contact

**Paper (placeholder,  available after publication):** [Link to the paper (to be added)](#)

**Recommended citation (placeholder, available after publication):**

> Author(s). (Year). *From Edits to Insights: Octi, a Learning Analytics Tool for Collaborative Writing in an LMS*. Venue/Journal. DOI/URL.

**BibTeX (placeholder,  available after publication):**

```bibtex
@inproceedings{octi_placeholder_2026,
  title   = {From Edits to Insights: Octi, a Learning Analytics Tool for Collaborative Writing in an LMS},
  author  = {Author, First and Author, Second},
  year    = {2026},
  url     = {https://example.org/paper-link-placeholder},
}
```

**Contact (placeholder,  available after publication):** Name, Institution — `name.surname@institution.example`