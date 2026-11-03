---
title: Story Article Editor User Manual
lang: en
---

**Story Kit version 0.8** · 한국어 매뉴얼: `사용매뉴얼.md` / `사용매뉴얼.docx`

A user manual for a web editor that helps data-journalism students and instructors build interactive articles with photos, Flourish charts, Google Sheets tables, Google Earth maps, YouTube videos and scrollytelling. There is nothing to install and no account to create: open one file in Chrome or Edge, and export the finished article as a single HTML file to put on the web.

| Reader | Start with |
|---|---|
| Students and aspiring reporters building an article | Ch. 1 Getting started → Ch. 2–4 how to fill in each part → Ch. 5 saving and publishing → Ch. 6 checks |
| Professors and instructors running a course | Ch. 7 Using it in a course → Ch. 8 story planning guide |

# 1. Getting started

The editor is a single file, `index.html`. No installation or sign-up. Open it in Chrome or Edge and start.

1. Download `index.html` to your computer.
2. Drag the file into a Chrome window, or double-click it.
3. The first time you open it, an **example article** is loaded. All numbers and place names are made-up practice data. Edit or delete them one by one to turn it into your own story.
4. To start from scratch, press **New article** in the top bar. Press **Load example** whenever you want the example back.

## The screen

| Area | What it does |
|---|---|
| Top bar | New article, Load example, Open / Save work file, Publish, language switch (EN \| 한국어), Help |
| Left editing pane | Fill in content in this order: Cover → Style → Blocks → Credits |
| Right preview | Shows your content as the real article, instantly. Switch between Desktop (PC) and Mobile views with the buttons above it |

- Click a paragraph or photo in the preview and its block opens on the left.
- Open a block on the left and the preview scrolls to that spot.
- When the window is narrow (for example a laptop screen split in half), **Edit / Preview** switch buttons appear at the top.
- Your work is autosaved in this browser and the last save time is shown at the top right. To move your work to another computer, you must use **Save work file** (Ch. 5).

## Language settings (English · 한국어)

The editor supports English and Korean, with two separate settings.

| Setting | Where | What it changes |
|---|---|---|
| Editor language | The **EN \| 한국어** button in the top bar | The editor itself: buttons, hints, check messages. The page reloads when you switch, and your work is kept. The first time, it follows your browser language |
| Article language | The first field under **Cover and article info** | The built-in wording inside the published article (Source, Copy link, Expand / Collapse, empty-block hints) and the `lang` attribute |

- The two settings are independent. You can write an English article in the Korean editor and vice versa.
- Your headline, body text and captions appear exactly as you type them. Nothing is translated automatically.
- Work files saved before the language feature existed open with the article language set to Korean.

# 2. Cover, Style, Credits

The top two cards and the bottom card in the left pane exist once in every article.

## Cover and article info

| Field | How to use it |
|---|---|
| Article language | English / 한국어. Language of the built-in wording in the published article |
| Outlet name | Shown at the left of the top bar. e.g. Kwangwoon Data Journalism Lab |
| Kicker | The small line above the title: series name or beat. e.g. Seoul in data |
| Article title | A line break shows as a line break on the cover. Two lines or fewer is recommended |
| Subtitle · lede | 2–3 sentences under the title: the key finding, with numbers |
| Cover layout | Title over photo (full screen) / Title and photo side by side / Text-first |
| Cover photo | [Upload photo] or drag and drop. Automatically resized and embedded in the file |
| Authors | One per line as `Name email`. The email becomes a link |
| Team name · date | Shown together in the byline under the title |

- With no cover photo you get a dark cover with a soft glow in the accent color.
- When putting the title over a photo, choose a photo whose lower part is not too bright. The title sits in the lower part.

## Style

| Field | How to use it |
|---|---|
| Background color | Pick one of six suggested colors or choose your own. With a dark background, text turns light automatically |
| Accent color | Color of highlights, kickers, big numbers and the top progress bar. Six suggestions or your own |
| Heading font · Body font | Choose from Nanum Gothic (default), Malgun Gothic, Noto Sans KR, Nanum Myeongjo, Noto Serif KR, Gowun Batang, or My uploaded font |
| Upload a font file | Upload a woff2, woff, ttf or otf file and it is applied to headings and body as "My uploaded font". Up to 12 MB |
| Body text size | 14–24 px (default 18). Captions, tables and boxes scale by the same ratio |
| Heading size | 70–130% (default 100). Applies to the article title, headings, quotes and big numbers |

- The default **Nanum Gothic** is a web font, so it looks the same on Windows, Mac and phones. Malgun Gothic exists only on Windows; on Mac and phones a similar default sans-serif (Apple SD Gothic Neo, etc.) is shown instead.
- An **uploaded font** is embedded in the article file, so it looks identical even if readers don't have it. The catch is that Korean fonts are several MB and make the article heavy, so use a smaller woff2 file when possible.
- Upload only fonts licensed for web publishing (embedding). Even free fonts have usage terms, so check the license at the source.

## Credits · sources

- **Credits**: one per line as `Role: Name`. e.g. `Data analysis: Alex Kim`
- **Sources**: one per line. Addresses become links automatically.
- **Closing note · corrections**: a note or a correction notice at the end of the article.
- **Share preview image address**: the picture shown when the link is sent via KakaoTalk or social media. Only an image address already on the web works. If left blank, only the title and subtitle show, with no picture.

# 3. Using the blocks

The body of an article is built by stacking blocks. Press **Add block** at the bottom, or hover between two blocks and press the **+** button to insert one at that spot. The buttons on the right of a block move it up or down, duplicate it or delete it.

| Block | Group | When to use it |
|---|---|---|
| Heading | Text | To divide the story into chapters. You can add a small kicker above it (e.g. Part 1 · Income) |
| Paragraph | Text | Body paragraphs. Bold, highlight, italic and links available |
| Quote | Text | A source's key statement, set large |
| Callout box | Text | Methods, glossary. With "Start collapsed" on, it opens only when clicked |
| Divider | Text | Scene break. Short line / Three dots / Space only |
| Photo | Media | One photo with a caption and credit |
| Gallery | Media | 2–4 photos side by side |
| YouTube | Media | A video (see Ch. 4) |
| Big numbers | Data | Count-up numbers rising from 0, up to 4 |
| Flourish visualization | Data | Charts and maps (see Ch. 4) |
| Google Sheets table | Data | A table (see Ch. 4) |
| Google Earth · Map | Data | A satellite map with a 3D view button (see Ch. 4) |
| Scrollytelling | Interactive | The graphic stays fixed on screen while text cards scroll past and change the scene |
| Other embed | Interactive | iframe code from Datawrapper, surveys, maps and more (see Ch. 4) |

## Text formatting

You can use the buttons above the text field or type the symbols yourself.

| Type | Result |
|---|---|
| `**bold**` | **bold** |
| `==highlight==` | highlight in the accent color |
| `*italic*` | *italic* |
| `[text](https://address)` | a link |
| One blank line | new paragraph |
| `- ` at the start of a line | list |

## Photos

- Photos are automatically resized and embedded in the article file. You don't need to upload them to the web separately.
- **Alt text** is the description read aloud by screen readers for blind and low-vision readers. Always write one sentence saying what the photo shows.
- **Width**: Text width / Wide / Full screen. For photos where atmosphere matters, try "Full screen".
- The more photos, the bigger the article file. The size is shown on the Publish screen.

## Big numbers

- If you type only digits in the **Number** field (e.g. `1,600`, `8.4`), it counts up from 0 when the reader reaches it. Commas and decimal places are preserved.
- If letters are mixed in, such as `1.6 billion`, it is shown as is with no animation. In that case split it: number `1.6`, unit `billion`.

## Scrollytelling

The graphic behind stays fixed on screen while only the text cards scroll up past it and the graphic changes. It is the same principle as the chart highlights in the Kyunghyang Shinmun report on 33 indicators of inequality in Korea, and the data transitions in "People who buy votes they won't cast".

1. Choose the **Graphic pinned behind**: photos / graphics, or a Flourish story.
2. For photos / graphics, upload a graphic for each step. A step left blank keeps the previous graphic.
3. Write each step's **Text card** in 2–4 sentences.
4. For graphics that must not be cropped, such as charts and maps, set **Graphic fit** to "Never crop".
5. Place the **Text card position** (left, center, right) on the empty side of the graphic.

- Tip: make several versions of the same chart with **only the highlight changed**. e.g. Step 1 all gray, Step 2 only Seoul in red, Step 3 Seoul and Busan in red.
- If you choose a Flourish story, enter a "Slide number to show" for each step. The story jumps to that slide as the card passes.

# 4. Getting embed addresses

When you paste an address, **✓ Recognized** or **✕ Couldn't recognize** appears right below the field. A green check means it worked.

## Flourish visualization

1. After finishing a chart in Flourish, press **Export & publish** at the top right.
2. Press **Publish to share and embed** to publish it.
3. Copy the link that appears (`https://public.flourish.studio/visualisation/…`) and paste it. You can also paste the whole **Embed code**.
4. Adjust **Desktop height** and **Mobile height** so the chart isn't cropped. Give charts with many legend items a taller mobile height.
5. Always fill in the **Data source**. If left blank it shows up in the checklist when you publish.

- If you enter an editing address (`app.flourish.studio/…/edit`), a "make sure you have published" notice appears. Readers can't see it until it is published.

## Google Sheets table

There are two modes. We recommend the **article-style table**: it matches the article's design, and the table stays even if you delete the sheet later.

1. In Google Sheets choose **File > Share > Publish to web** and press **Publish**.
2. Paste the link into the **Google Sheets address** field.
3. Press **Fetch data from the sheet** and the **Table data** box below fills in.
4. If fetching fails: drag over the table range in the sheet, copy it (Ctrl+C), and paste it into the **Table data** box. That's all.

- The first row becomes the header. Columns containing only numbers are right-aligned automatically.
- Long tables scroll inside the table and the header row stays pinned at the top.
- If you choose **Embed the Google Sheets view as is**, the sheet itself appears inside the article. Edits to the sheet show up in the article right away, but the design stays Google Sheets' own.

## Google Earth · Map

Google Earth for web is blocked from being embedded directly in other sites. So this block embeds a **satellite map of the same place** and adds a **View in 3D on Google Earth** button below it. When the reader presses the button, that scene opens in Google Earth in a new window.

1. Go to the place and angle you want to show on earth.google.com.
2. Press the **link icon** (share) in the left menu and copy the link. Copying the address bar works too.
3. Paste it into the block and the latitude, longitude and zoom fill in automatically.
4. Choose the **Map type** (Satellite / Satellite + labels / Standard map), **Drop a pin**, and the height.

- A Google Maps address, or just coordinates like `37.5665, 126.9780`, also works.
- If you paste the code from Google Maps **Share > Embed a map**, that map is embedded as is.
- For flight videos made with Google Earth Studio, upload them to YouTube and use a **YouTube block**.

## YouTube

1. Press **Share** under the video.
2. To start at a specific scene, tick **Start at**.
3. Paste the **copied** address. A Shorts address is embedded as a vertical screen.

- In a preview opened from your own computer, "Error 153" may appear. That is because YouTube blocks playback on pages that have no web address. Once you publish it to the web, it plays normally.

## Other embed

Most services that give you `<iframe …>` code, such as Datawrapper charts, Google Forms and Kakao Map, can go in this block.

- If you paste the whole code, the editor picks out only the address (src) and the height.
- Code that needs `<script>` (such as responsive height adjustment) is not run. Set the desktop and mobile heights yourself instead.
- Only addresses starting with https:// are accepted.

# 5. Saving and publishing

There are two kinds of files. The **work file (.json)** is the original you use to keep editing, and the **published file (index.html)** is the finished version readers see. Keep both.

| File | Button that makes it | Use |
|---|---|---|
| `article-title.storykit.json` | Save work file | Continue editing, move to another computer, pass between teammates |
| `index.html` | Publish → Download HTML file | The finished version to put on the web. Photos are included in the one file |

## Autosave and work files

- The editor autosaves in this browser on this computer. When you reopen the file on the same computer, your article is still there.
- On another computer, another browser, or in a private window, the autosave won't appear. If you use a lab computer, always **Save work file** before you finish.
- To continue next time, use **Open work file** and pick the .json file.
- Group work: one person saves a .json and sends it by messenger or drive, and another opens it and continues. You can't edit at the same time, so take turns.

## Publishing

Press **Publish** and the check results appear first. It tells you about a missing title or author, photos without alt text, embeds that will drop out for lack of an address, and charts without a source. After fixing them, press **Download HTML file**.

- In the published article, empty blocks and embeds whose address isn't recognized are left out automatically. The dashed boxes in the preview don't appear in the published file.
- If the file size exceeds 15 MB, a warning appears. Use fewer photos.

## Putting it on the web, option 1 · Netlify Drop (easiest)

1. Create a new folder on your desktop and put the downloaded `index.html` in it.
2. Go to `app.netlify.com/drop` in your browser and sign up for free.
3. Drag the whole folder onto the page. A few seconds later your article has an address.
4. In the site settings you can change the first part of the address to the article's name.
5. To re-upload after editing, drag the folder onto that site's **Deploys** screen again. The address stays the same.

## Putting it on the web, option 2 · GitHub Pages

1. On GitHub, create a new repository set to **Public**.
2. Upload `index.html` with **Add file > Upload files**.
3. In **Settings > Pages**, choose `main` as the Branch and press **Save**.
4. After 1–2 minutes the article opens at `https://username.github.io/repository-name/`.

- Uploading again to the same repository (overwriting the same name) updates the article.
- YouTube, Flourish and maps display most accurately in an article that is on the web. Always open the web address and check before you publish.

# 6. Common problems and pre-publication checks

| Symptom | Cause | Fix |
|---|---|---|
| Your article is gone when you reopen the file | You opened it on another computer, browser or private window | Use **Open work file** to open the .json you saved |
| "Error 153" on YouTube in the preview | The page was opened from your computer, so YouTube blocks playback | Publish it to the web and it plays normally |
| The Flourish spot is empty | It isn't published, or you entered the editing address | Publish in Flourish and use the link you get |
| [Fetch data from the sheet] fails | The sheet isn't published to the web, or it's private | Publish it to the web, or copy the table and paste it in yourself |
| A chart or map is cropped on phones | The height is too small | Increase the block's **Mobile height** and check with the preview on **Mobile** |
| A scrollytelling graphic is cropped | Graphic fit is "Fill the screen" | Change it to **Never crop** |
| The numbers don't count up | The Number field has letters mixed in | Split it into a number and a unit |
| The published file is too big | Too many photos, or a large GIF | Use fewer photos, or use YouTube or a photo instead of a GIF |
| The preview doesn't update | Auto-refresh is off | Press **Refresh** above the preview, or turn auto-refresh on |

## Pre-publication checklist

- [ ] The title and subtitle state the key finding, with numbers
- [ ] Author names, the team name and the date are filled in
- [ ] Every photo has alt text and a credit
- [ ] Every chart and table has a data source
- [ ] Charts, maps and tables aren't cropped in the Mobile preview
- [ ] The Publish screen's check results show 0 issues
- [ ] Opened at the web address, YouTube, Flourish and maps all show
- [ ] You kept both the work file (.json) and the published file (index.html)
- [ ] The credits at the end list production roles and sources

# 7. Using it in a course (for professors and instructors)

## Distributing the editor

The editor is one `index.html` file. Put it on the web and students can open it with a single address, and you can roll out fixes in one go.

1. Put `index.html` in a folder and drag it onto `app.netlify.com/drop`. (GitHub Pages works too. See Ch. 5.)
2. Share the resulting address with students.
3. To re-upload after changing the editor, drag the folder onto the same site's Deploys screen and the address stays the same.

Students' work is not sent to any server; it is saved only in each person's browser. No student information is collected, but that means students must keep their own work files (.json).

## What to tell students in the first session

- Autosave is kept only in that browser on that computer. If they use lab computers, have them **Save work file** before the session ends.
- For group work, let only one person edit at a time and pass the .json file around. If two people edit at once, one person's changes overwrite the other's.
- Flourish, Google Sheets and YouTube may need free accounts, so have them sign up beforehand. If they sign up during class, the session is over before editing starts.
- Go over source attribution for data and photos, copyright, and the principle of consent from sources.

## Assignment design example

The table below is an example; remove or add items to fit your course goals.

| Element | Example criterion | Editor block |
|---|---|---|
| Basic structure | Title, subtitle, authors, credits, 10 or more body blocks | Cover, Paragraph, Heading |
| Data visualization | At least one chart or map, with a source | Flourish |
| Table or numbers | A Google Sheets table or big numbers | Google Sheets table, Big numbers |
| On-the-ground feel | At least one photo; a map if the story is location-based | Photo, Google Earth · Map, YouTube |
| Interactive | At least one scrollytelling block | Scrollytelling |
| Submission | The web address of the published article, and the work file (.json) | Publish, Save work file |

## Grading criteria example

| Item | Weight (example) | What to look for |
|---|---|---|
| Topic and framing | 20% | Is the question clear and answered with data? |
| Data visualization | 30% | Do the charts fit the claim and read easily? Is there a source? |
| Story structure | 25% | Does the scroll-through reading flow feel natural? |
| Use of interactivity | 15% | Do scrollytelling, maps and video aid understanding? |
| Polish | 10% | Mobile view, sources, alt text, credits |

## How to submit

- If students submit the address they published under their own account, each article gets its own address.
- To show all the articles in one place, you can upload them into per-student folders in an instructor repository.
- Before grading, open the web address and confirm that YouTube, Flourish and maps all show. If you open a downloaded file from your own computer, YouTube may give "Error 153".

# 8. Story planning guide

A good data story starts from a question, not a tool. Before you open the editor, sketch it on paper in this order.

1. **One-sentence question**: what question does this story try to answer with data?
2. **One-sentence key finding**: the answer, with numbers. This sentence becomes the title and subtitle.
3. **Split into scenes**: divide the finding into 3–5 scenes and give each a heading.
4. **One piece of evidence per scene**: choose the one chart, table, map, photo or video that best fits that scene.
5. **Interaction only when it aids understanding**: don't let the effect become the goal.

## What to keep in mind inside the article

- Instead of a chart title, write a **sentence that states the finding**. e.g. "8.4% of households live more than 10 minutes from a bus stop".
- State the **source and reference date** for all data.
- Use color only when it means something. Set a rule, such as blue for positive and red for negative, and use it consistently.
- Many readers use phones. Always switch the preview to **Mobile** and check.
- Give photos and videos alt text and credits, and don't use copyrighted material.
- Print names and recognizable faces of sources only with their consent.

# 9. Data journalism reference cases

- [Data Journalism Archive](https://app.notion.com/p/406e950b95904ffc8ff9361cb20a4e70?v=3fb6bc1164fb8195872d000c84a7ee42) (Notion): a collection of data journalism and data storytelling cases
- Newsjelly (2026.2.4). [2025 Korea Data Journalism Awards: digging into the interactive elements of the winners](https://newsjel.ly/archives/newsjelly-report/visual-curation/17265)
- Kyunghyang Shinmun Data Journalism Team (2025.4.11). [The far-right YouTubers already knew about martial law](https://www.khan.co.kr/kh_storytelling/2025/youtube/)
- Kyunghyang Shinmun Data Journalism Team (2025.3.11). [A report on inequality in Korean society through 33 indicators](https://www.khan.co.kr/kh_storytelling/2025/inequal/)
- Kyunghyang Shinmun Data Journalism Team (2025.10.28). [Lee Jae-myung vs. Yoon Suk Yeol through the budget](https://www.khan.co.kr/kh_storytelling/2025/budget/)
- Kyunghyang Shinmun Data Journalism Team (2025.7.29). [The government's first faces: a comparative analysis of past cabinets and presidential offices](https://www.khan.co.kr/kh_storytelling/2025/cabinet/)
- Beautiful Forest (2025). [People who buy votes they won't cast](https://beautiful-forest.vercel.app/)
