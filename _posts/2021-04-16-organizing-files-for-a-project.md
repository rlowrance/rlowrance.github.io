---
layout: post
categories: person_productivity
title: "How I Organize Files for a Project"
---

I work on many project concurrently, each collecting
files. My projects are of all kinds: some are developing business
ideas, some are developing software, some are short-lived and some
seem to go on and on. When I switch from one project to another, I
need to quickly orient myself to the files in the project. To assist
in doing that, I organize project-related folders in a uniform
way. This organization structure has served for all kinds of
projects. It is simply to setup and use. This note explains the structure.

A project is typically defined as a coherent set of tasks that has a
beginning and ending date. Often, the project has deliverables and
when they are delivered, the project ends. Let's use that definition
for a while.

When I start a project, I create a folder for that project. I give it
an appropriate name. Where the project folders go will be the subject
of another post, but for now, you can assume that I have a folder
called "Projects" that contains all of the project folders.

Each project folder has within it at its top level three
folders: one call "work", another called "output", and a third called
"input." Typically there are no other top-level folders in a project
folder.

In the remainder of this post, I'll describe those subfolders. A project
folder might contains a few top-level files, and I'll describe those
next. Then comes a summary of the structure of a project folder, some
notes on how to use the project folders, and a discussion of prior work.

# The work folder

The "work" folder contains everything that I created or co-created. If I'm
working with a team, it contains everything the team created. If you
are thinking of citing literature, I am the author or a co-author or
team mate of the author of everything in the work folder. Examples of
files would include drafts of documents, final versions of documents,
spreadsheets that I'm working on or have finished, and other types of
documents.

Sometimes the work folder contains other folders. These folders might
be around the phases of a project or some other logical structure. If
I'm writing code, there is usually a "src" folder containing the
source code. The src folder is usually managed by a version control
application.

# The output folder

I want to keep track of everything I've shown external parties so that
I will know exactly what others have seen and when they saw it. That's
the purpose of the "output" folder . It contains a set of folders
named with the the date I transmitted material to someone else and the
name of the party that received the material. For example, a folder
named "output/2021-04-01 bob smith" contains documents I sent to Bob
Smith on April 1, 2021. I write the date in YYYY-MM-DD format so that
the folders in "output" sort by date sent.

Each folder contains whatever was transmitted. When I'm being careful,
the transmital document itself is in the folder. A typical transmital
document is the email used send the document. If I send to someone
more than once in a day, I append "a", "b", and so forth to the day
number. The output folder typically gets built early in a project's
life, because it contains documents describing the project and those
are most certainly sent to the client.

# The input folder

Usually there is an "input" folder as well. It contains material for
which neither I nor my team mates are the authors. Examples would be
analysis from other parties and data sets from others. My practice is to lock
the files in this folder so that I know that I did not modify
them. There is a folder for each source, which is often a person, but
sometimes an organization. The name of the folder is the name of the
person or organization.

Usually the document has the same name as the source used, so that I
can find the document when the source describes it. Some
documents--like webpages--don't have names. When that happens, I create
a name, typically starting with the last name of the primary
author, then a hyphen, then the year the document was published, and
finally either the author's title or an abbreviation of the title. So the
contents of the webpage "My Great Insights" written by John Smith in
2013, would be in the file "smith-2013 my great insights.txt".

# Other objects at the top level in a project folder

Sometimes I have projects that are related to each other. For example,
I create a project for each workshop and speech that I give. These
projects are closedly related to each other. For example, a workshop
is typically similar to a previous workshop. To keep track of the
related projects, at the top level in each project's folder, I place
an alias file to each of the previous related projects. Sometimes, in
the prior project's folders I put an alias to the new project.

# Summary

Let's summarize. If I have a project called say "marketing-plan" there
will be a folder for it. Inside that folder will be a work folder,
containing documents that I or my team have authored, an output folder
with a copy of whatever was sent to people outside the team, and an
input folder containing documents and data sets authored by others. No
other folders are at the top level in the project folder.

In addition to the subfolders, at the top level of the project folder
I place alias files for related projects. 

# Using the project folders

I use a loose definition of a project: some of my projects will run
for years and for some, I am among the clients. For example, I have a
home financial management project that will not end for a long time--
at least that's my plan. It contains an input folder containing
financial statements and bills and so forth, a work folder containing
the files my accounting system uses as well as various spreadsheets I
use to keep track of things, and an output folder for material I've
sent to others.

Sometimes a project contains subprojects. I put the project
folders for subprojects in the "work" folder of the main project.

The project folder can be shared when you are working with a
team. Share this note with team members as an aid to getting everyone
to organize that shared folder consistently. If you are following my
practice, create an input folder with the name "lowrance" and within
in, a webloc file named, perhaps, "lowrance-2021 folder organization.webloc".

# Prior work

Many others have written about organizing files for projects. Their
ideas typically apply to our "work" folder. The approach suggested
here often is more clearly focused on separating input, output, and
work.

Recent suggestions for organizing project folders are in part driven
by the need for reproducability. All those ideas apply to our
suggested "work" folder.

A notable example of organizing for reproducability is from Noble
(2009). He suggests these folders that would be in our work folder:
doc (containing documents, including papers), data (he segregates the
raw data from data the project generated), src (the source code), bin
(when working with some programming languages, a compiled version of
the source code is needed and those compiled versions go into bin),
and results (the results of running the programs). Noble's system is
compatible with our suggestions, with the exception that our approach
considers who provided the raw data. If it came from outside the
project, its in our "input" folder in a subfolder that identifies the
source of the data, not in our "work/data" folder.

In another post, I'll explain how I organize all the folders on my systems.

# Works CIted

William Stafford Noble. "A Quick Guide to Organizing Computational
Biology Projects." PLoS Comput Biol 5(7):
e1000424, 2009. doi.org/10.1371.journal.pcbi.1000424, published 2009-07-31. Accessed 2021-04-15.

