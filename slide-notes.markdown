# Intro to Vim

## Intro to Vim

## Why I use Vim

* Was using too many tools
  * Sublime Text 2 for editing
  * Putty for SSH
  * git bash for git
  * Cygwin for Rubt commands
* Can mostly be done in ST2, but with time invested.  Restart with Vim
  * "nerd cred"
  * More importantly, server administration
    * Vim (or vi) works **everywhere**, no matter how broken the machine is
    * (emacs does not)
  * After 20 years, people are still finding new ways to use it
  * Repetitive Strain injury - vim helps enforce better habbits
* You have to decide what works for you

## Everyone's first Vim session

* Bash.org joke

## But how can we avoid this

* vimtutor - 30-45 minutes is enough to gain usability
* VIM Adventures - game that finally pushed me into learning
* Cheat Sheet - I still keep one printed off on a wall
* Focus on a small set - I picked five that I wrote down and learned each week
  * and still do from time to time

## You will still struggle

* Some of the things I struggled with
  * Copy and paste - very different idea, more later (and more advanced)
  * Not using a mouse - if you don't plan on this, Vim is not for you
  * Getting to the end of the line example
    * I used shift+A<ESC> instead of $ for months

## Vim has modes

* In the early days, all editors had modes.  By programmers, for programers.
* Mid-1970s, Larry Tesler came up with the concept of modeless editors.
* But a lot of power in favor of this ease of use.

## You can move around

* Focus on home row.  h, l to go left and right, j, k to go up and down
  * Arrow keys are bad.  Require awkward hand movements.
* Variants can get you around the screen faster.
  * Screen: H, M, L
  * Document: gg, G, :50

## And do things

* insert is a complete mode switch to let you type text, leave with <ESC>
* delete, change, yank act on things
* All of them put affected text into a place that can be pasted from

## On objects

* Everything is an object in Vim.
* Learning to utilize these is the key to effective vim use

## That can be modified

* inside - excludes the surrounding part of the object
* around - includes the surrounding part of the object
* till - from cursor to the specific character
* find - the same as till except for including the specific character

## And finally combined into a language

* das - includes the spaces.  dis would not include the space after

# Demonstration

# Other Talks

* Ben Orenstein - one of my favorite speakers.  more intermediate than beginner
  * Note comment on saving keystrokes
* Damian Conway - More advanced and neat plugins
* Chris Hunt - Shows basics of using Vim in combination with Tmux
  * I do this

# Resources

* Slides along with sample configuration available on Github

# Try Vim for yourself
