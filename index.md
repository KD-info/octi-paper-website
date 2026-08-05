---
layout: default
title: Demonstration Website
---

# [Tool]: Supplementary Demo

[Tool] is an LMS-integrated platform for collaborative writing analytics and feedback. Embedded with LTI, it combines two components within a privacy-by-design approach:

- **[Tool]Pad**: a collaborative editor with structured workspaces for real-time group writing.
- **[Tool]Feedback**: a component that generates scheduled, text-based feedback on collaborative processes.

---

## System Overview

[Tool] is designed to support both instructional use and research-oriented data collection. In the research setting, learners collaborate in structured workspaces in [Tool]Pad, while [Tool]Feedback provides scheduled text-based guidance aligned with the task and collaboration goals.

<section class="figure-grid" aria-label="System overview figure">
  <figure class="figure-card figure-wide">
    <img src="{{ '/assets/images/general/system-overview.png' | relative_url }}" alt="Placeholder figure: [Tool] system overview" loading="lazy" />
    <figcaption>
      <strong>Figure 1.</strong> Overview of [Tool]’s Moodle integration and data flow. The figure illustrates the two components, [Tool]Pad and [Tool]Feedback, and their integration into a Moodle course. The arrows indicate the flow of data from the collaborative writing activity to the feedback generation and analytics processes.
    </figcaption>
  </figure>
</section>

---

## [Tool]Pad and [Tool]Feedback in Moodle

<section id="toolpad-feedback" class="figure-grid" aria-label="[Tool]Pad and [Tool]Feedback in Moodle figure and video">
  <figure class="figure-card figure-half">
    <img src="{{ '/assets/images/general/toolpad-toolfeedback-moodle.png' | relative_url }}" alt="Placeholder figure: [Tool]Pad and [Tool]Feedback in Moodle" loading="lazy" />
    <figcaption>
      <strong>Figure 2.</strong> Illustration of [Tool]Pad and [Tool]Feedback embedded within a Moodle course. The figure shows how learners access the collaborative writing activity through the LMS, while the feedback component provides scheduled guidance based on interaction traces.
    </figcaption>
  </figure>
  <figure class="figure-card figure-half video-card"
        data-video-src="{{ '/assets/video/toolpad-features-explained.mp4' | relative_url }}">
    <div class="video-thumb">
      <img src="{{ '/assets/images/general/tool-banner-placeholder.png' | relative_url }}" alt="[Tool]Pad walkthrough video thumbnail" />
      <div class="video-play-btn" aria-hidden="true">
        <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
          <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
          <polygon points="33,25 60,40 33,55" fill="white"/>
        </svg>
      </div>
    </div>
    <figcaption>
      <strong>Video 1.</strong> Walkthrough of [Tool]Pad's core features (currently in German). || Later demonstration of a walkthrough through a moodle course with [Tool]Pad and [Tool]Feedback, showing the student perspective and the feedback process.
    </figcaption>
  </figure>
</section>


## [Tool]Pad in use

The following figures illustrate the collaborative editor in use, with structured workspaces that guide group activity and support real-time coordination. The screenshots are placeholders and will be replaced with research images.

<section id="toolpad-figures" class="figure-grid" aria-label="[Tool]Pad screenshots">
  <figure class="figure-card">
    <img src="{{ '/assets/images/toolpad/toolpad-workspace-areas.png' | relative_url }}" alt="Image of [Tool]Pad workspace areas" loading="lazy" />
    <figcaption>
      <strong>Figure 2.</strong> [Tool]Pad structured workspace layout.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/toolpad/student-task.png' | relative_url }}" alt="image of [Tool]Pad students' task overview" loading="lazy" />
    <figcaption>
      <strong>Figure 3.</strong> General idea and overview of the students' task.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholders/toolpad-workspace-03.svg' | relative_url }}" alt="Image of the component within moodle" loading="lazy" />
    <figcaption>
      <strong>Figure 4.</strong> Appearance of the component within moodle.
    </figcaption>
  </figure>
</section>

<section id="toolpad-video" class="figure-grid figure-grid-solo" aria-label="[Tool]Pad video">
  <figure class="figure-card video-card"
          data-video-src="{{ '/assets/video/toolpad-features-explained.mp4' | relative_url }}">
    <div class="video-thumb">
      <img src="{{ '/assets/toolpad/toolpad-banner-placeholder.png' | relative_url }}" alt="[Tool]Pad walkthrough video thumbnail" />
      <div class="video-play-btn" aria-hidden="true">
        <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
          <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
          <polygon points="33,25 60,40 33,55" fill="white"/>
        </svg>
      </div>
    </div>
    <figcaption>
      <strong>Video 1.</strong> Walkthrough of [Tool]Pad's core features (currently in German). || Later demonstration of a walkthrough through a moodle course with [Tool]Pad and [Tool]Feedback, showing the student perspective and the feedback process.
    </figcaption>
  </figure>
</section>

<div class="callout">
  <div class="callout-title">Access</div>
  <p class="callout-text">
    [Tool]Pad can be accessed as a standalone demonstration instance.
    The same editor can also be embedded into learning management systems via LTI. 
    Please note that the demonstration instance is not connected to a learning management system and does not provide any feedback messages.
  </p>
  <p class="callout-text callout-notice">
    This demo link is temporarily disabled to avoid revealing the authors' identities during peer review.
  </p>
  <p class="callout-actions">
    <a class="btn btn-primary btn-disabled" aria-disabled="true" tabindex="-1">Open [Tool]Pad (Standalone) - disabled</a>
    <!-- <a class="btn btn-secondary" href="#toolpad-figures">Jump to Figures</a> -->
  </p>
</div>

---

## [Tool]Feedback in use

[Tool]Feedback provides scheduled feedback aligned with collaborative processes. Indicators can be computed from interaction traces to represent, for example, activation of prior knowledge, coordination and organization, and individual and group contributions. The examples below illustrate how feedback messages are presented.

<section id="toolfeedback-figures" class="figure-grid" aria-label="[Tool]Feedback screenshots">
  <figure class="figure-card">
    <img src="{{ '/assets/images/toolpad/feedback-indicators.png' | relative_url }}" alt="Feedback indicators explained" loading="lazy" />
    <figcaption>
      <strong>Figure 5.</strong> An overview of the current feedback indicators for analyzis.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholders/toolfeedback-02.svg' | relative_url }}" alt="Placeholder screenshot: [Tool]Feedback message example (2)" loading="lazy" />
    <figcaption>
      <strong>Figure 6.</strong> Example feedback message highlighting individual and group contributions (placeholder).
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/placeholders/toolfeedback-03.svg' | relative_url }}" alt="Placeholder screenshot: [Tool]Feedback message example (3)" loading="lazy" />
    <figcaption>
      <strong>Figure 7.</strong> Example feedback message related to activation of prior knowledge (placeholder).
    </figcaption>
  </figure>
</section>

<section id="toolfeedback-video" class="figure-grid figure-grid-solo" aria-label="[Tool]Feedback video">
  <figure class="figure-card video-card"
          data-video-src="{{ '/assets/video/toolpad-features-explained.mp4' | relative_url }}">
    <div class="video-thumb">
      <img src="{{ '/assets/images/toolfeedback/toolfeedback-banner-placeholder.png' | relative_url }}" alt="[Tool]Feedback walkthrough video thumbnail" />
      <div class="video-play-btn" aria-hidden="true">
        <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
          <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
          <polygon points="33,25 60,40 33,55" fill="white"/>
        </svg>
      </div>
    </div>
    <figcaption>
      <strong>Video 1.</strong> Walkthrough of [Tool]Feedback's core features. || Later demonstration of a walkthrough through a moodle course with [Tool]Pad and [Tool]Feedback, showing the student perspective and the feedback process.
    </figcaption>
  </figure>
</section>

<div class="callout">
  <div class="callout-title">Access</div>
  <p class="callout-text">
    [Tool]Feedback cannot be accessed as a standalone instance, because it depends on collaborative writing activity in multiple [Tool]Pad workspaces within a course context (e.g., an LMS such as Moodle). Instead, a demonstration video is provided to illustrate how [Tool]Feedback appears and behaves when integrated into an actual course.
  </p>
  <p class="callout-actions">
    <a class="btn btn-primary" href="#toolpad-feedback">Jump to Video</a>
  </p>
</div>

---

## Paper, citation, and contact

**Paper (placeholder,  available after publication):** [Link to the paper (to be added)](#)

**Recommended citation (placeholder, available after publication):**

> Author(s). (Year). *From Edits to Insights: [Tool], a Learning Analytics Tool for Collaborative Writing in an LMS*. Venue/Journal. DOI/URL.

**BibTeX (placeholder,  available after publication):**

```bibtex
@inproceedings{[Tool]_placeholder_2026,
  title   = {From Edits to Insights: [Tool], a Learning Analytics Tool for Collaborative Writing in an LMS},
  author  = {Author, First and Author, Second},
  year    = {2026},
  url     = {https://example.org/paper-link-placeholder},
}
```

**Contact (placeholder,  available after publication):** Name, Institution — `name.surname@institution.example`