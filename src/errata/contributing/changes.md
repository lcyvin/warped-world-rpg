# Changes, Fixes, and Improvements

Changes, fixes, and improvements to the core source material will generally fall into one
of two categories: simple changes, which fix minor errors or do not impact gameplay or
intended meaning of a sentence, phrase, or section; and system changes, which directly
impact the rules-as-written gameplay in some form or another. Their contribution processes
differ slightly, as described below.

## Simple Changes

Warped World's core source text was originally a one-person passion project, and as such
almost certainly contains a number of typos, grammatical errors, or unclear sentences.
Improvements to these relatively minor elements can be made via an expedited contribution
process as they should not impact the core gameplay itself. If you notice an error you
wish to fix, or an improvement that can be made in a particular sentence's wording, simply
open a branch on your own fork of the main repository and submit a PR with the changes
back to the main branch on the original repository. Once the changes have received an
approval, it may be eligible to be merged. If any maintainer of the repository has
concerns or feedback regarding the change, an issue may be created for discussion
regarding the change. 

## System Changes

If you wish to contribute a change to the source material which directly impacts how
gameplay proceeds, be that tweaking default dice values, changing how systems interact, or
adding/removing rules from the material; the first step should be to open an
[issue with the System Change RFC template](https://github.com/lcyvin/warped-world-rpg/issues/new?template=-rfc--system-change.md).
Within this issue, describe the specific changes you have made or intend to make along
with the justification for these changes. If your changes have been playtested, please
also include information regarding the results of this testing and how it compares to the
source book ruleset's current gameplay experience. If playtesting has not been completed,
or more is required to evaluate your changes, please mention that additional testing is
needed so that a maintainer can apply the "playtest needed" label to your issue. Finally,
if a PR has been opened with changes to the source material ready to go, please include
the link to that PR within the issue. 

Once an issue has been created, it will require discussion and approval by at least 1
maintainer. Unless overwhelmingly approved, a system change issue will require at minimum
7 days in open status before it may be merged, to allow time for maintainers and community
to evaluate the changes. However, due to the time playtesting takes, it may be open
significantly longer. In addition, if the suggested change conflicts with or is
significantly related to another open RFC, these issues may be merged or have a new RFC
opened in order to rectify any conflicting elements or facilitate collaboration between
contributing members.

Due to the longer and more involved contribution process for major system changes, it is
recommended to open an RFC issue *before* contributing work, to prevent duplicate work
from being done and allow feedback and discussion to occur before significant time is sunk
into making changes. For relatively minor system changes, this is less likely to be an
issue, but in cases where major overhauls to systems or gameplay elements are proposed,
the need for discussion is significant.

Once the RFC has been appropriately discussed and the associated PR has been reviewed, the
issue may be given an approval alongside the PR; allowing the changes to be merged and the
issue to be closed. 
