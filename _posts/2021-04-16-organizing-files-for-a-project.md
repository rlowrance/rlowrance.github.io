---
layout: post
categories: person_productivity
title: "How I Organize Files for a Project"
permalink: /202104170736
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

Each project folder has within it at its top level three subfolders:
one called "work", another called "output," and a third called
"input." I usually create these folders when I create then project folder.
Typically there are no other top-level folders in a project
folder. Sometimes there are a few files at the top level of the
project folder.

The remainder of this post is organized into sections. First I
describe the three subfolders and then the optional top-level files. I
summarize the structure of project folders and then discuss how to use
them. Finally, I explain how my approach differs from the approaches
often recommended by others.

# The work folder

The "work" folder contains everything that I created or co-created. If
I'm working with a team, it contains everything the team created
during the project. If you are thinking of citing literature, I am the
author or a co-author or team mate of the author of everything in the
work folder. Examples of files would include drafts of documents,
final versions of documents, spreadsheets that I'm working on or have
finished, and other types of documents.

Sometimes the work folder contains other folders. These folders might
be around the phases of a project or some other logical structure such
as a deliverable. If I'm writing code, there is usually a "src" folder
containing the source code. The src folder content is usually managed by a
version control application.

When the project has grown complicated, I keep a project notebook file
in the top level of the work folder.

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
number, when I need to distinguish the transmitals. The output folder
typically gets its first content early in a project's life, because it
contains documents describing the project and those are most certainly
sent to the client.

# The input folder

The input folder contains work that neither I nor my project team
created. The problem is to organize it so as to be able to find
material easily. I do that by keeping track of the source of every
document and the date of the document. The file and directory names in
the input folder start with "input/SOURCE DATE".

When someone sends me files, the source is their name and the date is
the date the files were sent. All the files go into one folder. I keep
the file names that the sender used. If I get multiple transmission on
one date from someone, I append "a", "b", and so forth to the date.

When I download files from a source, I treat those files just like I
do when someone sends them to me. Thus, I create a folder and put the
files in it, using the original file names.

The exception is when I find prior literature written by someone
else. Frequently the literature is a paper or a web page. Usually I
capture the document as a PDF file. For this type of material, the
author is more important than the source, so I set SOURCE to the
lastname of the author and DATE to the publication date. Since there
is only one document, I prepend the original file name with the SOURCE
and DATE. Sometimes the original file name is not descriptive. For
example, the file name may be a DOI identifier. When that happens, I
use the title of the work.

With this scheme, the input folder has both subfolders and files. The
is a folder for each source and date the material was received. There
is a file for each paper or similar document.

A good practice is to never edit or otherwise change the documents in
the input folder. Doing so would make your process hard to
replicate. Instead, write a program that makes the changes for
you. That program would read from the project's input folder and write
to its work folder. To avoid the temptation to edit input files, you
can lock your input folder or individual files in it. How to lock
files and folders depends on your operating system. A search will tell
you how to do that.

# Other objects at the top level in a project folder

I have projects that are related to each other. For example,
I create a project for each workshop and speech that I give. These
projects are closedly related to each other. To keep track of the
related projects, at the top level in each project's folder, I place
an alias file to each of the previous related projects. Sometimes, in
the prior project's folders I put an alias to the new project.

# Summary

Let's summarize. If I have a project called say "marketing-plan" there
will be a folder for it. Inside that folder will be a work folder,
containing documents that I or my team have authored, an output folder
with a copy of whatever was sent to people outside the team, and an
input folder containing documents and data sets authored by others. No
other folders are at the top level in the project folders.

In addition to the subfolders, at the top level of the project folder
I place alias files for related projects.

The structure of a project folder looks like this:

    # alias for related projects
    project name/alias of folder for related project
    ...
	# input documents organized into sources or names of authors
	project name/input/SOURCE DATE/ORIGINAL-FILENAME
	project name/input/SOURCE DATE [ORIGINAL FILENAME | WORK TITLE]
    ...
	# output document organized by date-party sent to
    project name/output/YYYY-MM-DD NAME1/document 1
	...
	# work documents organized by deliverable or phase
	project name/work/notebook.txt
    project name/work/[DELIVERABLE | PHASE]/document 1
    ...



# Using the project folders

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
to organize that shared folder consistently. If you are following my
practices, download a link to this document, name it perhaps,
"lowrance-2021 folder organization.webloc", and put it into your
project's input folder.

I've written this note up as if all my project files are organized as
I described. But that's not true, as I have many years of project
files and this organization occured to me only a few years ago. So
there a lot of project folders for completed projects that are not
organized this way. Sometimes I restructure them when I have to refer to
material in those folders.

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
(executable files go here, including scripts), and results (the
results of running the programs and a digital project
notebook). Noble's system is compatible with our suggestions, with the
exception that our approach considers who provided the raw data. If it
came from outside the project, its in our "input" folder in a
subfolder that identifies the source of the data, not in our
"work/data" folder.

In another post, I'll explain how I organize all the folders on my systems.

# Works CIted

William Stafford Noble. "A Quick Guide to Organizing Computational
Biology Projects." PLoS Comput Biol 5(7):
e1000424, 2009. doi.org/10.1371.journal.pcbi.1000424, published 2009-07-31. Accessed 2021-04-15.

