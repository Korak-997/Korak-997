# README open questions

Things I could not verify or that need your call. The matching `TODO(verify)` comments are in `README.md`.

## Blocking nothing, but please answer before merging

1. **ki.oracom.de link.** F3 names the platform URL, but I don't know whether it is a public page or should be linked from a personal profile. Remove the link if unsure.
2. **Door-access integration: your role.** F5 says "built or led" for the group as a whole. The bullet currently states the work without a verb. If you built it, add "Built"; if you led it, add "Led".
3. **Post URLs.** I only have the `/writing` index for the three posts. All three entries currently link to the index. Send me the individual URLs and I'll switch them.
4. **RSS/Atom feed.** `korak-kurani.com` is blocked from this workspace, so I could not check for a feed. The list is static and I did not add the weekly refresh Action. If a feed exists, tell me its URL and I'll add a SHA-pinned, minimal-permission workflow that only commits `README.md`.
5. **Naming Sha Style.** F6 names your first client, but a client name on a public profile needs their consent. I left it out.
6. **Naming Morika publicly.** It is labelled "in development", as required. Confirm you are happy for the name to appear before the product launches.
7. **Email.** No email was provided in the prompt, so none is listed.

## Verified against the repos

Read on 2026-09-29 from shallow clones (the GitHub API and `gh` were not available in this session):

- `agemon`: MIT, TypeScript source, tests, CHANGELOG, `--dry-run`, Ubuntu-only per its README, `## Install` section present.
- `qrgen`: MIT, Vue, described as free and ad-free.
- `esp8266_yt_counter`: exists and is public. I left it out of the README to keep it short.

## Not checked

- Whether a GitHub Release exists for `agemon` (needs the API). The installer's default "latest" path depends on it.
- Repo descriptions and topics on GitHub, for the same reason.
- Pinned repositories on the live profile.
- Anything on `korak-kurani.com`, `nishansystems.de` or LinkedIn.

## Left untouched, your decision

- `.github/workflows/main.yml` still runs the daily.dev DevCard action every day and commits `devcard.svg` / `devcard.png` (the PNG is 0 bytes). The new README no longer uses either. I'd remove the workflow and both files, but that is outside what you asked for. There is also a stale Dependabot branch for that action.
- Your profile bio and pins are manual steps, listed in the final message.

## Optional appendix (agemon polish): not done

I did not start the appendix, and one item in it I would not do as written. See the final message.
