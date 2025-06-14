# Programming

<!-- INDEX_START -->

- [Languages](#languages)
- [Expect](#expect)
- [Free Programming Courses](#free-programming-courses)
- [Testing](#testing)
- [Code Pastebin Sites](#code-pastebin-sites)
- [Big O Notation](#big-o-notation)
- [Count Lines of Code](#count-lines-of-code)
  - [cloc](#cloc)
  - [scc](#scc)
  - [Tokei](#tokei)
- [Memes](#memes)
  - [Hello World](#hello-world)
  - [Program in Tutorial vs Made Following Tutorial](#program-in-tutorial-vs-made-following-tutorial)
  - [Resolving Broken Dependencies](#resolving-broken-dependencies)
  - [Practice](#practice)
  - [Butting Head Against A Programming Problem](#butting-head-against-a-programming-problem)
  - [Documentation](#documentation)
  - [Poking the Hornets Nest](#poking-the-hornets-nest)
  - [Run It Again](#run-it-again)
  - [Like Coding, Good at Math](#like-coding-good-at-math)
  - [Software Development Process](#software-development-process)
  - [Coding in Depth](#coding-in-depth)
  - [Pretending You Know Every Programming Language](#pretending-you-know-every-programming-language)
  - [Are You Really Sure You Want to be a Software Developer??](#are-you-really-sure-you-want-to-be-a-software-developer)
  - [Coding with GPT](#coding-with-gpt)
  - [Senior Devs Fixing Bugs in Production](#senior-devs-fixing-bugs-in-production)
  - [Theory vs Practice](#theory-vs-practice)
  - [Concurrent Programming](#concurrent-programming)
  - [Meme Driven Development](#meme-driven-development)
  - [OverEngineering Simple Solutions](#overengineering-simple-solutions)
  - [Hating on Languages You Don't Use](#hating-on-languages-you-dont-use)
  - [H8 PHP Range Rover](#h8-php-range-rover)
  - [C++ for Python Developers](#c-for-python-developers)
  - [Hell is Debugging Other People's Code](#hell-is-debugging-other-peoples-code)
  - [Programmer Sleep Coding](#programmer-sleep-coding)
  - [Developers at Beginning vs End of of Project](#developers-at-beginning-vs-end-of-of-project)
  - [When You Decide to Share Your Pain With Users](#when-you-decide-to-share-your-pain-with-users)
  - [The DevOps Guide to Dealing with Management](#the-devops-guide-to-dealing-with-management)
  - [The Hungry Developer](#the-hungry-developer)
  - [The Mobile Developer](#the-mobile-developer)
  - [The Desert Developer](#the-desert-developer)
  - [The Lead Developer](#the-lead-developer)
  - [The Lone Wolf Developer](#the-lone-wolf-developer)
  - [Bash Scripting: Essential DevOps](#bash-scripting-essential-devops)
  - [Writing Code That Nobody Else Can Read](#writing-code-that-nobody-else-can-read)
  - [Removing Code & Hoping Nothing Breaks](#removing-code--hoping-nothing-breaks)
  - [Hype Driven Development](#hype-driven-development)
  - [Whitespace Wars](#whitespace-wars)
  - [Heroes & Villains of Software Development](#heroes--villains-of-software-development)
  - [Will Not Fix Your Computer](#will-not-fix-your-computer)
  - [Programmer Interview - Can You Work Under Pressure](#programmer-interview---can-you-work-under-pressure)
  - [How It Feels Being A Programmer After 30](#how-it-feels-being-a-programmer-after-30)
  - [When You Copy Parts of Your Code from Stack Overflow](#when-you-copy-parts-of-your-code-from-stack-overflow)
  - [Me When Code Works as Intended](#me-when-code-works-as-intended)
  - [When You're Thinking About That Code You Wrote Last Night](#when-youre-thinking-about-that-code-you-wrote-last-night)
  - [Vibe Coding, Vibe Debugging](#vibe-coding-vibe-debugging)
  - [Assembly](#assembly)
  - [C for the Brave and Foolish](#c-for-the-brave-and-foolish)
  - [Built Same Project in Multiple Languages](#built-same-project-in-multiple-languages)
  - [Pretend to be a Good Programmer](#pretend-to-be-a-good-programmer)
  - [Programmers Then vs Now](#programmers-then-vs-now)
  - [O'Reilly - Vibe Coding](#oreilly---vibe-coding)
  - [Rock Star Developer](#rock-star-developer)

<!-- INDEX_END -->

## Languages

1. [Bash](bash.md) - the gold standard for shell scripting
1. [Python](python.md) - general purpose object oriented language, easy to write, widely used but hard to maintain due
   to environment differences, language and library changes over time
1. [Golang](golang.md) - imperative compiled self-contained binaries, simple toolchain, smashes Python in portability,
   maintainability, build time etc.
1. [Perl](perl.md) - fast to write imperative code, stable, the gold standard for regex string processing, works
   everywhere and doesn't break every few years like Python
1. [Groovy](groovy.md) - a better version of Java, with interactive REPL and some language construct conveniences.
   Hard to want to write in Java again after getting spoilt by Groovy
1. [Java](java.md) - battle tested, but slower to develop in than the above languages
1. [Scala](scala.md) - was supposed to be the next Java but wasn't
1. Kotlin - another next Java, we'll see
1. Clojure - another JVM language
1. [R](r.md) - old data analytics languages, matrices, awkward, but widely used and lots of libraries
1. [Expect](#expect) - an extension of the Tcl language specialized in interactive text interface automation and
   keystroke control
1. [HTMX](https://htmx.org/) - [:octocat: bigskysoftware/htmx](https://github.com/bigskysoftware/htmx) -
   power tools for HTML

Beware the `"Hello World"`... see [this meme](#hello-world) further down.

## Expect

Excellent TCL language framework for automating systems which have no alternative but interactive timed text inputs.

[Autoexpect](https://linux.die.net/man/1/autoexpect) - generates an expect script from an interactive session, tune from there

[Expect](https://linux.die.net/man/1/expect) has libraries in most languages.

For example, used Perl's `Net::SSH::Expect` library to test [iDRAC and iLO controllers](hardware.md)
in [check_ssh_login.pl](https://github.com/HariSekhon/Nagios-Plugins/blob/master/check_ssh_login.pl)

Add this to the top of an expect script to debug output:

```shell
exp_internal 1
```

## Free Programming Courses

You are limited only by time and effort.

- [Coursera](https://www.coursera.org/)
- [edX](https://www.edx.org/learn/coding)
- [FreeCodeCamp](https://www.freecodecamp.org/)
- [CodeCademy](https://www.codecademy.com/)
- [Udemy](https://www.udemy.com/topic/programming-fundamentals/free/)
- [LearnCodeTheHardWay](https://learncodethehardway.org/)
- [Khan Academy](https://www.khanacademy.org/computing/computer-programming)
- [Class Central](https://www.classcentral.com/subject/programming-and-software-development)

<https://www.digitalocean.com/community/tutorials/gangs-of-four-gof-design-patterns>

## Testing

See [Testing](testing.md)

## Code Pastebin Sites

If you need to share code privately or publicly to ask for help, you'll need a Pastebin site,
se the [File Upload & Code Pastbin Sites](upload-sites.md) doc.

## Big O Notation

![Big O Notation](images/big_O_notation.gif)

## Count Lines of Code

### cloc

[:octocat: AlDanial/cloc](https://github.com/AlDanial/cloc/)

Counts lines of code vs comments vs blanks.

Install on Mac:

```shell
brew install cloc
```

Install on Debian / Ubuntu:

```shell
sudo apt install cloc
```

Run it against a directory of code to count the lines of code:

```text
cloc /path/to/git/checkout
```

```shell
cloc ~/github/bash-tools
```

```text
github.com/AlDanial/cloc v 2.02  T=3.16 s (1084.1 files/s, 260706.2 lines/s)
---------------------------------------------------------------------------------
Language                       files          blank        comment           code
---------------------------------------------------------------------------------
JSON                              33              5              0         528324
Bourne Shell                    1594          26338          38702          70205
YAML                             885           6568          29712          41929
HCL                              192           3965           4595          16567
Markdown                          70           3964            321          13016
Text                              56            323              0           5004
SQL                              233            862           5533           4182
Groovy                           140            924           4122           3933
Bourne Again Shell                97           1219           3904           2337
XML                               24              9              9           1490
make                              21            352            373           1320
INI                               12            148              0            804
Maven                              1             62             68            342
Python                             7            108            401            235
Perl                               5             67             74            230
m4                                 5             55              3            216
Go                                 1             12             20             97
Ruby                              13             16            247             81
Dockerfile                         1             66            181             78
Properties                         8             54            133             77
Java                               4             31             54             63
Scala                              4             27             69             42
Gradle                             2             13             60             39
Jinja Template                     1              2              0             33
JavaScript                         3             31            152             30
Expect                             2              5             15             22
Puppet                             3              7             61             20
ASP                                1              4              1             11
SVG                                6              0              0              6
C                                  1              3              6              3
zsh                                1              1             13              3
PHP                                1              3              6              2
DOS Batch                          1              2              5              1
Visual Basic Script                1              3              5              1
Pig Latin                          1              2             14              0
---------------------------------------------------------------------------------
SUM:                            3430          45251          88859         690743
---------------------------------------------------------------------------------
```

Script in [DevOps-Bash-tools](devops-bash-tools.md) to count lines across all public original GitHub repos:

```shell
github_public_lines_of_code.sh
```

### scc

[:octocat: boyter/scc](https://github.com/boyter/scc)

Counts lines of code and cocomo man effort estimate.

Install on Mac:

```shell
brew install scc
```

Linux - not in Apt yet, so you'd need to install it the Golang way:

```shell
go install github.com/boyter/scc/v3@latest
```

<!--

Install on Debian / Ubuntu:

```shell
sudo apt install scc
```

-->

Run it against a directory of code to count the lines of code:

```text
scc /path/to/git/checkout
```

```shell
scc ~/github/bash-tools
```

```text
───────────────────────────────────────────────────────────────────────────────
Language                 Files     Lines   Blanks  Comments     Code Complexity
───────────────────────────────────────────────────────────────────────────────
Shell                     1391    113237    19013     32719    61505       9083
YAML                       122      7543      464      1858     5221          0
Plain Text                  43      4291      257         0     4034          0
BASH                        16      1299      218       625      456         98
JSON                        12      7572        5         0     7567          0
Markdown                    12      3725      650         0     3075          0
Groovy                       7       198       22       156       20          0
XML                          6       358        0         0      358          0
Zsh                          5       294       58       200       36          4
Properties File              3        45        9        21       15          0
License                      2       287       45         0      242          0
Makefile                     2       466       92        51      323         22
Autoconf                     1       865      143        95      627         78
Bitbucket Pipeline           1        38        5        24        9          0
Docker ignore                1      4007     1022      1528     1457          0
Gemfile                      1        33        6        23        4          0
Python                       1        43        1        20       22          0
Ruby                         1        31        1        24        6          0
SQL                          1        21        2        15        4          0
Vim Script                   1       796       98       251      447         28
───────────────────────────────────────────────────────────────────────────────
Total                     1629    145149    22111     37610    85428       9313
───────────────────────────────────────────────────────────────────────────────
Estimated Cost to Develop (organic) $2,882,541
Estimated Schedule Effort (organic) 20.57 months
Estimated People Required (organic) 12.45
───────────────────────────────────────────────────────────────────────────────
Processed 4611424 bytes, 4.611 megabytes (SI)
───────────────────────────────────────────────────────────────────────────────
```

There are also
[badges](https://github.com/boyter/scc?tab=readme-ov-file#badges-beta)
which you can see applied on my
[GitHub profile](https://github.com/HariSekhon#cocomo---estimates-of-man-years--costs).

### Tokei

[:octocat: XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei)

```shell
brew install tokei
```

```shell
tokei .
```

## Memes

### Hello World

![Printing Hello World](images/printing_hello_world_in_5_languages.jpeg)

### Program in Tutorial vs Made Following Tutorial

![Program in Tutorial vs Made Following Tutorial](images/program_in_tutorial_vs_made_after_following_tutorial.jpeg)

### Resolving Broken Dependencies

![Resolving Broken Dependencies](images/orly_resolving_broken_dependencies.png)

### Practice

![Practice](images/github_coding_practice_vs_innate_gift.png)

### Butting Head Against A Programming Problem

![Butting Head Against A Programming Problem](images/orly_butting_head_programming_problem_until_it_works.png)

### Documentation

The importance of documentation:

![There's No Documentation - The Code is the Documentation](images/theres_no_documentation_code_is_self_explanatory.jpeg)

### Poking the Hornets Nest

![Poking the Hornets Nest](images/orly_poking_hornets_nest_of_company_codebase.png)

### Run It Again

Every one of you engineers has done this…

Don’t pretend you haven’t !!

![Run It Again](images/my_code_doesnt_work_change_nothing_run_it_again.jpeg)

### Like Coding, Good at Math

Not any more 😭

![Like Coding, Good at Math](images/cat_like_coding_good_at_math.jpeg)

### Software Development Process

How many times have you tech bros questioned your life choices?

Be honest now…

![Software Development Process](images/software_development_process.jpeg)

### Coding in Depth

![Coding in Depth](images/orly_coding_in_depth_dont_anticipate_social_life.png)

### Pretending You Know Every Programming Language

![Pretending You Know Every Programming Language](images/orly_pretending_you_know_every_programming_language.png)

### Are You Really Sure You Want to be a Software Developer??

![People Who Sell vs Build Software](images/people_who_sell_software_vs_build_software.jpeg)

### Coding with GPT

Watch out for that quality and not knowing WTF you're doing!

![Coding with GPT](images/orly_book_coding_with_gpt.jpeg)

### Senior Devs Fixing Bugs in Production

![Senior Devs Fixing Bugs in Production](images/senior_devs_fixing_bugs_in_production.gif)

### Theory vs Practice

I suspect this is only when recruiters try programming... :wink:

![When Recruiters Try Programming](images/theory_vs_practice_programming.jpg)

### Concurrent Programming

![Concurrent Programming Sleep Statements](images/concurrent_programming_sleep_statements.jpeg)

### Meme Driven Development

![Meme Driven Development](images/meme_driven_development.jpeg)

### OverEngineering Simple Solutions

![OverEngineering Simple Solutions](images/overengineering_simple_solutions.jpeg)

### Hating on Languages You Don't Use

![Hating on Languages You Don't Use](images/orly_hating_on_languages_you_dont_use.jpeg)

### H8 PHP Range Rover

Hate PHP... but PHP paid for the Range Rover...

![H8 PHP Range Rover](images/h8_php_range_rover.jpeg)

### C++ for Python Developers

![C++ for Python Developers](images/orly_c%2B%2B_for_python_developers.png)

### Hell is Debugging Other People's Code

Or even your own code from a while ago if you haven't written it carefully and commented any fancy tricks
(avoid using fancy tricks).

This is at best janitorial work.

![Hell is Debugging Other People's Code](images/orly_debugging_someone_elses_code.jpeg)

### Programmer Sleep Coding

The number of weekend mornings I’ve woken up and jumped straight on the computer for my girlfriend to ask what I’m
doing, and then I have to explain I’ve been stuck in a coding loop half the night and need to write this sh*t down to
get rid of it...

![Programmer Sleep Coding](images/programmer_sleep_coding.jpeg)

### Developers at Beginning vs End of of Project

![Developers at Beginning vs End of Project](images/developers_at_beginning_vs_end_of_project.jpeg)

### When You Decide to Share Your Pain With Users

![Password Typed Too Quickly](images/password_typed_too_quickly_denied.jpeg)

### The DevOps Guide to Dealing with Management

![DevOps Guide to Dealing with Management](images/orly_devops_guide_to_dealing_with_management.png)

### The Hungry Developer

![Hungry Developer](images/orly_hungry_developer_elephant.png)

### The Mobile Developer

The loyalty of a cat watching you get axed murdered...

Given the average tenure in Tech is ~18 months... you think you have time to train guys up?

This is why companies hunt for seniors instead of saving money on juniors at the expense of 2-3 years of training them
up to proficient level only for them to leave for another company to reap the benefits...

![Mobile Developer](images/orly_mobile_developer_mobilize_to_another_company_whenever_better_offer.png)

### The Desert Developer

![Desert Developer](images/orly_desert_developer.png)

### The Lead Developer

![Lead Developer](images/orly_lead_developer.png)

### The Lone Wolf Developer

Aren't you lucky this isn't me...

![Lone Wolf Developer](images/orly_lone_wolf_developer.png)

### Bash Scripting: Essential DevOps

![Bash Scripting: Essential DevOps](images/orly_bash_scripting_essential_devops.png)

### Writing Code That Nobody Else Can Read

Pull Request reviews are here to preven this...

![Writing Code That Nobody Else Can Read](images/orly_writing_code_nobody_else_can_read.jpg)

### Removing Code & Hoping Nothing Breaks

![Removing Code & Hoping Nothing Breakts](images/orly_removing_code_hoping_nothing_breaks.png)

### Hype Driven Development

![Hype Driven Development](images/orly_hype_driven_development.jpg)

### Whitespace Wars

![Whitespace Wars](images/orly_whitespace_wars_tabs_vs_spaces3.png)

### Heroes & Villains of Software Development

![Heroes & Villains of Software Development](images/heroes_villains_software_development.jpg)

### Will Not Fix Your Computer

Many of you will want to send this to your relatives:

![Not Fix Your Computer](images/programmer_write_code_not_fix_your_computer.jpeg)

### Programmer Interview - Can You Work Under Pressure

![Programmer Interview - Can You Work Under Pressure](images/programmer_interview_work_under_pressure_3_months_in.jpeg)

### How It Feels Being A Programmer After 30

![How It Feels Being A Programmer After 30](images/how_it_feels_being_programmer_after_30.webp)

### When You Copy Parts of Your Code from Stack Overflow

![When You Copy Parts of Your Code from Stack Over](images/cat_copy_parts_code_stack_overflow.jpeg)

### Me When Code Works as Intended

![Me When Code Works as Intended](images/me_when_code_works_as_intended.jpeg)

### When You're Thinking About That Code You Wrote Last Night

When you’re thinking about how to improve that code you wrote last night… 😂

![When You're Thinking About That Code You Wrote Last Night](images/havent_listened_to_work_she_said.jpeg)

### Vibe Coding, Vibe Debugging

![Vibe Coding, Vibe Debugging](images/vibe_coding_vibe_debugging.jpeg)

### Assembly

![Assembly](images/orly_assembly_programming.jpeg)

### C for the Brave and Foolish

![C for the Brave and Foolish](images/orly_c_for_brave_and_foolish.jpeg)

### Built Same Project in Multiple Languages

![Built Same Project in Multiple Languages](images/same_project_multiple_languages_hello_world.jpeg)

### Pretend to be a Good Programmer

![Pretend to be a Good Programmer](images/pretend_to_be_a_good_programmer.jpeg)

### Programmers Then vs Now

![Programmers Then vs Now](images/programmers_then_vs_now.jpeg)

### O'Reilly - Vibe Coding

![O'ReillyVibe Coding](images/oreilly_vibe_coding.jpeg)

### Rock Star Developer

![Rock Star Developer](images/rock_star_developer.png)

**Ported from various private Knowledge Base pages 2008+**
