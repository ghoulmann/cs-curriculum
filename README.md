Let's collaborate, please
-------------------------

I have been looking for collaborators since August at http://badsville.ignorelist.com. I had to get moving to propose this in time for Fall 2013. Please, let's work together.

If you have git installed, you can:

* git clone git@github.com:ghoulmann/cs-curriculum.git

To work with the existing materials, you need, if I understand what I've done correctly, the following:

* Python installed
* Python-sphinx installed
* basic understanding of reStructuredText syntax.

I've never had a pull request. Not exactly sure how modifications and additions will be incorporated, but I can find out very quickly.

Unless I get feedback to the contrary
-------------------------------------
* Avoid proposing adoption of specific technologies and vendors. [when this doc refers to revision tracking, that will most likely mean git; that won't be explicit because we want the flexibility to use subversion, etc, when the problem calls for a different solution]
* GNU/Linux generic - trying to not be raspbian/debian-centric as this document takes shape. It was tough dealing with raspi-config, for example. I had to step back and think in terms of LPI objectives.
* The power to create, access, and destroy virtual machines is assumed.
* Within our lab, students have root access over systems providing services they administer. By administering production systems, they get authentic experience. [clearly they do not have admin privs where there're are privacy concerns or safety issues].

Context
-------

I'm trying to reflect what our program has turned into over the course of 5 years, and now how its radically changed since August when we started with 1 raspi per child. It is a 2 year program that many students stay in from 8-12th with the use of elective credits. Current class sizes are four students each. We'll serve up to seven per section.

When a group started working on code for submission to a real open source community, we realized the power of authentic assessment (not simply project-based). That was five years ago and rippled from our technology courses into our composition program. Something I'm struggling with is how to use Scratch as the powerful learning tool its meant to be, but to create authentic solutions for real users with it. 

I am in a nonpublic school that primarily serves urban students with diverse learning styles; many are significantly impacted in the areas of reading and writing. The seed from which I started, the CAS Computer Science Curriculum, aims the first set of objectives for seven-year olds. I've adopted those objectives with our population in mind, and with the recognition that most are in line with accomodations, modifications that are often in place. Note that these earliest objectives are consistent with reading remediation objectives and several English/Language Arts *grade level* objectives.

A recent decision by the state requires all students have a course called "Fundamentals of Technology." It covers systems, the design process, the nature of technology, etc. We're looking at how compatible that system is with our shared value in authentic learning: if we articulate this document effectively, that course could serve as 1 year of this program. Raspis are in place.

We do not have a computer applications class. We do have a computer graphics and graphic design program.

Many of the students only have access to computing systems in school; others have access with restricted or no Internet access.

Whether I'm teaching English or ISM (our name for the 2 year program I've described), the 6 productivity machines run Ubuntu LTS and a great suite of productivity software and accessibility applications that satisfies their learning styles.

We are not entirely open source: we rely on virtual machines extensively, especially for students invested in CompTIA A+ certification. We use one xenserver machine, one esxi box, and one headless virtualbox system (administered via phpvirtualbox). Students are expected to be fluent in creating, modifying, starting, stopping, configuring virtual machines using 2 of the 3 technologies.

Work in Progress
----------------
tools: python-sphinx, or pip install sphinx; also ReText is a steady rST editor - with preview mode).

1/16: 

* Feedback suggests learning objectives could be more concrete. Piloting example "artifacts of learning" in year 1.
* Beginning curriculum mapping under domains in preface.

1/15 (later): Linux+ exam objectives begin showing up, as do marks of raspberry pi specific procedure. No longer just CAS' work.

1/15 (first commit): every part of this curriculum is either reworded or verbatim from http://www.computingatschool.org.uk/index.php?id=cacfs. It is copyright 2012 by Computing at School: This work is licensed under the Creative Commons Attribution-Non Commercial license;
see http://creativecommons.org/licenses/by-nc/3.0/ for details.

To Do
------
* concrete artifacts of learning
* at collaboration and tools
* add narrative per year
* add literacy across curriculum
* add control and process input from hardware
* anchor texts
* add electronic engineering learning objectives
* add bug reporting
* add to year summary or as object of learning: effective commenting
* rewrite documentation to included technical writing curriculum objectives
* add revision tracking
* add IDE
* add OS fundamentals
* add sys admin
* read an electronic schematic diagram
* create a series circuit with DC current
* create a parallel circuit with DC current
* test a circuit
* measure resistance with ohm meter
* measure voltage with volt meter
* measure current with amp meter
* given schematic, create a circuit that senses motion, temperature, huminity, etc
* write a program that reads, processes, stores, and output data sensed from input
* use a breadboard to integrate components into circuit from schematic
* use a soldering station to integret component into circuit from schematic
