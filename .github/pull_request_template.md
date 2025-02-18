## What are the changes introduced by this PR

<!-- Tell what this PR does and why. -->
<!-- Specifies which keys are being created, added or removed, if any-->

## Checklist

- [ ] Have I created an associated PR in the main repo?
  - [ ] Please link it here:
- [ ] Have made sure that the changes work in game?
  - [ ] Have I included screenshots of them in this PR, or the main repo PR?

- [ ] Does this PR adds new key(s) to localize?
  - [ ] If so, have I added the new key(s) only in the English file(s)
<!-- not relevant for now - [ ] Has the translation/proofreading team has been contacted? -->
<details><summary>Merging process reminder</summary>

- **If the PR also updates or removes key(s), please refer to the process reminder for these cases instead**
- This locale PR can be merged at any time as long as it has been approved
- The main PR can then update the submodule by running the command `git submodule update --remote --recursive --force` and committing the change

</details>

- [ ] Does this PR updates or removes existing key(s)
  - [ ] If so, I have deleted the outdated key(s) in all languages other than English
<!-- not relevant for now - [ ] Has the translation/proofreading team has been contacted about the updated key(s)? -->
<details><summary>Merging process reminder</summary>

- This locale PR should **not** be merged until the main repo PR is ready to be merged itself
- Once both the main repo PR and this PR have the needeed approvals:
  - Merge this locale PR
  - In the main PR, update the submodule by running the command `git submodule update --remote --recursive --force` and committing the change
  - The main repo PR can now be merged

</details>
