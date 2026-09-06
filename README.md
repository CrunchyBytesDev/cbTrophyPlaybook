# cbTrophyPlaybook — ARCHIVED

Moved 2026-09-06: these playbooks now live in the private
[cbTrophyPi](https://github.com/CrunchyBytesDev/cbTrophyPi) repo under
`ansible/`, alongside a new `local.yml` that devices run nightly via
`ansible-pull` (trophy-ansible-pull.timer).

This repo was public only because we believed anonymous cloning was
required for device access; devices authenticate with a read-only deploy
key, so one private repo covers everything.
