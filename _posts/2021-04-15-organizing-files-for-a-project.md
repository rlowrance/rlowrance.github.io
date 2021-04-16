---
layout: post
categories: person_productivity
title: "How To Organize Files for a Project"
---

I work typically on many project concurrently, each collecting
files. My projects are of my kinds: some are developing business
ideas, some are developing software, some are short-lived and some
seem to go on and on. When I switch from one project to another, I
need to quickly orient myself to the files in the project. To assist
in doing that, I organize project-related folders in a uniform
way. This organization structure has served for all kinds of
projects. It is simply to setup and use. This note explains how.

A project is typically defined as a coherent set of tasks that has a
beginning and ending date. Often, the project has deliverables and
when they are delivered, the project ends. Let's use that definition
for a while.

When I start a project, I create a folder for that project. I give it
an appropriate name. Where the project folders go will be the subject
of another post, but for now, you can assume that I have a folder
called "Active Projects" that contains all the active projects.

Each project folder has within it at its top level three
folders: one call "work", another called "output", and a third called
"input." Typically there are no other top-level folders in a project folder.

The "work" folder contains everything that I created or co-created. If I'm
working with a team, it contains everything the team created. If you
are thinking of citing literature, I am the author or a co-author or
team mate of the author of everything in the work folder. Examples of
files would include drafts of documents, final versions of documents,
spreadsheets that I'm working on or have finished, and other types of
documents. Sometimes the work folder contains other folders. These
folders might be around the phases of a project or some other logical
structure. If I'm writing code, there is usually a "src" folder
containing the source code. The src folder is usually managed by a
version control system, but I don't use version control on everything
else, because I'm sharing the files and the recipients typically don't
have version control built into their workflows.

Usually the projects have a client. I want to keep track
of everything I've shown external parties. That's the purpose of the
"output" folder . It contains a set of folders that contains the dates
I transmitted material to someone else and the name of the party that
recevied the material. For example, a folder named "output/2021-04-01
bob smith" contains documents I sent to Bob Smith on April 1, 2021. I
write the date in ISO format so that the folders in "output" sort by
date sent. Each folder contains whatever was transmitted. When I'm
being careful, the transmital document itself is in the folder. A
typical transmital document is the email used send the document. If I
send to someone more than once in a day, I append "a", "b", and so
forth to the day. The output folder typically gets built just as the
project is starting, because it contains documents describing the
project and those are most certainly sent to the client.

Usually there is an "input" folder as well. It contains material for
which I and my team mates are not the authors. Examples would be
analysis from other parties and data sets from others. A good practice is to lock
the files in this folder so that you are sure you did not modify
them. This folder typically has subfolders, one for each author or
source. If multiple versions of an input document are received, I
indicate those version with either a suffix on the document file name (for
example, "marketing plan-v12") or a date on the document file name (for example,
"raw data-2021-03-15").

Let's summarize. If I have a project called say "marketing-plan" there
will be a folder for it. Inside that folder will be a work folder,
containing documents that I or my team have authored, an output folder
with a copy of whatever was sent to people outside the time, and an
input folder containing documents and data sets authored by others. No
other folders are at the top level in the project folder.

I use a loose definition of a project: some of my projects will run
for years and for some, I am among the clients. For example, I have a
home financial management project that will not end for a long time--
at least that's my plan. It contains an input folder containing
financial statements and bills and so forth, a work folder containing
the files my accounting system uses as well as various spreadsheets I
use to keep track of things, and an output folder for material I've
sent to others.

The project folder can be shared when you are working with a
team. Share this note with team members as an aid to getting everyone
to organize that shared folder consistently.

Many others have written about organizing files for projects. Their
ideas typically apply to our "work" folder. The approach suggested
here often is more clearly focused on separating input, output, and
work, as existing work is mostly about organizing the work itself, and
recent work often has the goal of increasing reproducibility.

A notable example is from Noble (2009). He suggests these folders that
would be in our work folder: doc (containing documents, including
papers), data (he segregates the raw data from data the project
generated), src (the source code), bin (when working with some
programming languages, a compiled version of the source code is needed
and those compiled versions go into bin), and results (the results of
running the programs). Noble's system is compatible with our
suggestions, with the exception that our approach considers who
provided the raw data. If it came from outside the project, its in our
"input" folder in a subfolder that identifies the source of the data,
not in our "work/data" folder.

In another post, I'll explain how I organize all the folders on my systems.

# Works CIted

William Stafford Noble. "A Quick Guide to Organizing Computational
Biology Projects." PLoS Comput Biol 5(7):
e1000424, 2009. doi.org/10.1371.journal.pcbi.1000424, published 2009-07-31. Accessed 2021-04-15.

