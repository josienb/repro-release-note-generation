# Reproduction repo

See the [Generate release notes button does not work for release branches](https://github.com/orgs/community/discussions/113181) issue. This repository currently has an active `main` branch and a backport `release-branch-1.1` branch. A merged PR with a bugfix has been cherry picked to the backport branch and a tag `v1.1.1` has been created on the backport branch and pushed to GitHub. If we want to automatically generate release notes for `v1.1.1`, this happens:

![image](https://github.com/josienb/repro-release-note-generation/assets/7879336/f732c871-4d8e-4021-b408-fd29cc4bf3d8)

And after pushing the "Generate release notes" button:

![image](https://github.com/josienb/repro-release-note-generation/assets/7879336/0f563053-095a-4c3a-9ae4-abf1e5db23e8)
