# Contributing

## Mentors

To be a mentor go to [GSoC homepage][GSoC]
and create a profile for you.
If you need help, please check
http://en.flossmanuals.net/melange/creating-and-editing/.

**After you create your profile,
open a [issue][issues] requesting that your username be add at [organization-team.md][OT]
or send a pull request with this change.**

### Proposal summary

**Short Version**

If you have a proposal, please create a [issue][issues] for it.

**Long Version**

If you have a proposal,

1.  copy `YYYY/ideas/skeleton.md` to `YYYY/ideas/title-of-my-proposal.md`
    where `YYYY` is the currently year
    and `title-of-my-proposal` is a sort version of the title of your proposal.
2.  add a link to `YYYY/ideas/title-of-my-proposal.md` at `YYYY/ideas-list.md`.
3.  send a pull request with the changes at `YYYY`.
4.  [create a issue](https://github.com/numfocus/gsoc/issues/new)
    where students can ask questions.

## Students

Projects proposed by mentors are listed at
our [ideas list][IL] and questions can be ask at
[our issue tracker][issues].

You are welcome to proposal a project by your own.
If this is the case, please open a issue to discuss your proposal
or send a pull request with it.

If you are going to propose your own idea you will need to find
a mentor for it. **Proposal without a mentor will not be considered.**

### Proposal draft

1.  Fork https://github.com/numfocus/gsoc

2.  Clone your fork:

    ~~~
    $ git clone https://github.com/username/gsoc2015.git
    ~~~

    where `username` is your GitHub username.

    In my case is `r-gaia-cs`, so I will use

    ~~~
    $ git clone https://github.com/r-gaia-cs/gsoc.git
    ~~~

2.  Copy `YYYY/proposals/skeleton.md` to `YYYY/proposals/your-name.md`
    where `YYYY` is the currently year, `your` is your last name, all lowercase,
    and `name` is your firts name, all lowercase.

    For example, my name is Raniere Silva so I need to
    copy `YYYY/proposals/skeleton.md` to `YYYY/proposals/silva-raniere.md`.

3.  Edit `YYYY/proposals/your-name.md` filling all sections.

    If you need you can create new sections.

    The text in a few sections are reminders for you
    when writing your proposal.

4.  Commit your changes:

    ~~~
    $ git add proposals
    $ git commit
    ~~~

5.  Update it to GitHub:

    ~~~
    $ git push origin master
    ~~~

6.  Create a pull request.

7.  Edit `YYYY/proposals/your-name.md` to address the comments.

8.  Update your pull request:

    ~~~
    $ git commit -a
    $ git push origin master
    ~~~

9.  Back to step 7.

### Final Proposal

Your final proposal need to submitted to [GSoC][]
**before March 27th 19:00 UTC**.

[GSoC]: https://www.google-melange.com/gsoc/homepage/google/gsoc2015
[IL]: 2015/ideas-list.md
[OT]: organization-team.md
[issues]: https://github.com/numfocus/gsoc/issues
