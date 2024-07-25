---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---

{% include base_path %}

## HKU Course Notes
Here collects my personal notes for some HKU courses (mainly actuarial science
courses). Note that they are unofficial and may not completely match with the
syllabus.

Feel free to contact me if you have any questions/comments.

* STAT2902 Financial mathematics ([syllabus](https://webapp.science.hku.hk/sr4/servlet/enquiry?Type=Course&course_code=STAT2902))
   * study notes (under construction)
   * [GitHub repository](https://github.com/leochiukl/HKU-STAT2902-notes)
   * related SOA exam: [FM](https://www.soa.org/education/exam-req/edu-exam-fm-detail.aspx)
* STAT3901 Life contingencies I ([syllabus](https://webapp.science.hku.hk/sr4/servlet/enquiry?Type=Course&course_code=STAT3901))
   * [study notes (pdf)](/files/stat3901-study-notes.pdf)
   * [GitHub repository](https://github.com/leochiukl/HKU-STAT3901-notes)
   * related SOA exam: [FAM](https://www.soa.org/education/exam-req/edu-exam-fam/) (long-term)
* STAT3905 Introduction to financial derivatives ([syllabus](https://webapp.science.hku.hk/sr4/servlet/enquiry?Type=Course&course_code=STAT3905))
   * [study notes (pdf)](/files/stat3905-study-notes.pdf)
   * [GitHub repository](https://github.com/leochiukl/HKU-STAT3905-notes)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
