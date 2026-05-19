# KangLang Elementary · Bilingual Page

A bilingual web page for **臺中市清水區槺榔國民小學 (KangLang Elementary School)**, a middle-tier bilingual public elementary school in Qingshui District, Taichung.

Built and donated by [My Culture Connect 人師教育協會](https://www.mycultureconnect.org/), a Taiwanese non-profit. Hosted on GitHub Pages at:

**Live**: <https://lukelin7429.github.io/klnes-bilingual/>

## Pages

| URL | Page | Content |
|---|---|---|
| `/` | Home | School identity, lineage from Dashiou (1982 → 1991), three pillars, principal teaser, student life cards, contact |
| `/principal/` | Principal's Office | Dr. Wang Sheng-chung (7th principal), bilingual letter, three commitments, full lineage of seven principals |
| `/bilingual-campus/` | Bilingual Campus | Middle-tier bilingual curriculum (Grade 3 Science / Grade 4 Integrated / Grade 6 Math) + embedded Classroom English & Bilingual Announcements playlists (My Culture Connect resources) |
| `/community-walk/` | Community Walk | A bilingual companion to KangLang's signature outdoor curriculum &ldquo;Walking Qingshui&rdquo;: six stations (kanglang trees → broom-makers → temple → market → rice fields → coast), each with English and Chinese phrases |

## Design

- **Primary**: deep coastal teal `#1E5963`
- **Accent**: sand gold `#D9A85B` (a nod to the dried kanglang leaves that became brooms)
- **Type**: PingFang TC + Cormorant Garamond (English serif) + Inter (English sans)
- **Background**: pure white throughout
- **Pattern**: inline single-page per section &mdash; no click-outs, no popups, no iframes-in-iframes

## Bilingual resource credits

The two YouTube playlists embedded on `/bilingual-campus/` are produced by **My Culture Connect** and shared across multiple partner schools. The same playlists power similar pages at other schools in the MCC network. See the [shared assets registry](https://www.mycultureconnect.org/) for the canonical record.

## To bind a custom domain

If KangLang Elementary's IT eventually wishes to bind a subdomain (e.g. `bilingual.klnes.tc.edu.tw`) to this page:

1. Create a `CNAME` file in this repo's root containing only the desired hostname.
2. In your DNS console, add a `CNAME` record pointing the chosen hostname to `lukelin7429.github.io`.
3. Wait for propagation (typically 1&ndash;24 hours), then enable HTTPS in this repo's **Settings → Pages**.

Note: `tc.edu.tw` subdomains are managed through TANet — KangLang's IT will need to submit the change through that channel.

## License

Content (text and curriculum design) is original to KangLang Elementary and My Culture Connect, and shared for non-commercial educational reuse. Code (HTML/CSS) is MIT-licensed.

## Maintainer

- **Repo**: [lukelin7429/klnes-bilingual](https://github.com/lukelin7429/klnes-bilingual)
- **Designed and donated by**: [Luke Lin 林吉祥](https://www.mycultureconnect.org/), My Culture Connect 人師教育協會
- **School**: [klnes.tc.edu.tw](https://klnes.tc.edu.tw/) · 04-2656-2684
