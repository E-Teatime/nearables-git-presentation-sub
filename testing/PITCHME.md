#HSLIDE

### Git(Hub)?
### Git with a touch of Hub.

<span style="color:gray">Matthew Crocco</span>
##### <span style="color:gray">With Attribution to @schacon</span>

#HSLIDE

First, some terminology!

#VSLIDE
- **Version Control**: Managing file version history. 
    - essay-1.docx, essay-2.docx, essay-3.docx, ... essay-N.docx, ...

#VSLIDE

- **Repository**: Often shortened to 'repo' colloquially, refers to the file tree on which the versioned files are found. 

#VSLIDE

- **Working Copy**: Local copy of files from a repository. 

#VSLIDE

- **Revision**: Some change in form. Eqivalent to saying "version".

#VSLIDE

- **Commit** *(verb)*: To write or merge the changes made in the working copy back to the repository.

#VSLIDE

- **Commit** *(noun)*: Refers to the revision of files created by committing.

#VSLIDE


- **Clone**: Cloning in git typically means to copy the contents and history of another repository such that
they are identical.

#HSLIDE

What is Git?

#VSLIDE

- An Open Source, Distributed, Version Control System designed to be both fast and efficient.
- But what does all of that even mean? <!-- .element: class="fragment" -->

#HSLIDE

Open Source

> denoting software for which the original source code is made freely available and may be redistributed 
> and modified.

#HSLIDE

Distributed (As in, fully distributed)

- Almost everything git does is also stored locally. <!-- .element: class="fragment" -->
- Ok sure, but still, what does that mean? <!-- .element: class="fragment" -->

#VSLIDE

*That means*

- Everything is fast. <!-- .element: class="fragment" -->
- Every 'clone' of a repository is a backup. <!-- .element: class="fragment" -->
- Offline work is easy. <!-- .element: class="fragment" -->

#HSLIDE

Git is **Immutable**

```Python
# Strings are (typically) immutable.
a = "Let's See... "

# 'b' now points to the same string as 'a'
b = a   

# Modify the string 'a' and 'b' point to directly.
a += "Gotcha!"

# A copy was made, the string was not mutated.
print(a)    # Prints "Let's See... Gotcha!"
print(b)    # Prints "Let's See... "
```

#VSLIDE

Git is **Immutable**

- Almost Never *Removes* Data 
- Which means Snapshots! Not patches! <!-- .element: class="fragment" -->

#VSLIDE

[Let's use someone's diagrams... someone who had more time than me.](https://github.com/schacon/git-presentations/blob/master/basic_git_talk/BasicGitTalk.pdf) (Slide 15)

#HSLIDE

GitHub, in it's most basic form, is *just* a service providing a server for you to store your 
git repository. All the other stuff (privacy, GitHub markdown, etc.) is just additional special
things GitHub offers.

#HSLIDE

How Do *I* Use Git?

#VSLIDE

Baby Steps. Install Git from `git-scm.com`.

#VSLIDE

Make Git and GitHub Work

nehehehehehe