# WeBWorK_reading_questions_Beezer_LA
WeBWorK reading questions for [A First Course in Linear Algebra](http://linear.ups.edu/index.html) by Robert A. Beezer.

## Description

These are WeBWorK reading questions for the free textbook [A First Course in Linear Algebra](http://linear.ups.edu/index.html) by Robert A. Beezer. They are meant to be assigned before the material is covered in class, to encourage students to read the book.

The problems are in the ``templates`` directory, in a directory named after the corresponding section in Beezer's book. However, WeBWorK does not appear to like one-character directory names; hence, the folders ``Bases``, ``Dimension``, ``Orth``, and ``Subspaces`` for Sections [B](http://linear.ups.edu/html/section-B.html), [D](http://linear.ups.edu/html/section-D.html]), [O](http://linear.ups.edu/html/section-O.html), and [S](http://linear.ups.edu/html/section-S.html), respectively.

There are two main types of problems:

* The files with names of the form ``basic_read_X.pg`` (where ``X`` is the section) are multiple-choice questions determined to gauge basic comprehension of the section. These were authored by Christopher Phan.

* The files with names of the form ``X-rq-n.pg`` (where ``X`` is the section and ``n`` is a positive integer) are the nth open-response reading question provided in Beezer's book. While Christopher Phan coded these problems to WeBWorK, authorship credit goes to Robert A. Beezer.

In either case, content from Beezer's book is used under the GNU Free Documentation License.

Finally, there is a file ``templates\generic\generic_understading.pg``, which is a generic open-response question, inviting the student to either explain what they found difficult to understand or what they enjoyed most about the material, which may be included at the end of each reading assignment.

## Easy installation directions

If you don't have command-line server access to your WeBWorK server, it is still straightforward to install these problems.

1. Download the [tarball of this repository from GitHub](https://github.com/christopherphan/WeBWorK_reading_questions_Beezer_LA/archive/master.tar.gz).

2. In the WeBWorK file manager, navigate to your course's root directory (the parent directory of ``templates``).

3. Enable the options "Overwrite existing files silently",
"Unpack archives automatically" and "then delete them".

4. Upload the tarball.

## Important installation directions

In order to use these files, you must upload

## Copyright and authorship information
