.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introductiont to reStructuredText see:
.. 
.. https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
.. 
.. Lines like this which start with `.. ` are comments which won't appear
.. in the generated output.
.. 
.. To apply for a GSoC project with Xapian, please fill in the template below.
.. Placeholder text for where you're expected to write something says "FILLME"
.. - search for this in the generated PDF to check you haven't missed anything.
.. 
.. See our GSoC Project Ideas List for some suggested project ideas:
.. https://trac.xapian.org/wiki/GSoCProjectIdeas
..
.. You are also most welcome to propose a project based on your own ideas.
.. 
.. From experience the best proposals are ones that are discussed with us and
.. improved in response to feedback.  You can share draft applications with
.. us by forking the git repository containing this file, filling in where
.. it says "FILLME", committing your changes and pushing them to your fork,
.. then opening a pull request to request us to review your draft proposal.
.. You can do this even before applications officially open.
.. 
.. IMPORTANT: Your application is only valid is you upload a PDF of your
.. proposal to the GSoC website at https://summerofcode.withgoogle.com/ - you
.. can generate a PDF of this proposal using "make pdf".  You can update the
.. PDF proposal right up to the deadline by just uploading a new file, so don't
.. leave it until the last minute to upload a version.  The deadline is
.. strictly enforced by Google, with no exceptions no matter how creative your
.. excuse.
.. 
.. If there is additional information which we haven't explicitly asked for
.. which you think is relevant, feel free to include it. For instance, since
.. work on Xapian often draws on academic research, it's important to cite
.. suitable references both to support any position you take (such as
.. 'algorithm X is considered to perform better than algorithm Y') and to show
.. which ideas underpin your project, and how you've had to develop them
.. further to make them practical for Xapian.
.. 
.. You're welcome to include diagrams or other images if you think they're
.. helpful - for how to do this see:
.. https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html#images
.. 
.. Please take care to address all relevant questions - attention to detail
.. is important when working with computers!
.. 
.. If you have any questions, feel free to come and chat with us on IRC, or
.. send a mail to the mailing lists.  To answer a very common question, it's
.. the mentors who between them decide which proposals to accept - Google just
.. tell us HOW MANY we can accept (and they tell us that AFTER student
.. applications close).
.. 
.. Here are some useful resources if you want some tips on putting together a
.. good application:
.. 
.. "Writing a Proposal" from the GSoC Student Guide:
.. https://google.github.io/gsocguides/student/writing-a-proposal
.. 
.. "How to write a kick-ass proposal for Google Summer of Code":
.. https://teom.wordpress.com/2012/03/01/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/

============================
Speed up Xapian's Test Suite
============================

About You
=========

 * Name: Tanmay Sachan

 * E-mail address: tanmay.sachan@research.iiit.ac.in, tnmysachan@gmail.com

 * IRC nickname(s): Tanmay

 * Any personal websites, blogs, social media, etc: https://www.facebook.com/tanmaysch, https://tanmaysachan.github.io

 * github URL: https://github.com/tanmaysachan

 * Biography:

.. Tell us a bit about yourself.

I'm a freshman at IIIT-Hyderabad, and my major is Computer Science and Engineering. I love solving
problems and learning new things. My current interests are linux, compilers and exploring how they
work. I like to play basketball occasionally and my favourite computer scientist is Edsger W. Dijkstra.

"Perfecting oneself is as much unlearning as it is learning." - Dijkstra

Background Information
----------------------

.. The answers to these questions help us understand you better, so that we can
.. help ensure you have an appropriately scoped project and match you up with a
.. suitable mentor or mentors.  So please be honest - it's OK if you don't have
.. much experience, but it's a problem if we aren't aware of that and propose
.. an overly ambitious project.

**Have you taken part in GSoC and/or GCI (https://codein.withgoogle.com/) and/or
similar programmes before?  If so, tell us about how it went, and any areas you
would have liked more help with.**

No, this is my first time taking part in GSOC, and I've not participated in GCI.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I currently have 2 merged PRs in Xapian and 1 open.

Merged:

- https://github.com/xapian/xapian/pull/219
- https://github.com/xapian/xapian/pull/222

Open:

- https://github.com/xapian/xapian/pull/223

Other than that, I have no prior experience with indexed text search systems.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I have contributed to other small open source projects for fun, but nothing as serious as Xapian.
As for using them, my current daily driver is Ubuntu, on which I frequently use Vim, Libre Office,
Firefox, etc. Most of the software I use on a daily basis is open source.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

Relevant courses taken at college include Computer systems organisation, Software Systems, Data
Structures and Algorithms, Discrete Structures.

Other than that, in 2017 and 2018, I was selected among the top 30 school students in India for
training in computer science for International Olympiad in Informatics, where I mainly studied
advanced data structures and algorithms and worked primarily with C++.

Again in 2018, I was selected for ACM-ICPC Amritapuri regionals, as a freshman in college.

I have worked extensively in python using libraries and frameworks like numpy, scipy, keras, pytorch, opencv, django,
etc.

I also have prior experience with Bash, as I've used it frequently to write scripts to automate
tasks, and for my college assignments.

My main hobby is coding, and I love to learn new things.

**What development platforms, tools and methods do you prefer to use?**

I primarily use Vim as my text editor, and CLion(C/C++)/PyCharm(Python) for navigating through the code. My primary version
control system is Git. I use Ubuntu 18.04 as my OS.

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

Right now, I'm working on improving the condition of Vlabs, an initiative by the
Government of India to improve the teaching of Computer Science across low tier engineering
colleges in India.

**What timezone will you be in during the coding period?**

IST (UTC + 05:30).

**Will your Summer of Code project be the main focus of your time during the
program?**

Yes. GSoC will be my main focus this summer.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

Monday-Friday 4:30 AM - 3:30 PM UTC.
Equivalent to Monday-Friday 10:00 AM - 8:00 PM IST.

Since I will mostly be free this summer, these timings are flexible, and I would be able to devote
even more time to the project if need be.

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

This project will help be become a better programmer, and improve my experience with C++. I'll get
to learn more about how complex software is built and how it functions.

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

All the developers of Xapian will benefit from this project. Right now, devs spend a lot of time
trying to run tests on Xapian, or they try to speed it up by disabling Valgrind, which can cause
problems. This project aims to improve the speed of the test suite, so that less time will be wasted
running tests.

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

We know that splitting up the tests into different backends and using automake's parallel test
harness causes a decent speedup in the runtime of tests, as demonstrated by
https://github.com/xapian/xapian/pull/210. Taking full advantage of the parallelisation should speed
up the tests even further.

Current plans for the project:

1) Implement a basic scheduler for tests.

In this part, I will implement a simple scheduler which breaks apart the test cases in groups and
runs them in parallel by separating them into multiple processes. The collate-test script gathers the testcases and runs them according to each
condition. I will be modifying that script to run the tests in processes by the grouping that
already exists.
After successful completion of this basic scheduler, I will be implementing a Scheduler class, with
better scheduling, which will be receiving test cases from api_collated.h file, analyzing(by test
run times) them and then grouping them.

2) Handling the results with parallel tests.

I will be making the harness output the results in TAP format. While collecting the results, we can
keep track of failed results to provide a better summary of failed testcases.

3) Implement a time tracker for testcases.

In this part, I will implement a time tracker for testcases, which will report the time taken by
each testcase to run.
Another part would be checking out the slow testcases, and analyzing them for potential speed
improvements.
This timer can be implementing using a simple chrono clock inside the run_tests function, which will
record how long each test execution takes.

4) Fixing testcases which require multiple backends.

Certain testcases which make use of multiple backends (using BackendManagerLocal) need to rewritten.
BackendManagerLocal needs to be removed, and the harness should support using multiple backends.
I will be implementing a new harness backend which would use a local shard and remote shard
together, and so if anyone wants to write a new test case which makes use of both, they will be able
to do so via the condition set in DEFINE_TESTCASE.

If all goes smoothly, and my work is finished before the completion of summer, I would like to work
on "Python bindings improvements" and "Performance test suite".

I will start off by getting familiar with the relevant section of the codebase for the stretch goals during the
community bonding period, and discuss with the mentors about the specific implementation details.

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

Guruhegde's pull request https://github.com/xapian/xapian/pull/210 tells us that just by seperating
the tests into different backends, and running them parallely using automake's parallel test
harness causes a speed increase from 15 minutes to 9 minutes.

**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**

No other approach considered.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

None so far.

**How useful will your results be when not everything works out exactly as
planned?**

The test suite will experience an improvement regardless of the full project completion. The project is
broken into pieces, each of which is somewhat of an attempt to improve and speed up the testsuite.

Project Timeline
----------------

.. We want you to think about the order you will work on your project, and
.. how long you think each part will take.  The parts should be AT MOST a
.. week long, or else you won't be able to realistically judge how long
.. they might take.  Even a week is too long really.  Try to break larger
.. tasks down into sub-tasks.
.. 
.. The timeline helps both you and us to know what you should do next, and how
.. on track you are.  Your plan certainly isn't set in stone - as you work on
.. your project, it may become clear that it is better to work on aspects in a
.. different order, or you may some things take longer than expected, and the
.. scope of the project may need to be adjusted.  If you think that's the
.. case during the project, it's better to talk to us about it sooner rather
.. than later.
.. 
.. You should strive to break your project down into a series of stages each of
.. which is in turn divided into the implementation, testing, and documenting of
.. a part of your project. What we're ideally looking for is for each stage to
.. be completed and merged in turn, so that it can be included in a future
.. release of Xapian. Even if you don't manage to achieve everything you
.. planned to, the stages you do complete are more likely to be useful if
.. you've structured your project that way. It also allows us to reliably
.. determine your progress, and should be more satisfying for you - you'll be
.. able to see that you've achieved something useful much sooner!
.. 
.. Look at the dates in the timeline:
.. https://summerofcode.withgoogle.com/how-it-works/
.. 
.. There are about 3 weeks of "community bonding" after accepted students are
.. announced.  During this time you should aim to complete any further research
.. or other issues which need to be done before you can start coding, and to
.. continue to get familiar with the code you'll be working on.  Your mentors
.. are there to help you with this.  We realise that many students have classes
.. and/or exams in this time, so we certainly aren't expecting full time work
.. on your project, but you should aim to complete preliminary work such that
.. you can actually start coding at the start of the coding period.
.. 
.. The coding period is broken into three blocks of about 4 weeks each, with
.. an evaluation after each block.  The evaluations are to help keep you on
.. track, and consist of brief evaluation forms sent to GSoC by both the
.. student and the mentor, and a chance to explicitly review how your project
.. is going with Xapian mentors.
.. 
.. If you will have other commitments during the project time (for example,
.. any university classes or exams, vacations, etc), make sure you include them
.. in your project timeline.

April 9 - May 6:

- Get https://github.com/xapian/xapian/pull/223 merged.
- Work on other small issues.

I will be having my end semester exams around this time, so I wouldn't be able to contribute a lot
to Xapian.

Community Bonding Period: May 6 - May 27

- Understand the codebase better.
- Discuss about stretch goals.
- Start discussing the implementation of stretch goals.
- Do pending research, if any.

Week 1: May 27 - Jun 3

- Implement a new harness backend, remove BackendManagerLocal altogether.

Week 2: Jun 3 - Jun 10

- Fix testcases which regenerate Databases each time, slowing down performance.

Week 3: Jun 10 - Jun 17

- Implement timer to analyze testcase run times.
- Discuss about slow testcases, and ways to improve their performance.

Week 4: Jun 17 - Jun 24

- Continue improving the testcases.
- Implement "slow" tags for testcases which are slow and can't be sped up.

Phase 1 evaluation

Week 5: Jun 24 - Jul 1

- Start implementing a basic scheduler which seperates the harness backends.

Week 6: Jul 1 - Jul 8

- Finish implementing the scheduler.
- Handle errors if any.
- Test the scheduler thoroughly.

Week 7: Jul 8 - Jul 15

- Handle the results and output from the process, and output them in TAP format.
- While combining results, keep track of failed testcases and report a summary.

Week 8: Jul 15 - Jul 22

- Buffer week for pending work.
- Write and/or improve documentation if any.

Phase 2 evaluation

Week 9: Jul 22 - Jul 29

- Implement a proper scheduler class which analyzes testcases by their tags, and chunks them up appropriately.

Week 10: Jul 29 - Aug 5

- Continue working on the scheduler.
- If finished, test it thoroughly and handle errors.

Week 11: Aug 5 - Aug 12

- Buffer week for pending work.
- Write and/or improve documentation if any.

Week 12: Aug 12 - Aug 19

- Start working on stretch goals.
- Write a PyPI package of python bindings for xapian (Stretch goal).

Week 13: Aug 19 - Aug 26

- Work on adding better real world data to Xapian performance tests (Stretch goal).

Final evaluation

If all goes well, I would be completing my main project much quicker than proposed above.
I will be spending the rest of the time working on the Stretch goals.

Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

Discussed on IRC under the nick "Tanmay".

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

Yes, I agree to dual licence all my contributions under the GNU GPL version 2 and all later
versions, and the MIT/X licence.

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1399

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

No such use planned at the moment for the main project.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
