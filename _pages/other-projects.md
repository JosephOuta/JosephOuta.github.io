---
layout: lab_custom
permalink: /other-projects/
nav: false
# id: 3
---

##### __Replication of Cao, Kleiman-Weiner & Banaji (2019)__
<img class="fig" src="/images/projects/proj-scripts.png" width="260">

While a research assistant with Prof. Mike Frank, I had the opportunity to audit his <a href = "https://explorecourses.stanford.edu/search?academicYear=20182019&filter-coursestatus-Active=on&q=PSYCH%20251%3A%20Experimental%20Methods&view=catalog#:~:text=Graduate%20laboratory%20class%20in%20experimental,the%20ethical%20conduct%20of%20research." target="_blank" rel="noopener noreferrer">Psych 251: Experimental Methods class.</a> Our final project assignment was to attempt to replicate a finding from a randomly selected paper in psychology. We had just learnt about the open science movement so this was an exciting chance to experience the notorious challenges of replication I’d heard so much about; where would I get the data and analysis scripts? Would the code be readable? How would I know it was successful? I chose two target effects from study 5 of <a  href = "https://journals.sagepub.com/doi/full/10.1177/0956797618805750" target="_blank" rel="noopener noreferrer">Cao, Kleiman-Weiner & Banaji (2019)</a>, preregistered and ran it on Amazon Mturk and analyzed the data. The replication was partially successful: the two-tailed t-test was replicated whereas only the main effects of the ANOVA were replicated. 

<a href = "https://rpubs.com/joouta/700018" target="_blank" rel="noopener noreferrer">Full replication report</a>

---
##### __Scripts to automate tedious tasks__
<img class="fig" src="/images/projects/proj-replication.png" width="260">

As a research coordinator managing the online research platform for Prof. Hyowon Gweon’s Social Learning Lab, I spend a great many hours on Google Sheets. I often work on “tedious tasks” like updating hundreds of cells many times over. Against my better instincts, I decided to automate some of my workflows using <a href = "https://developers.google.com/apps-script" target="_blank" rel="noopener noreferrer">Apps Script</a>. I was by no means a <a href = "https://xkcd.com/378/" target="_blank" rel="noopener noreferrer">\"real programmer\"</a> when I started off, but I was farily successful thanks to the altruism of random internet strangers. In this spirit of open access (and in memory of <a href = "https://xkcd.com/979/" target="_blank" rel="noopener noreferrer">DenverCoder9</a>), I hope to pay it forward by sharing the little wisdom I picked up along the way.
<ul>
    <li>search the last date you emailed a list of addresses on Gmail, save the dates to a spreadsheet, <a href = "https://github.com/JosephOuta/gmail-dates-to-google-sheets" target="_blank" rel="noopener noreferrer">here</a></li>
    <li>reduce the size of large video files in bulk, <a href = "https://github.com/JosephOuta/bulk-resize-videos" target="_blank" rel="noopener noreferrer">here</a></li>
    <li>generate personalized graphic certificates in bulk from a template and a spreadsheet with relevant data, <a href = "https://github.com/JosephOuta/pdf-certificates-from-google-sheets" target="_blank" rel="noopener noreferrer">here</a></li>
</ul>

---