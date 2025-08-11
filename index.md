---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}

{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}

[syllabus]: syllabus
[piazza]: https://piazza.com/ucsd/summer2025/dsc80
[gradescope]: https://www.gradescope.com/courses/1076838
[github]: https://github.com/dsc-courses/dsc80-2025-su
[welcome-survey]: https://docs.google.com/forms/d/e/1FAIpQLSdSi6UdyjUcaQ_-iA2M39w8gwftuYgedtDHC1ViIZZ1M9y4Mw/viewform?usp=sf_link
[extension-request-form]: https://docs.google.com/forms/d/e/1FAIpQLSd1F7vvNy00Yvk-bKnt-ZdRsObkI8grQ6rw-AAeAryeX2p3AA/viewform?usp=sf_link
[exam-accommodations]: https://docs.google.com/forms/d/e/1FAIpQLSd7Im23x9HcF9ok-rm1Bq8kI0WPl9735sgFeSgZJAji4gdrTQ/viewform?usp=sf_link
[Lecture-Recordings]:https://docs.google.com/document/d/1k1rF-zdeNSJ9y5eo8YFTfJ8muiFdOfXY7v0_9pfUFA4/edit?usp=sharing)
[OfficeHours]:https://docs.google.com/document/d/1OIFXoQ4ADIzyk1EZSZz6izD7A7Cngxu4CnUVcYzOQ6Q/edit?usp=sharing

<!-- [Jump to the current week](#week-9-modeling-in-practice){: .btn } [Lab Solutions](https://edstem.org/us/courses/51951/discussion/4183397){: .btn .btn-green } -->

[Lecture Recordings][Lecture-Recordings]{: .btn }
[Welcome Survey][welcome-survey]{: .btn }
[Extension Request Form][extension-request-form]{: .btn }
[Exam Accommodations Form][exam-accommodations]{: .btn }
[Office Hours][OfficeHours]{: .btn }


<!-- [Exam Accommodations Form][exam-accommodations]{: .btn }
[Extension Request Form][extension-request-form]{: .btn } -->

<!-- Click the 🎥 button to view the recording of a lecture/discussion.<br>Click the 📝 button to view lecture notebooks after they've been filled in during lecture. -->

<!-- {: .green }
**Welcome to DSC 80! 👋 Make sure to: read the [syllabus][syllabus], check that you can access [Gradescope][gradescope] and [Ed][ed], fill out the [Welcome Survey][welcome-survey], and fill out the [Exam Accommodations Form][exam-accommodations] if you have an exam conflict.** -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
