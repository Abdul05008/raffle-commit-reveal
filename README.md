Raffle-Commit-Reveal
A provably fair raffle contract built with Clarity on the Stacks blockchain.
It uses a commit-reveal scheme to prevent front-running and ensure fairness in random winner selection.

Features
Two-phase commit-reveal process
Commit entry with hash of (secret + address)
Reveal secret to validate entry
Random winner chosen from valid reveals
Event logs for transparency
