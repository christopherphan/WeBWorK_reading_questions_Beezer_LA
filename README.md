# WeBWorK_reading_questions_Beezer_LA
WeBWorK reading questions for [A First Course in Linear Algebra](http://linear.ups.edu/index.html) by Robert A. Beezer.

Christopher Phan, Ph.D., <cphan@chrisphan.com>

## Description

This repository contains WeBWorK reading questions for the GFDL-licensed textbook [A First Course in Linear Algebra](http://linear.ups.edu/index.html) by Robert A. Beezer. They are meant to be assigned before the material is covered in class, to encourage students to read the book.

The problems are in folders named after the corresponding section in Beezer's book. However, WeBWorK does not appear to like one-character folder names; hence, the folders ``Bases``, ``Dimension``, ``Orth``, and ``Subspaces`` for Sections [B](http://linear.ups.edu/html/section-B.html), [D](http://linear.ups.edu/html/section-D.html]), [O](http://linear.ups.edu/html/section-O.html), and [S](http://linear.ups.edu/html/section-S.html), respectively.

There are two main types of problems:

* The files with names of the form ``basic_read_X.pg`` (where ``X`` is the section) are multiple-choice questions determined to gauge basic comprehension of the section. These were authored by Christopher Phan.

* The files with names of the form ``X-rq-n.pg`` (where ``X`` is the section and ``n`` is a positive integer) are the nth open-response reading question provided in Beezer's book. While Christopher Phan coded these problems to WeBWorK, authorship credit and copyright interest of the text remains with Robert A. Beezer.

In either case, content from Beezer's book is used under the GNU Free Documentation License.

Finally, there is a file ``generic/generic_understading.pg``, which is a generic open-response question, inviting the student to either explain what they found difficult to understand or what they enjoyed most about the material, which may be included at the end of each reading assignment.

While we have used Beezer's book as a source of some of the reading questions and a basis of some of the others, any errors in this repository is the responsibility of Christopher Phan.

## Installation directions

If you don't have command-line server access to your WeBWorK server, it is still straightforward to install these problems.

1. Download the [tarball of this repository from GitHub](https://github.com/christopherphan/WeBWorK_reading_questions_Beezer_LA/archive/master.tar.gz).

2. In the WeBWorK file manager, navigate to your course's  ``templates`` folder.

3. Enable the options "Overwrite existing files silently",
"Unpack archives automatically", and "then delete them".

4. Upload the tarball. This will put the questions in the folder ``templates/WeBWorK_reading_questions_Beezer_LA-master``.

5. Click on the folder ``WeBWorK_reading_questions_Beezer_LA-master``, click on "Rename", and change the name to ``Beezer_RQ``.

5. Navigate to the ``html`` folder. (You have to go up one level from the ``templates`` folder.)

6. Click "New Folder", and make a new folder called ``copyright_info``.

7. Navigate to the ``templates/Beezer_RQ/copyright_info`` folder.

8. Select ``cphan_handout.css``, click "Copy", and then enter ``../../../html/copyright_info/cphan_handout.css``, and click "Copy".

9. Select ``index.html``, click "Copy", and then enter ``../../../html/copyright_info/index.html``, and click "Copy".

## Copyright and authorship information

This repository is Copyright (C) 2017 Christopher Phan, Ph.D.

Some of the reading questions in this repository are based on [*A First Course in Linear Alegbra*](http://linear.ups.edu/html/fcla.html), by Robert A. Beezer, which is used under the GNU Free Documentation License. They were written by Christopher Phan.

Some of the reading questions used in this repository have been copied directly from [*A First Course in Linear Alegbra*](http://linear.ups.edu/html/fcla.html), by Robert A. Beezer, and are used under the GNU Free Documentation License. They were converted to WeBWorK by Christopher Phan, but copyright interest in the text of these questions remains property of Prof. Beezer.

Permission is granted to copy, distribute and/or modify the contents of this repository under the terms of the GNU Free Documentation License, Version 1.2 or any later version published by the Free Software Foundation; with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.

A copy of this license is provided in the file ``LICENCE``.
