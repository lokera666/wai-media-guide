---
title: "Changelog"
nav_title: "Changelog"

lang: en
last_updated: 2020-11-24

permalink: /media/av/changelog/
ref: /media/av/changelog/   # Do not change
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/changelog.md'

resource:
  title: "Making Audio and Video Media Accessible"
  ref: /media/av/
navigation:

---

## 2020-November-24

* Include text in description
  * In Audio Description of Visual Information page, under [Tips for Writing Descriptions](https://www.w3.org/WAI/media/av/description/#writing), added paragraph:<br>"Generally, all text in the video should be included in the main audio (integrated description) or in the separate description. For example, title text at the beginning of the video, links and e-mail addresses shown at the end, speakers’ names in text, and text in a presentation. The text does not have to be included verbatim (exactly word-for-word), yet all of the information conveyed by the text needs to be available in the main audio, in the separate description, or clearly with the video."
  * In first page, under [How to Make Audio and Video Accessible](https://www.w3.org/WAI/media/av/#how-to-make-audio-and-video-accessible), at end of Audio Description of Visual Information paragraph, added:<br>", including text displayed in the video."
  * In Audio Content and Video Content page, under [Plan for audio description of visual information](https://www.w3.org/WAI/media/av/av-content/#plan-description), at end of first paragraph, added:<br>", **including text displayed in the video**."
  * ([Diff for text in description](https://github.com/w3c/wai-media-guide/pull/126/files))
* bring up common barriers in content
  * In [Audio Content and Video Content page](https://www.w3.org/WAI/media/av/av-content/)
    * Added to summary:<br>"This page covers **common accessibility barriers** including:...<br>{and 3 bullets with in-page links}"
    * Moved paragraph: "Guidance on what to include is in the "Creating Audio Description of Visual Information" page, [Tips for Writing Description section](/media/av/description/#writing)."
    * Added "script" to "### Plan for sign language – _storyboarding, script, recording_ (WCAG AAA)"
      * Added targets:
      * "### Provide redundancy for sensory characteristics – _script_ (WCAG A)  {#sensory}"
      * "### Make overlay text readable – _storyboarding, post-production_ (WCAG AA, AAA) {#readable}"
    * Corrected grammar have->has:<br>"Some of the guidance below is related to requirements in Web Content Accessibility Guidelines (WCAG) and have links to a separate resource." -><br>"Some of the guidance below is related to requirements in Web Content Accessibility Guidelines (WCAG) and has links to a separate resource."
  * ([Diff 2020-November-24 AV Content](https://github.com/w3c/wai-media-guide/pull/127/files))
* add alt
  * In [Captions/Subtitles](https://www.w3.org/WAI/media/av/captions/) and [Transcribing Audio to Text](https://www.w3.org/WAI/media/av/transcribing/) added alt "food on fire under broiler" to:<br><code>{% include image.html src="food-fire.jpg" alt="food on fire under broiler" class="normal right" %}</code>

## 2020-October-09

* In Transcripts page, [Does My Media Need a Transcript? section](https://www.w3.org/WAI/media/av/transcripts/#checklist), corrected bullets under "Video-only (no audio content)"
* ([Diff 2020-October-09](https://github.com/w3c/wai-media-guide/pull/128/files))

## 2020-October-01

* In [Audio Content and Video Content page](https://www.w3.org/WAI/media/av/av-content/), added missing WCAG to:
   * Plan for sign language – _storyboarding, recording_ (WCAG AAA)
   * Plan for audio description of visual information – _storyboarding, recording_  (WCAG A, AA)
* ([Diff 2020-October-01](https://github.com/w3c/wai-media-guide/commit/77727ef8d05f3fee95b6150164d837465cb8cb8c))

## 2020-September-12

* In [Captions page](https://www.w3.org/WAI/media/av/captions/#captions-and-subtitles), corrected: "Subtitles/interlingual subtitles are usually only the spoken audio (for people who can hear the audio but do not know the spoken language)."
* In [Planning Audio and Video Media](https://www.w3.org/WAI/media/av/planning/), corrected "(called subtitles or interlingual subtitles)"

## 2019-November-18

Clarified and corrected WCAG requirements in:
* [Checklists for Audio and Video section](/media/av/planning/#checklist) of Planning Audio and Video Media page 
* Tables in [WCAG Standard section](/media/av/planning/#wcag-standard) of Planning Audio and Video Media page 
* [Does My Media Need Captions? section](/media/av/captions/#checklist) of Captions/Subtitles page
* [Does My Media Need a Transcript? section](/media/av/transcripts/#checklist) of Transcripts page