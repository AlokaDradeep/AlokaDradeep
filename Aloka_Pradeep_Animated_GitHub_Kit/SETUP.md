# Aloka Pradeep — Profile setup

## ඉක්මන් setup එක

1. ZIP file එක extract කරන්න.
2. README.md එකේ `YOUR_GITHUB_USERNAME` තියෙන හැම තැනම ඔයාගේ GitHub username එක දාන්න. LinkedIn username එකෙන් GitHub username එක අනුමාන කරලා නැහැ.
3. Profile එකේ පෙන්වන්න නම් public repository එකේ නම GitHub username එකට හරියටම සමාන විය යුතුයි. `main` කියන්නේ branch එකේ නම විය හැකියි; profile repository name එක වෙනමයි.
4. README.md, assets folder එක සහ .github folder එක repository root එකට දාන්න. ZIP file එක පමණක් upload කළොත් README/animations වැඩ කරන්නේ නැහැ. Folder paths ඒ විදිහටම තියාගන්න.
5. `.github/workflows/contribution-snake.yml` file එක default branch එකේ තියෙන බව බලන්න. Web upload එකේ hidden .github folder එක මඟහැරුණොත් Add file > Create new file හරහා ඒ සම්පූර්ණ path එක දී YAML content එක paste කරන්න.
6. Repository එකේ Actions > Update contribution snake > Run workflow තෝරන්න. Default branch එක තෝරලා run කරන්න.
7. Workflow එක සාර්ථක වූ පසු assets/contribution-snake.svg එක සැබෑ contribution animation එකෙන් replace වේ. README එක refresh කරන්න; GitHub image cache එක නිසා ටික වේලාවක් ගත වෙන්න පුළුවන්.

## ඇතුළත් animations

- assets/hero.svg: custom animated neural-network banner.
- assets/activity-header.svg: rotating activity motif සහ animated heading.
- assets/playground.svg: pulsing technology cards, moving connection dot සහ blinking terminal cursor.
- assets/divider.svg: animated mint light line.
- Typing introduction: external animated SVG service.
- Contribution snake: GitHub Action එකෙන් generate වන සැබෑ contribution data visualization.

මුලින් contribution-snake.svg එක setup message එකක් පෙන්වනවා. එය fake activity graph එකක් නොවේ. Workflow එක run කළාම සැබෑ data එනවා.

## Activity updates

- Stats, streak සහ activity graph සඳහා README.md එකේ නිවැරදි GitHub username එක අත්‍යවශ්‍යයි.
- Snake workflow එක දිනපතා 01:17 UTC (ශ්‍රී ලංකාවේ 06:47 AM) ට schedule කරලා තියෙනවා. GitHub scheduling delays නිසා එය හරියටම ඒ මොහොතේ run වේ යැයි සහතිකයක් නැහැ. අවශ්‍ය නම් manually run කරන්න.
- Hosted stats cards භාවිත කරන්නේ external services. ඒවා cache විය හැකි අතර rate limits/downtime ඇති වෙන්න පුළුවන්. ඒ අවස්ථාවල View contribution history button එකෙන් GitHub බලන්න.
- Language breakdown එක public code composition එක පෙන්වනවා; skill level එක නොවේ.
- Workflow එකට personal access token එකක් එකතු කරන්න අවශ්‍ය නැහැ. Built-in GITHUB_TOKEN භාවිත කරනවා.
- Push denied නම් repository Actions policy එක write access ලබා දෙනවද බලන්න. Protected branch rules තිබේ නම් අවශ්‍ය review/PR ක්‍රමය අනුගමනය කරන්න.
- මේක individual user profile repository එකකට සකස් කරලා තියෙන්නේ. Organization repository එකක owner වෙනස් නිසා generated user data වෙනස් විය හැකියි.

## LinkedIn / certifications

LinkedIn button එක දැනටමත් https://www.linkedin.com/in/aloka-pradeep-644251238/ වෙත යොමු වෙනවා. Certification data LinkedIn එකෙන් automatic import කරන්නේ නැහැ.

## Sources

- Snake action: https://github.com/Platane/snk
- Typing animation: https://github.com/DenverCoder1/readme-typing-svg
- Stats cards: https://github.com/anuraghazra/github-readme-stats
- Activity graph: https://github.com/Ashutosh00710/github-readme-activity-graph

මේ package එක local files විදිහට සකස් කරලා තියෙනවා; ඔයාගේ GitHub repository එකට upload කරලා හෝ workflow එක run කරලා නැහැ.
