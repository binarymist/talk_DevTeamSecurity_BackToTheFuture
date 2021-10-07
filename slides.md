<link rel="stylesheet" href="proj-css/talk.css">

<!--Cover Slide-->

<span style="font-size: 5rem; color: #9b6bcc">
  <a href="https://twitter.com/purpleteamlabs" target="_blank"><i class="fab fa-twitter"></i> purpleteamlabs</a>
  <!--<a href="https://twitter.com/OWASPPurpleTeam" target="_blank"><i class="fab fa-twitter"></i> OWASPPurpleTeam</a>-->
</span>

----  ----

# Past

### Definitions <!-- .element: style="text-align:left" -->

Two people types involved: <!-- .element: style="text-align:left" -->

1. Mainstream (less technical & Devs)
2. Creating security info & tooling for category 1

Note:
2 people types or target audiences involved

1. Mainstream category targeting less technical folks and most Devs (those consuming what category 2 create)
2. Those creating the security information and tooling for category 1

----

<!-- .slide: style="text-align:left" -->

## Doc and Standards

#### OWASP

* <!-- .element: style="font-size: 2rem;" --> Application Security Verification Standard (<a href="proj-media/OWASPApplicationSecurityVerificationStandard4.0.2-en.pdf" target="_blank">ASVS</a>)
* <!-- .element: style="font-size: 2rem;" --> Software Assurance Maturity Model (<a href="proj-media/OWASP-SAMM-v2.0.pdf" target="_blank">SAMM</a>)
* <!-- .element: style="font-size: 2rem;" --> Software Component Verification Standard (<a href="proj-media/OWASP_SCVS-1.0-en.pdf" target="_blank">SCVS</a>)
* <!-- .element: style="font-size: 2rem;" --> <a href="https://cheatsheetseries.owasp.org/" target="_blank">~75 Cheat Sheets</a>
* <!-- .element: style="font-size: 2rem;" --> Varius Top 10 lists
* <!-- .element: style="font-size: 2rem;" --> Quite a few others

&nbsp;<!-- .element: style="font-size: 1rem;" --> 

#### Others

* <!-- .element: style="font-size: 2rem;" --> SANS <a href="https://www.sans.org/top25-software-errors/" target="_blank">Top 25</a>
* <!-- .element: style="font-size: 2rem;" --> Mitre <a href="https://cwe.mitre.org/top25/archive/2021/2021_cwe_top25.html" target="_blank">Top 25</a>
* <!-- .element: style="font-size: 2rem;" --> CIS Controls
* <!-- .element: style="font-size: 2rem;" --> others

Note:
How did we used to measure the security maturity of the software that our Dev Teams produced?

Discuss the points.

Lot's of docs to read, standards to attempt to adhere to.

Confusing

So much to learn before you could even get started.

So much manual testing and verification work

These standards are not prescriptive enough, they don't really provide metrics to measure, or if they do, there are far too many.<br>
Provide very long lists of check boxes for technical people to work through manually.

----

## Tooling

Mostly manual

Note:

A lot of manual work

Sure we had tools, but we mostly drove them manually

----  ----

# Present

----

<!-- .slide: style="text-align:left" -->

## Doc and Standards

<span class="fragment">New commer:</span><span class="fragment"> . </span><span class="fragment">. </span><span class="fragment">. <br>
<a href="https://www.nist.gov/itl/executive-order-improving-nations-cybersecurity/recommended-minimum-standard-vendor-or-developer" target="_blank">NIST Recommended Minimum Standard for Vendor or Developer Verification of Code</a></span> <!-- .element: class="fragment fade-right" -->

<a href="proj-media/DeveloperVerificationOfSoftware.pdf" target="_blank">Accompanying Doc</a></span> <!-- .element: class="fragment fade-right" -->

Note:
Many of us are still trying to hold on to the past (left arrow to the past then back again), or at least don't yet understand that there is a better way.

1. There have been significant improvements in the information and tooling available recently
2. Some new standards are emerging and starting to reflect this also
3. Security documentation and tooling is starting to grow up.
4. Discus new NIST almost standard.  
  NIST is trying to make a smaller, simpler, more achievable standard that can also be understood by non tech types.<br>
  It's prescriptive, less intimidating, measurable and concise.<br>
  Not technically a standard yet
5. Discuss accompanying doc

The new NIST (almost standard) lends itself very well to being automated, and it's no accident.

----

## Tooling

<a href="https://docs.google.com/spreadsheets/d/13H-to0QP4r2WFC5kEH6ZiinO2xvnVyyrZ8bVIIX6XaU/" target="_blank">
  <span style="font-weight: 900; color: #9b6bcc">></span>
  <span class="fragment">a</span><span class="fragment">u</span><span class="fragment">t</span><span class="fragment">o</span><span class="fragment">m</span><span class="fragment">a</span><span class="fragment">t</span><span class="fragment">e</span><span class="fragment">d</span><span class="fragment"> </span><span class="fragment">s</span><span class="fragment">t</span><span class="fragment">a</span><span class="fragment">n</span><span class="fragment">d</span><span class="fragment">a</span><span class="fragment">r</span><span class="fragment">d</span><span class="fragment">s</span>
</a>





Note:
I've taken the table from the new NIST standard and extended it to include a tools column.

---

Besides the:

* Threat modeling material
* Evil Test Conditions
* The fuzzing tools

The rest of these tools lend themselves very well to being automated and added to your editors, IDEs & build pipelines.

We now have tooling that automatically does most of what we used to do manually...<br>
Our tooling is maturing.

----  ----

# Future

----

<!-- .element: data-background-image="proj-img/future0.jpg" data-background-opacity="0.3" -->

----

<!-- .element: data-background-image="proj-img/future1.jpg" data-background-opacity="0.3" -->

----

<!-- .element: data-background-image="proj-img/future2.jpg" data-background-opacity="1" -->

----

Two people types involved: <!-- .element: style="text-align:left" -->

1. Mainstream (less technical & Devs)
2. Creating security info & tooling for category 1






Note:
I believe for type 1 People... where we're going is a mix of the NIST type standard with most of the detail being taken care of by automated tooling.

This is all part of infosec commoditisation.

As Developers you can expect to see the level of technical detail lifting so as to focus on more abstract topics and activities. Such as verification as opposed to hands-on testing.

Standards will continue to become higher level, and the tool-chains will continue to support.

----

<!-- .slide: style="text-align:left" -->

Runtime Application Self Protection (RASP)

* <!-- .element: class="fragment fade-right" data-fragment-index="1" --> <a href="https://docs.sqreen.com/guides/how-sqreen-works-in-depth/" target="_blank">Sqreen</a>
* <!-- .element: class="fragment fade-right" data-fragment-index="2" --> hdiv
* <!-- .element: class="fragment fade-right" data-fragment-index="2" --> others..


Note:
With the new Runtime Application Self Protection (RASP) type tooling such as:

* Sqreen
* hdiv
* others..

Your applications can now defend themselves

Sqreen has a microagent which becomes a lib dependency of your app code.

----

<span style="font-size: 5rem; color: #9b6bcc">
  <a href="https://twitter.com/purpleteamlabs" target="_blank"><i class="fab fa-twitter"></i> purpleteamlabs</a>
  <!--<a href="https://twitter.com/OWASPPurpleTeam" target="_blank"><i class="fab fa-twitter"></i> OWASPPurpleTeam</a>-->
</span>

