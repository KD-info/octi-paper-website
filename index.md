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
  <figure class="figure-card figure-wide" style="max-width: 70%; margin: 0 auto;">
    <img src="{{ '/assets/images/general/octi-overview-current-placeholder.png' | relative_url }}" alt="Placeholder figure: [Tool] system overview" loading="lazy" />
    <figcaption>
      <strong>Figure 1.</strong> Overview of the current implementation of [Tool], including its Moodle integration and data flow. The figure illustrates the two components, [Tool]Pad and [Tool]Feedback, and their integration into a Moodle course. The arrows indicate the flow of data from the collaborative writing activity to the feedback generation and analytics processes.
    </figcaption>
  </figure>
</section>

---

## [Tool]Pad and [Tool]Feedback in Moodle

<section id="toolpad-feedback" class="figure-grid" aria-label="[Tool]Pad and [Tool]Feedback in Moodle figure and video">
  <figure class="figure-card figure-half">
    <img src="{{ '/assets/images/general/moodle-tool.png' | relative_url }}" alt="Placeholder figure: [Tool]Pad and [Tool]Feedback in Moodle" loading="lazy" />
    <figcaption>
      <strong>Figure 2.</strong> Illustration of [Tool]Pad and [Tool]Feedback embedded within a Moodle course. The figure shows how learners access the collaborative writing activity through the LMS, and the feedback component providing scheduled guidance based on interaction traces.
    </figcaption>
  </figure>
  <div class="figure-stack figure-half">
        <figure class="figure-card video-card"
          data-video-src="{{ '/assets/video/tool-student.mp4' | relative_url }}">
      <div class="video-thumb">
        <img src="{{ '/assets/images/general/tool-banner-placeholder.png' | relative_url }}" alt="[Tool] walkthrough through moodle video thumbnail from a students perspective" />
        <div class="video-play-btn" aria-hidden="true">
          <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
            <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
            <polygon points="33,25 60,40 33,55" fill="white"/>
          </svg>
        </div>
      </div>
      <figcaption>
        <strong>Video 1.</strong> Demonstration of a walkthrough through a moodle course with [Tool]Pad and [Tool]Feedback from a student's perspective.
      </figcaption>
    </figure>

        <figure class="figure-card video-card"
          data-video-src="{{ '/assets/video/tool-student.mp4' | relative_url }}">
      <div class="video-thumb">
        <img src="{{ '/assets/images/general/tool-banner-placeholder.png' | relative_url }}" alt="[Tool] walkthrough through moodle video thumbnail from a teachers perspective" />
        <div class="video-play-btn" aria-hidden="true">
          <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
            <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
            <polygon points="33,25 60,40 33,55" fill="white"/>
          </svg>
        </div>
      </div>
      <figcaption>
        <strong>Video 2.</strong> Demonstration of a walkthrough through a moodle course with [Tool]Pad and [Tool]Feedback from a teacher's perspective.
      </figcaption>
    </figure>
  </div>
</section>


## [Tool]Pad in use

The following material illustrates the collaborative editor in use, with structured workspaces that guide group activity and support real-time coordination. The video below provides a walkthrough of the core features of [Tool]Pad, while the figure illustrates the structured workspace layout.

<section id="toolpad-figures" class="figure-grid" aria-label="[Tool]Pad screenshots">
  <figure class="figure-card figure-half">
    <img src="{{ '/assets/images/toolpad/toolpad-workspace-areas.png' | relative_url }}" alt="Image of [Tool]Pad workspace areas" loading="lazy" />
    <figcaption>
      <strong>Figure 2.</strong> [Tool]Pad structured workspace layout.
    </figcaption>
  </figure>
    <figure class="figure-card figure-half video-card"
      data-video-src="{{ '/assets/video/toolpad-features-explained.mp4' | relative_url }}">
    <div class="video-thumb">
      <img src="{{ '/assets/images/toolpad/toolpad-banner-placeholder.png' | relative_url }}" alt="[Tool]Pad walkthrough video thumbnail" />
      <div class="video-play-btn" aria-hidden="true">
        <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg" width="56" height="56">
          <circle cx="40" cy="40" r="38" fill="rgba(0,0,0,0.52)" stroke="rgba(255,255,255,0.55)" stroke-width="2"/>
          <polygon points="33,25 60,40 33,55" fill="white"/>
        </svg>
      </div>
    </div>
    <figcaption>
      <strong>Video 1.</strong> Walkthrough of [Tool]Pad's core features.
    </figcaption>
  </figure>
</section>

<div class="callout">
  <div class="callout-title">Access</div>
  <p class="callout-text">
    [Tool]Pad can be accessed as a standalone demonstration instance.
    The same editor can also be embedded into a learning management systems via LTI. 
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

[Tool]Feedback provides scheduled feedback aligned with collaborative processes. Indicators can be computed from interaction traces to represent, for example, activation of prior knowledge, coordination and organization, and individual and group contributions. The examples below illustrate how feedback is presented.

<section id="toolfeedback-student-view" class="figure-grid" aria-label="[Tool]Feedback screenshots">
  <figure class="figure-card">
    <img src="{{ '/assets/images/toolfeedback/student/toolfeedback-overview.png' | relative_url }}" alt="Feedback Overview in [Tool]Feedback explained" loading="lazy" />
    <figcaption>
      <strong>Figure 5.</strong> An overview of the current feedback available in the course for a specific student.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/toolfeedback/student/toolfeedback-selection.png' | relative_url }}" alt="Selection of Feedback for [Tool]Pad explained" loading="lazy" />
    <figcaption>
      <strong>Figure 6.</strong> Example of how feedback for an [Tool]Pad can be selected.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/toolfeedback/student/toolfeedback-example.png' | relative_url }}" alt="Example for Automated Feedback in [Tool]Feedback presented" loading="lazy" />
    <figcaption>
      <strong>Figure 7.</strong> Example of how feedback is currently delivered in [Tool]Feedback to a student.
    </figcaption>
  </figure>
</section>

<section id="toolfeedback-teacher-view" class="figure-grid" aria-label="[Tool]Feedback teacher view screenshots">
  <figure class="figure-card">
    <img src="{{ '/assets/images/toolfeedback/teacher/toolfeedback-schedule.png' | relative_url }}" alt="Feedback Overview Toggle in the external plugin [Tool]Feedback explained" loading="lazy" />
    <figcaption>
      <strong>Figure 8.</strong> The external plugin feature "Content" is used to trigger the feedback schedule overview of [Tool]Feedback for scheduling feedback as a teacher.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/toolfeedback/teacher/toolfeedback-overview-schedule.png' | relative_url }}" alt="Overview of Feedback Schedule for [Tool]Pads in [Tool]Feedback explained" loading="lazy" />
    <figcaption>
      <strong>Figure 9.</strong> Editor of the feedback schedule for specific [Tool]Pads in [Tool]Feedback for teachers.
    </figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/toolfeedback/teacher/toolfeedback-create.png' | relative_url }}" alt="Overview of Selection Options to specify Feedback in [Tool]Feedback presented" loading="lazy" />
    <figcaption>
      <strong>Figure 10.</strong> Current selection options for creating new feedback for specific [Tool]Pads in [Tool]Feedback.
    </figcaption>
  </figure>
</section>

<!-- <section id="toolfeedback-video" class="figure-grid figure-grid-solo" aria-label="[Tool]Feedback video">
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
      <strong>Video 1.</strong> Walkthrough of [Tool]Feedback's core features.
    </figcaption>
  </figure>
</section> -->

<div class="callout">
  <div class="callout-title">Access</div>
  <p class="callout-text">
    [Tool]Feedback cannot be accessed as a standalone instance, because it depends on a collaborative writing activity in multiple [Tool]Pad workspaces within a course context (e.g., an LMS such as Moodle). Instead, a demonstration video is provided to illustrate how [Tool]Feedback appears and behaves when integrated into an actual course.
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