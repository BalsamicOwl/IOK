<p align="center">
  <img
    width="400"
    src="https://raw.githubusercontent.com/phish-report/IOK/main/.github/logo.svg"
    alt="IOK logo"
  />
</p>

<img
src="https://raw.githubusercontent.com/phish-report/IOK/main/.github/fake-chrome-error.yml.svg"
alt="Screenshot of one of the IOK indicator rules"
width="50%"
align="right"
/>

**Open source detection rules for phishing site techniques, kits, and threat actors 🕵️**

- **Simple:** based on [Sigma](https://github.com/sigmahq/Sigma), a simple detection rules language 🚀
- **Rich metadata:** rules have descriptions, tags, and links to blog posts or related rules.

**Use cases:**

- [Identify fingerprints of known threat actors](https://github.com/phish-report/IOK/blob/main/indicators/cazanova-cookie.yml)
- [Discover anti-analysis techniques](https://github.com/phish-report/IOK/blob/main/indicators/fake-chrome-error.yml)
- Classify which specific phishing kit is in use on a page

## 💭 Comparison to other projects

|                                       |          IOK          | [PhishingKit-Yara-Rules] |   [Wappalyzer]    |
|---------------------------------------|:---------------------:|:------------------------:|:-----------------:|
| Open Source                           |           ✅           |            ✅             |         ✅         |
| Ruleset size                          | Small, but growing 🦐 |    &gt; 300 rules 🐠     | 1000s of rules 🐳 |
| Can scan                              |   Live websites 🕸    |   Phishing kit zips 📦   | Live websites 🕸  |
| Phishing focused                      |           ✅           |            ✅             |         ❌         |
| Supports complex conditions           |           ✅           |            ✅             |         ❌         |
| Sends out stickers to contributors 🎁 |           ✅           |            ❌             |         ❌         |

[PhishingKit-Yara-Rules]: https://github.com/t4d/PhishingKit-Yara-Rules

[Wappalyzer]: https://www.wappalyzer.com/

## 🤝 Contributing

We are always looking for contributions—there's far more phishing kits and techniques than a single team can analyse!

To contribute a new rule:

1. Try to make sure it doesn't already exist
2. Open a pull request, adding your new file in the `indicators/` folder
3. We'll review it and merge your PR
4. It'll go live on [phish.report/IOK](https://phish.report/IOK)!

Documentation on how to write a rule is coming soon...

## 📝 License

This project is [ODbL](https://github.com/phish-report/IOK/blob/main/LICENSE) licensed.
You're free to use the rules in your own projects (including commercial ones!)
as long as you credit [phish.report/IOK](https://phish.report/IOK) as the source.

For more details, read [OpenStreetMap's guidance](https://wiki.openstreetmap.org/wiki/License/Use_Cases) (who also use
the ODbL license).
