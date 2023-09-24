# P4 exercise reconstruction

## Source

The baseline is the historical p4lang/tutorials snapshot at commit
`4914893445ae24bd1fa3b4aeea4910eeb412f7de`:
https://github.com/p4lang/tutorials/commit/4914893445ae24bd1fa3b4aeea4910eeb412f7de
The original license, upstream teaching materials, and reference solutions are preserved.
They are not claimed as original learner implementations.

## History

This history reconstructs saved P4 exercise changes in thirteen logical commits.
Its author and committer timestamps were copied, in order, from the repository's
former Java history at the owner's request. They do not establish when the P4
work was performed. The former Java files and ancestry are not part of this branch.

## Exercise changes and validation limits

- Basic forwarding: parsing, forwarding, IPv4 validity guard, and deparsing.
- Basic tunnel: tunnel parsing, exact-match forwarding, and deparsing.
- P4Runtime: transit rules and table readback, adapted to the baseline's Python 2 syntax.
- Load balancing: five-tuple hash and next-hop lookup guard. The saved hash call's
  missing semicolon was repaired during reconstruction.

Other exercises remain upstream materials and do not imply completed work.
P4 compilation and live network behavior have not been verified for this historical
baseline in the current environment; its legacy VM and dependencies are required.
