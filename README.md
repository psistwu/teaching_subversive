# Teaching As a Subversive Activity

## About
This is my practice of English-Chinese translation for
Neil Postman's _Teaching As a Subversive Activity_.

The work is first done on [HackMD](https://hackmd.io/@psistwu/HkofenHjS).
To have a better typesetting for the bilingual contents,
I use [Jekyll](https://jekyllrb.com/) to generate HTML webpages and
host them on [GitHub](https://psistwu.github.io/teaching_subversive/).

- Book title: Teaching As a Subversive Activity:
  A No-Holds-Barred Assault on Outdated Teaching Methods-with Dramatic and
  Practical Proposals on How Education Can Be Made Relevant to Today's World
- Author: Neil Postman
- Chinese translation by: Haopin Wu


## Webpage build instruction
1. Install __RubyGems__ and __bundler__ in your system.
2. Clone the repository via __Git__ and
   change the working directory to `/jekyll/`.
3. Install necessary Ruby packages:
   ```console
   $ bundler install
   ```
4. Generate HTML webpages:
   ```console
   $ bundler exec jekyll b -d ../doc --baseurl teaching_subversive
   ```
   Here, `-d` selects the destination of the generated webpages
   and `--baseurl` sets up the base URL for the site deployment.
   These options are required for hosting the webpages on GitHub.

