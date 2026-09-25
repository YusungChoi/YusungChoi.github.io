---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: CV_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: |
    <p>cyscyb@gmail.com</p>
    <p class="profile-social-links">
      <a href="https://github.com/YusungChoi" target="_blank" rel="noopener noreferrer" aria-label="GitHub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24" fill="currentColor"><path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/></svg>
      </a>
      <a href="https://scholar.google.com/citations?user=v_qFdHIAAAAJ&amp;hl=ko" target="_blank" rel="noopener noreferrer" aria-label="Google Scholar">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24" fill="currentColor"><path d="M5.242 13.769L0 9.5 12 0l12 9.5-5.242 4.269C17.548 11.24 14.978 9.5 12 9.5c-2.977 0-5.548 1.74-6.758 4.269zM12 10a7 7 0 1 0 0 14 7 7 0 0 0 0-14z"/></svg>
      </a>
    </p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page (kept off; GitHub/Scholar are linked under the photo instead)

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am Yusung Choi, an undergraduate student in Computer Engineering at Pukyong National University.

My research interests:

- Computer Vision
- Correspondence, 3D Grounding
- VLA, VLM, Robotics Manipulation

I am currently looking for a research lab to join!

<style>
  /* add breathing room between the news list and selected publications */
  .news {
    margin-bottom: 4rem;
  }
  /* shrink the profile picture (matched by filename, since the theme's own
     layout/wrapper classes are gem-owned and not guaranteed to stay the same) */
  img[src*="CV_pic"] {
    max-width: 220px !important;
    height: auto !important;
  }
  /* GitHub / Google Scholar links placed under the profile photo */
  .profile-social-links {
    display: flex;
    gap: 0.75rem;
    margin-top: 0.5rem;
  }
  .profile-social-links a {
    color: inherit;
    display: inline-flex;
    opacity: 0.75;
    transition: opacity 0.15s ease;
  }
  .profile-social-links a:hover {
    opacity: 1;
  }
</style>
