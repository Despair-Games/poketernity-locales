## What are the changes introduced by this PR?

<!-- Tell what this PR does and why -->
<!-- Specify which keys are being created, added or removed, if any -->

## Checklist
<!-- This section can be ignored if the PR only adds translations to existing key(s) or fixes typo(s) -->
- [ ] Have I created an associated PR in the main repo?
  - [ ] Please link it here:
- [ ] Have I made sure that the changes work in game?
  - [ ] Have I provided screenshots of it in this PR or the main repo PR?

#### Does this PR add new key(s) to localize?
- [ ] If so, have I made sure to add the new key(s) in the English file(s) only?
<!-- not relevant for now - [ ] Has the translation/proofreading team been contacted about the new key(s)? -->
<details><summary>Merging process reminder for this situation</summary>

- **If the PR also updates or removes key(s), please refer below to the process for these cases instead**
- If not, this locale PR can be merged at any time as long as it has been approved
- The main PR can then update the submodule by running the command `npm run update-locales:remote` and committing the change

</details>

#### Does this PR update or remove existing key(s) in English?
- [ ] If so, have I deleted the outdated key(s) in all languages other than English?
<!-- not relevant for now - [ ] Has the translation/proofreading team been contacted about the updated key(s)? -->
<details><summary>Merging process reminder for this situation</summary>

- This locale PR should **not** be merged until the main repo PR is ready to be merged itself
- Once both the main repo PR and this PR have the needeed approvals:
  - Merge this locale PR
  - In the main PR, update the submodule by running the command `npm run update-locales:remote` and committing the change
  - The main repo PR can now be merged

</details>
