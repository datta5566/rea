# Cracked career skills

This repository includes [nishant-Tiwari24/cracked](https://github.com/nishant-Tiwari24/cracked) as a Git submodule at `external/cracked`.

## First-time setup

Clone this repository with the submodule:

```bash
git clone --recurse-submodules https://github.com/datta5566/rea.git
cd rea
```

If you already cloned it:

```bash
git submodule update --init --recursive
```

## Useful skills for job applications

The upstream project is primarily designed for software/tech interviews. For Quality Assurance and manufacturing-quality roles, start with these adaptable workflows:

- `skills/profile/roast-my-resume` — review a resume and improve clarity without inventing achievements.
- `skills/profile/jd-match` — compare a real job description with your experience and identify gaps.
- `skills/profile/referral-dm` — prepare a concise, truthful referral message.
- `skills/strategy/offer-decode` — understand and compare a job offer.
- `skills/core/setup-cracked` and `skills/core/cracked-profile` — configure the skills and their local profile.

The DSA, online-assessment, and system-design interview skills are mainly for software engineering roles and may not fit manufacturing QA interviews without adaptation.

## Install for an AI coding agent

Follow the upstream README for the supported agent installation method and current commands:
https://github.com/nishant-Tiwari24/cracked#installation-30-second-setup

Do not run unfamiliar scripts blindly. Review commands and requested permissions first. Keep personal details, resumes, tokens, and credentials out of commits.

## Update the submodule

```bash
git submodule update --remote --merge external/cracked
git add .gitmodules external/cracked
git commit -m "chore: update cracked skills submodule"
```

Upstream source is MIT-licensed; retain its LICENSE and attribution when redistributing its contents.
