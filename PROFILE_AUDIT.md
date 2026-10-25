# Profile Audit — GitHub Snapshot

_Audit of the HeziLiu GitHub account, captured for a portfolio packet. All values below are recorded exactly as the GitHub APIs returned them; nothing has been inferred or filled in by hand. Where a field came back empty, it is explicitly flagged as not returned rather than guessed._

---

## Account

Identity was confirmed two independent ways, and both returned the same handle:

- Signed-in identity (`GET /user`): login **HeziLiu**, numeric account id **28861483**
- Search by display name "Hezi Liu": exactly one result, **HeziLiu** (id **28861483**)

Profile details, exactly as the profile returned them:

| Field | Value as returned |
| --- | --- |
| Login | HeziLiu |
| Numeric account id | 28861483 |
| Display name | Hezi Liu |
| Company | BUPT/GZU |
| Location | Beijing/Guiyang |

Profile URL: https://github.com/HeziLiu

The profile also reports `public_repos: 4`, which matches the four repositories itemized below (the initial repository search omitted forks; a second query including forks returned all four).

---

## Public repositories (4)

### 1. Little-rookie

- **URL:** https://github.com/HeziLiu/Little-rookie
- **Description:** Undergraduate coursework
- **Primary language:** Java
- **Stars:** 0
- **Fork:** no (original)
- **Default branch:** master
- **Most recent commit on default branch:** `964bd6b191a3864a4c6c4430a85d17bb16920581` — "DELETE" — 2019-06-02T07:47:10Z

### 2. Big-Buzzard

- **URL:** https://github.com/HeziLiu/Big-Buzzard
- **Description:** For future....
- **Primary language:** ⚠️ Not returned (empty)
- **Stars:** 0
- **Fork:** no (original)
- **Default branch:** master
- **Most recent commit on default branch:** `4ce5a6d6e410756cebcaed5cdf6f661c24446bda` — "Merge branch 'master' of https://github.com/Tackic/Big-Buzzard" — 2018-05-17T10:22:21Z

### 3. CodingInterviewChinese2

- **URL:** https://github.com/HeziLiu/CodingInterviewChinese2
- **Description:** 《剑指Offer》第二版源代码
- **Primary language:** C++
- **Stars:** 0
- **Fork:** yes (fork of an upstream repository)
- **Default branch:** master
- **Most recent commit on default branch:** `2d6eb6d9127d1ad728ba60bb25bc5a5e91e519ac` — "Minor changes on license comments" — 2016-12-07T05:25:09Z

### 4. awesome-chatgpt-prompts-zh

- **URL:** https://github.com/HeziLiu/awesome-chatgpt-prompts-zh
- **Description:** ChatGPT 中文调教指南。各种场景使用指南。学习怎么让它听你的话。
- **Primary language:** ⚠️ Not returned (empty)
- **Stars:** 0
- **Fork:** yes (fork of an upstream repository)
- **Default branch:** main
- **Most recent commit on default branch:** `2d1ff55a4c0f293157c8b235051b5175d3af57ef` — "Merge pull request #127 from layyback/main\n\n:pencil2: fix typo" — 2023-04-13T07:30:55Z

---

## Empty / not-returned values

The following were queried and came back empty, and are reported as such rather than filled in:

- **Big-Buzzard primary language** — the repository listing returned no primary language for this repository.
- **awesome-chatgpt-prompts-zh primary language** — the repository listing returned no primary language for this repository.

All four repositories returned a description and a stars count (each was 0), and each default branch returned a most-recent commit, so nothing else in this audit is missing.

---

## Repository used for this audit

- **URL:** https://github.com/mcpmark-eval-liuhezi/github-audit-2026
- **Default branch:** main (unchanged; audit content lives only on `audit/profile-snapshot`)
- **Audit branch:** audit/profile-snapshot
- **Files on the audit branch:** `PROFILE_AUDIT.md` (this report) and `.github/workflows/audit.yml`
