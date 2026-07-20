[WTRRJ_Sources_Final_Cut.html](https://github.com/user-attachments/files/30199572/WTRRJ_Sources_Final_Cut.html)
# The-Jesus-You-Never-Met-Sources
This channel is built on one rule: every claim traces to a primary source with a direct URL before it goes to camera. Nothing here is asking you to take my word for it — go read the originals. I've labeled every source as either [Established] (documented fact) or [Contested] because honesty about what we know and don't know is the whole point.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Who Was the Real Jesus? — Sources by Chapter</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html, body {
            font-family: 'Georgia', 'Garamond', serif;
            background: linear-gradient(135deg, #faf7f2 0%, #f5f1eb 100%);
            color: #2c2c2c;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        header {
            text-align: center;
            margin-bottom: 60px;
            border-bottom: 2px solid #c9a876;
            padding-bottom: 40px;
        }

        h1 {
            font-size: 2.8em;
            font-weight: 400;
            letter-spacing: -0.02em;
            color: #1a1a1a;
            margin-bottom: 12px;
            font-style: italic;
        }

        .subtitle {
            font-size: 1.1em;
            color: #6b6b6b;
            font-weight: 300;
            margin-bottom: 20px;
        }

        .meta {
            display: flex;
            justify-content: center;
            gap: 30px;
            font-size: 0.95em;
            color: #7a7a7a;
            margin-top: 20px;
        }

        .legend {
            background: rgba(201, 168, 118, 0.08);
            border: 1px solid rgba(201, 168, 118, 0.3);
            border-radius: 4px;
            padding: 24px;
            margin: 40px 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 24px;
        }

        .legend-item {
            display: flex;
            gap: 12px;
            align-items: flex-start;
        }

        .legend-badge {
            font-size: 0.75em;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.08em;
            padding: 4px 8px;
            border-radius: 2px;
            white-space: nowrap;
            margin-top: 2px;
        }

        .badge-verified {
            background: #e8f5e9;
            color: #2e7d32;
            border: 1px solid #4caf50;
        }

        .badge-contested {
            background: #fff3e0;
            color: #e65100;
            border: 1px solid #ff9800;
        }

        .legend-text {
            font-size: 0.9em;
            color: #555;
            line-height: 1.4;
        }

        .chapter {
            margin-bottom: 80px;
        }

        .chapter-header {
            display: flex;
            align-items: flex-start;
            gap: 24px;
            margin-bottom: 40px;
            border-top: 3px solid #c9a876;
            padding-top: 30px;
        }

        .chapter-number {
            font-size: 4em;
            font-weight: 300;
            color: #c9a876;
            line-height: 0.85;
            flex-shrink: 0;
        }

        .chapter-info {
            flex: 1;
        }

        .chapter-title {
            font-size: 1.8em;
            color: #1a1a1a;
            font-weight: 400;
            margin-bottom: 12px;
        }

        .chapter-timecode {
            display: inline-block;
            font-size: 0.95em;
            color: white;
            background: #c9a876;
            padding: 6px 12px;
            border-radius: 3px;
            font-weight: 600;
            letter-spacing: 0.05em;
        }

        .block {
            margin-bottom: 50px;
            background: white;
            border-left: 4px solid #d4c5b9;
            padding: 28px;
            border-radius: 2px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.04);
        }

        .block-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 24px;
            gap: 20px;
        }

        .block-title {
            flex: 1;
        }

        .block-heading {
            font-size: 1.3em;
            color: #1a1a1a;
            font-weight: 500;
            line-height: 1.3;
        }

        .block-quote {
            font-size: 0.95em;
            color: #6b6b6b;
            font-style: italic;
            margin-top: 12px;
            padding-left: 16px;
            border-left: 2px solid #e0d5ca;
            line-height: 1.5;
        }

        .sources-list {
            list-style: none;
            margin-top: 20px;
        }

        .source-item {
            margin-bottom: 16px;
            padding: 16px;
            background: #faf7f2;
            border-radius: 3px;
            border: 1px solid #e8e0d6;
            transition: all 0.2s ease;
        }

        .source-item:hover {
            background: #f5f1eb;
            border-color: #d4c5b9;
            transform: translateX(4px);
        }

        .source-main {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 16px;
            margin-bottom: 8px;
        }

        .source-text {
            flex: 1;
        }

        .source-title {
            font-weight: 600;
            color: #1a1a1a;
            margin-bottom: 4px;
            font-size: 0.95em;
        }

        .source-citation {
            font-size: 0.85em;
            color: #7a7a7a;
            line-height: 1.4;
            font-style: italic;
        }

        .source-badge {
            flex-shrink: 0;
        }

        .source-link {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            font-size: 0.82em;
            color: #0066cc;
            text-decoration: none;
            padding: 6px 10px;
            background: rgba(0, 102, 204, 0.08);
            border-radius: 2px;
            transition: all 0.2s ease;
            margin-top: 8px;
        }

        .source-link:hover {
            background: rgba(0, 102, 204, 0.15);
            color: #0052a3;
        }

        .link-icon {
            font-size: 0.85em;
        }

        .toc {
            background: rgba(201, 168, 118, 0.1);
            border: 1px solid rgba(201, 168, 118, 0.2);
            border-radius: 4px;
            padding: 30px;
            margin-bottom: 60px;
        }

        .toc-header {
            font-size: 1.2em;
            font-weight: 600;
            color: #1a1a1a;
            margin-bottom: 16px;
        }

        .toc-list {
            list-style: none;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 12px;
        }

        .toc-item {
            border-left: 2px solid #c9a876;
            padding-left: 12px;
        }

        .toc-item a {
            color: #0066cc;
            text-decoration: none;
            font-size: 0.95em;
            display: block;
            padding: 4px 0;
        }

        .toc-item a:hover {
            text-decoration: underline;
        }

        .toc-time {
            font-size: 0.82em;
            color: #999;
            font-weight: 600;
        }

        .footnote {
            margin-top: 80px;
            padding-top: 40px;
            border-top: 2px solid #e8e0d6;
            font-size: 0.9em;
            color: #7a7a7a;
            line-height: 1.6;
        }

        .footnote-header {
            font-weight: 600;
            color: #1a1a1a;
            margin-bottom: 12px;
        }

        .footnote p {
            margin-bottom: 12px;
        }

        @media (max-width: 768px) {
            .container {
                padding: 24px 16px;
            }

            h1 {
                font-size: 2em;
            }

            .meta {
                flex-direction: column;
                gap: 12px;
            }

            .chapter-header {
                flex-direction: column;
                gap: 12px;
            }

            .chapter-number {
                font-size: 2.5em;
            }

            .chapter-title {
                font-size: 1.4em;
            }

            .block {
                padding: 20px;
            }

            .source-main {
                flex-direction: column;
            }

            .source-badge {
                margin-bottom: 8px;
            }

            .toc-list {
                grid-template-columns: 1fr;
            }
        }

        @print {
            body {
                background: white;
            }

            .block {
                page-break-inside: avoid;
                box-shadow: none;
            }

            a {
                color: #0066cc;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Who Was the Real Jesus?</h1>
            <p class="subtitle">Complete Sources by Chapter — Final Cut</p>
            <div class="meta">
                <span>📍 Episode: EP-1 · Sacred Pillar</span>
                <span>⏱ Runtime: ~37:57</span>
                <span>✍️ Format: Solo · Teleprompter</span>
            </div>
        </header>

        <div class="legend">
            <div class="legend-item">
                <span class="legend-badge badge-verified">Established</span>
                <span class="legend-text">Documented fact; the text or artifact says exactly this.</span>
            </div>
            <div class="legend-item">
                <span class="legend-badge badge-contested">Contested</span>
                <span class="legend-text">Real scholarship supports it, but scholars genuinely disagree.</span>
            </div>
            <div class="legend-item">
                <span class="legend-badge badge-contested">Reconstruction</span>
                <span class="legend-text">Scholarly interpretation; flag explicitly if needed on camera.</span>
            </div>
        </div>

        <div class="toc">
            <div class="toc-header">Quick Navigation</div>
            <ul class="toc-list">
                <li class="toc-item"><a href="#ch1"><span class="toc-time">1:44–3:32</span> Act 1: The Name They Changed First</a></li>
                <li class="toc-item"><a href="#ch2"><span class="toc-time">3:33–9:15</span> Act 2: Nazareth or Nazarene?</a></li>
                <li class="toc-item"><a href="#ch3"><span class="toc-time">9:16–12:59</span> Act 3: The Town That Leaves No Trace</a></li>
                <li class="toc-item"><a href="#ch4"><span class="toc-time">13:00–17:04</span> Act 4: The Heretics Who Kept His Name Alive</a></li>
                <li class="toc-item"><a href="#ch5"><span class="toc-time">17:05–21:23</span> Act 5: The Quran's Smoking Gun</a></li>
                <li class="toc-item"><a href="#ch6"><span class="toc-time">21:24–25:43</span> Act 6: The Heretics Who Became A Religion</a></li>
                <li class="toc-item"><a href="#ch7"><span class="toc-time">25:44–32:12</span> Act 7: No Altar, No Blood, No Flesh</a></li>
                <li class="toc-item"><a href="#ch8"><span class="toc-time">32:13–34:20</span> Act 8: The Babylonian Roots of Israel</a></li>
                <li class="toc-item"><a href="#ch9"><span class="toc-time">34:21–36:18</span> Act 9: Escape From Jerusalem</a></li>
                <li class="toc-item"><a href="#closing"><span class="toc-time">36:19–37:57</span> Closing Thoughts</a></li>
            </ul>
        </div>

        <!-- CHAPTER 1 -->
        <div class="chapter" id="ch1">
            <div class="chapter-header">
                <div class="chapter-number">1</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">The Name They Changed First</h2>
                    <span class="chapter-timecode">1:44 – 3:32</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">"He was not called Jesus. His name was Yeshua."</div>
                        <div class="block-quote">The Hebrew name, Greek translation, and what was lost in three languages.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Hebrew/Greek Lexicons</div>
                                <div class="source-citation">Standard reference: "Jesus" (Ἰησοῦς) from Hebrew Yeshua (ישוע), meaning "salvation" or "God delivers."</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">James Tabor, The Jesus Dynasty (2006)</div>
                                <div class="source-citation">Tabor, James D. <em>The Jesus Dynasty: The Hidden History of Jesus and His Family.</em> Simon & Schuster, 2006. Chapter 1: name etymology and messianic context.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="https://www.jamestabor.com/" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>James Tabor's Research</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Tacitus, Annals 15.44 (c. 116 AD)</div>
                                <div class="source-citation">"Christus, from whom the name had its origin, suffered the extreme penalty during the reign of Tiberius at the hands of one of our procurators, Pontius Pilatus." Earliest non-Christian governmental confirmation of the crucifixion.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://perseus.tufts.edu" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>Perseus Digital Library</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CHAPTER 2 -->
        <div class="chapter" id="ch2">
            <div class="chapter-header">
                <div class="chapter-number">2</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">Nazareth or Nazarene?</h2>
                    <span class="chapter-timecode">3:33 – 9:15</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">The Branch, Not the Town</div>
                        <div class="block-quote">Isaiah 11:1 — Netzer (branch). Nazoraios. The name that predates the geography.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Matthew Black, An Aramaic Approach to the Gospels and Acts (3rd ed., 1967)</div>
                                <div class="source-citation">Black, Matthew. Oxford University Press, 1967. Arguments on the difficulty of deriving Nazoraios from "Nazareth."</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Isaiah 11:1 (Old Testament)</div>
                                <div class="source-citation">"A shoot shall come up from the stump of Jesse — a branch (נצר netzer) shall grow from his roots." Messianic prophecy; the root behind Nazarene.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://sefaria.org" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>Sefaria.org — Hebrew Bible</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Matthew 2:23 (Gospel)</div>
                                <div class="source-citation">"And he went and lived in a city called Nazareth, so that what was spoken by the prophets might be fulfilled, that he would be called a Nazarene." — Matthew claims a prophecy but provides no biblical citation.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Interlinear</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Jerome, Commentary on Isaiah (late 4th century)</div>
                                <div class="source-citation">Jerome of Stridon. <em>Commentarius in Isaiam.</em> Identifies the Nazarene as deriving from netzer (branch), not the town.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Church Fathers</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Q Reconstruction (Robinson/Hoffmann/Kloppenborg, 2000)</div>
                                <div class="source-citation">Robinson, James M., Paul Hoffmann, and John S. Kloppenborg. <em>The Critical Edition of Q.</em> Fortress Press, 2000. Earliest form of the name in the Q source (pre-Gospel stratum).</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Epiphanius, Panarion 29.1.3–4 (c. 375 AD)</div>
                                <div class="source-citation">"The disciples came to be called 'Jessaeans'... before being called Christians at Antioch." After Jesse, the father of David. A messianic rather than geographic designation.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Acts 11:26 (New Testament)</div>
                                <div class="source-citation">"In Antioch the disciples were first called Christians." External label, not self-chosen; earlier names were Jessaeans, Nazarenes, Ebionites.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Acts 11:26</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CHAPTER 3 -->
        <div class="chapter" id="ch3">
            <div class="chapter-header">
                <div class="chapter-number">3</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">The Town That Leaves No Trace</h2>
                    <span class="chapter-timecode">9:16 – 12:59</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">Absent from Josephus, the Talmud, and the Scrolls</div>
                        <div class="block-quote">The oldest records name 45+ Galilean towns. Nazareth is not among them.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Josephus, Jewish War III & Life (c. 93–94 AD)</div>
                                <div class="source-citation">Josephus ben Matthias. Catalogs ~45 Galilean towns in detail; lives near the modern site; Nazareth is absent from both works.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://earlychristianwritings.com" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>Early Christian Writings</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Encyclopaedia Biblica (Cheyne, 1902)</div>
                                <div class="source-citation">Cheyne, T.K., ed. "Nazareth" entry. Frankly acknowledges we cannot positively assert a city called Nazareth existed in Jesus's day.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Julius Africanus via Eusebius, Church History 1.7.14 (c. 200 AD)</div>
                                <div class="source-citation">Julius Africanus. First external (non-biblical) mention of Nazara, ~200 AD. Still called Nazara, not Nazareth, and still using the zeta form.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Caesarea Priestly-Courses Inscription (~3rd–4th century)</div>
                                <div class="source-citation">Hebrew inscription recovered from Caesarea, listing priestly families resettled after 70 AD. Line mentions "course Hapizzez at Nazareth." Earliest physical non-Christian evidence of the place.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Eusebius, Life of Constantine 3.41–43 (c. 337–340 AD)</div>
                                <div class="source-citation">Eusebius of Caesarea. Constantine's mother Helena's pilgrimage (326–328 AD). Credited with founding churches at Bethlehem and Mount of Olives; Nazareth NOT mentioned here (later tradition from Ambrose, Rufinus).</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers/250042.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Full Text</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Joan Taylor, Christians and the Holy Places (1993)</div>
                                <div class="source-citation">Taylor, Joan. <em>Christians and the Holy Places: The Myth of Jewish-Christian Origins.</em> Oxford University Press, 1993. Scholarly basis for 4th-century holy-site construction wave.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CHAPTER 4 -->
        <div class="chapter" id="ch4">
            <div class="chapter-header">
                <div class="chapter-number">4</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">The Heretics Who Kept His Name Alive</h2>
                    <span class="chapter-timecode">13:00 – 17:04</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">The Sect That Survived in the Record</div>
                        <div class="block-quote">A sect called the Nazarenes. Named on a Roman court record, 57 AD.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Acts 24:5, 14 (New Testament)</div>
                                <div class="source-citation">"We have found this man a pest and a ringleader of the sect of the Nazarenes." Paul before Roman governor Felix, c. 57–59 AD. A documented, named movement.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com/acts/24-5.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Acts 24:5</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Epiphanius, Panarion 29 (c. 375 AD)</div>
                                <div class="source-citation">Describes Nazarenes as law-keeping descendants of original disciples. Hostile but documentary witness to their existence and lineage claims.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Dead Sea Scrolls, 1QS 9.11</div>
                                <div class="source-citation">Community Rule: "Until the coming of the Prophet and the Messiahs of Aaron and Israel." Two-Messiah expectation. Same world Yeshua emerged from.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://earlychristianwritings.com" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>Early Christian Writings</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">John Bergsma, Jesus and the Dead Sea Scrolls (2019)</div>
                                <div class="source-citation">Bergsma, John Sietze. <em>Jesus and the Dead Sea Scrolls.</em> Ignatius Press, 2019. Franciscan University scholar arguing direct connection between Qumran and early Church.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">James Tabor, Two Messiahs (1995 & jamestabor.com)</div>
                                <div class="source-citation">Tabor, James D., and Michael O. Wise. "4Q521 On Resurrection and the Synoptic Gospel Tradition." In <em>Qumran Questions.</em> Sheffield Academic Press, 1995. John the Baptist and Yeshua as twin-messiah figures matching Qumran expectation.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                        <a href="https://www.jamestabor.com/two-messiahs/" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>James Tabor's Site</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CHAPTER 5 -->
        <div class="chapter" id="ch5">
            <div class="chapter-header">
                <div class="chapter-number">5</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">The Quran's Smoking Gun</h2>
                    <span class="chapter-timecode">17:05 – 21:23</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">Three Hostile Traditions, One Name</div>
                        <div class="block-quote">Nasara (Arabic) · Notzrim (Hebrew) · Nazarenes (English). One root across three languages, six centuries of history.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Quran, Surahs 2:62; 3:52; 5:14; 5:69; 22:17 (+ 9 others)</div>
                                <div class="source-citation">The Quran uses Nasara (Nazarenes) 14 times for followers of Jesus. Never Masihiyyun (Christians from Messiah). 7th century AD.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">François de Blois, "Nasrani and Hanif" (2002)</div>
                                <div class="source-citation">de Blios, François. <em>Bulletin of the School of Oriental and African Studies</em> 65:1 (2002): 1–30. Linguistic chain: Greek Nazoraios → Syriac → Arabic Nasrani/Nasara. Phonological continuity across three languages.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Babylonian Talmud, Berakhot 28b–29a (Birkat haMinim)</div>
                                <div class="source-citation">The Blessing Against Heretics, compiled c. 90 AD. Cairo Genizah manuscripts preserve "Notzrim" (Nazarenes); most printed editions are censored and read only "heretics" (minim).</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://sefaria.org/Berakhot.28b" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>Sefaria — Talmud</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Jerome, Commentary on Isaiah & Letters (c. 342–420 AD)</div>
                                <div class="source-citation">Jerome of Stridon. Reports Jews cursing the Notzrim (Nazarenes) three times daily in synagogue prayer. Independent Christian witness to the name's use.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Jerome</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Epiphanius, Panarion 29.9 (c. 375 AD)</div>
                                <div class="source-citation">Corroborates: Jews cursed "the Nazarenes" by name, three times daily in synagogue.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Disputation of Paris (1240) & Talmud Burning (1242)</div>
                            <div class="source-citation">Chazan, Robert. <em>Daggers of Faith: Thirteenth-Century Christian Missionizing and Jewish Response.</em> University of California Press, 1989. Trial and burning of ~24 wagonloads of Talmud manuscripts; papal censorship orders (1554).</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Yeshivat Har Etzion (etzion.org.il)</div>
                                <div class="source-citation">Orthodox Jewish scholarship: "Even the name Jesus... emended or excised" from printed Talmud under Christian censorship. Acknowledges textual tampering.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://etzion.org.il" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>Yeshivat Har Etzion</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Talmud, Sanhedrin 43a (Munich 95 manuscript)</div>
                                <div class="source-citation">"On the eve of Passover they hung Yeshu ha-Notzri..." Uncensored text names him directly as "the Nazarene." Printed editions read blank.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Peter Schäfer, Jesus in the Talmud (2007)</div>
                                <div class="source-citation">Schäfer, Peter. <em>Jesus in the Talmud.</em> Princeton University Press, 2007. Analysis of Talmudic passages and their relation to the Christian Jesus.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">David Instone-Brewer, "The Talmudic Jesus" (2011)</div>
                                <div class="source-citation">Instone-Brewer, D. <em>Tyndale Bulletin</em> 62:1 (2011): 1–23. Munich 95 manuscript evidence and uncensored transmission.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CHAPTER 6 -->
        <div class="chapter" id="ch6">
            <div class="chapter-header">
                <div class="chapter-number">6</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">The Heretics Who Became A Religion</h2>
                    <span class="chapter-timecode">21:24 – 25:43</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">A Name Worn as a Badge Across Three Faiths</div>
                        <div class="block-quote">Hanif (pagan slur worn as identity). Zayd ibn Amr. Waraqa ibn Nawfal. The Dome of the Rock in Jerusalem, 692 AD.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Britannica, "Hanif"</div>
                                <div class="source-citation">Arab monotheist reformers in pre-Islamic Arabia. Etymology: Syriac hanpa (pagan/heathen) — a slur worn as identity, like "Nazarene."</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Sahih al-Bukhari 3826 & 5499</div>
                                <div class="source-citation">Zayd ibn Amr, refusing idol-meat in Mecca: "I do not eat anything which you slaughter in the name of your stone idols. I eat none but that on which God's name has been mentioned." Earliest Islamic hadith collection; anti-sacrifice monotheist.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Ibn Ishaq, Sira (Life of Muhammad, c. 768 AD)</div>
                                <div class="source-citation">Ibn Ishaq. <em>Sira Rasul Allah</em> [Life of the Messenger of God]. Waraqa ibn Nawfal: non-Trinitarian Christian, Khadijah's cousin, early influence on Muhammad.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Quran 2:142–144 (Qibla Change)</div>
                                <div class="source-citation">Quranic verses recording shift in prayer direction from Jerusalem to Mecca. Earliest believers prayed toward Jerusalem — same orientation as James and the Jerusalem community.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Dome of the Rock Inscriptions (692 CE / 72 AH)</div>
                                <div class="source-citation">Arabic inscriptions, Jerusalem. Built by Abd al-Malik (not Muhammad). Names Jesus as Prophet and Servant; denies Trinity; repeats "God has no companion" five times. Nazarene Christology in stone on the Temple Mount.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Hans-Joachim Schoeps, Jewish Christianity (1969)</div>
                                <div class="source-citation">Schoeps, Hans-Joachim. <em>Jewish Christianity: Factual Disputes in the Early Church.</em> Fortress Press, 1969. Theological parallels between Quranic Jesus and Ebionite/Nazarene Christology.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Shlomo Pines, "The Jewish Christians of the Early Centuries" (1968)</div>
                                <div class="source-citation">Pines, Shlomo. <em>The Israel Academy of Sciences and Humanities, Proceedings</em> 2 (1968): 1–74. Documents Ebionite/Nazarene theological parallels to the Quranic Jesus.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Dominique Bernard, Les disciples juifs de Jésus (2017)</div>
                                <div class="source-citation">Bernard, Dominique. <em>Les disciples juifs de Jésus du 1er siècle à Mahomet.</em> L'Harmattan, 2017. Ebionites and Nazarenes present in early Muslim communities.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CHAPTER 7 -->
        <div class="chapter" id="ch7">
            <div class="chapter-header">
                <div class="chapter-number">7</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">No Altar, No Blood, No Flesh</h2>
                    <span class="chapter-timecode">25:44 – 32:12</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">The Practice That Got Him Killed</div>
                        <div class="block-quote">The Temple cleansing. The collapse of the sacrificial-animal market. James the Just and the family practice.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Hosea 6:6 & Matthew 9:13, 12:7</div>
                                <div class="source-citation">"I desire mercy, not sacrifice." Quoted twice by Jesus against Temple authorities; originally Hosea 6:6 (8th century BCE).</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — All Versions</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Mark 11:15–18 (Temple Cleansing)</div>
                                <div class="source-citation">Jesus overturns tables of animal-sellers for sacrifice; chief priests immediately plot to destroy him. Trigger is the altar economy, not theology.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com/mark/11-15.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Mark 11:15</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Hegesippus in Eusebius, Church History 2.23</div>
                                <div class="source-citation">"He [James] was holy from his mother's womb; he drank no wine nor strong drink, nor did he eat flesh." 2nd-century historian Hegesippus, preserved in Eusebius. Lifelong vegetarianism and abstinence.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers/250102.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Church History 2.23</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Jerome, De Viris Illustribus 2 (late 4th century)</div>
                                <div class="source-citation">Jerome's biographical entry on James: "He did not eat flesh, nor drink wine." Corroborates Hegesippus.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers/29011.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Full Text</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Robert Eisenman, James the Brother of Jesus (1997)</div>
                                <div class="source-citation">Eisenman, Robert. <em>James the Brother of Jesus: The History and Legacy of the First Church.</em> Viking, 1997. "Whatever James was, so was Jesus" — inference from biography and family practice.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Old Syriac Gospels (Curetonian), Luke 21:34</div>
                                <div class="source-citation">Reads: "Do not let your hearts grow heavy with the EATING OF FLESH (ʾākaltā d-besrā) and the intoxication of wine." Greek version reads only "carousing" — the Syriac (Aramaic dialect) preserves a dietary prohibition the Greek obscures.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="https://archive.org/details/evangeliondameph00burk" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>F.C. Burkitt Edition (Archive.org)</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Pliny the Younger, Letters 10.96 (c. 112 AD)</div>
                                <div class="source-citation">Roman governor Pliny reports on Christian practice. Notes that the Temple sacrificial-animal market had "nearly no buyers" until his crackdown. Earliest secular/outside account of Christianity's market impact.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://earlychristianwritings.com/pliny.html" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>Early Christian Writings</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Isaiah 1:11–13, Jeremiah 7:22, Micah 6:6–8</div>
                                <div class="source-citation">Prophetic voices across centuries denying the necessity or desirability of sacrifice. "I do not delight in blood... Do justice, love kindness, walk humbly."</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — All Versions</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Amos 5:21, 5:25–26 (8th century BCE)</div>
                                <div class="source-citation">"I hate, I despise your feasts... Did you bring me sacrifices during forty years in the wilderness?" The claim: sacrifice was never commanded at the Exodus.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com/amos/5-21.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Amos 5</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Acts 7:42–43 (Stephen's Speech)</div>
                                <div class="source-citation">Stephen quotes Amos, accusing Israelites of carrying Moloch and Remphan (Saturn) in the wilderness — Mesopotamian astral deities, not the God of Abraham. Witnesses stone him for it.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com/acts/7-42.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Acts 7:42</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">2 Maccabees 6:18–20 (Maccabean Martyrs, 2nd century BCE)</div>
                                <div class="source-citation">Jewish martyrs die rather than eat pork under kosher law. Demonstrates that diet can be a line worth dying for — precedent for the later Nazarene/Ebionite movement.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com/2_maccabees/6-18.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — 2 Maccabees 6</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Bernard Gui, Inquisitor's Manual (c. 1261–1331)</div>
                                <div class="source-citation">Gui, Bernard. <em>Liber Sententiarum Inquisitionis.</em> Documents Cathar Perfecti as vegetarian; refusing meat marked them for Inquisitorial persecution. Same pattern: dietary practice as marker of heresy.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">R.I. Moore, The War on Heresy (2012)</div>
                                <div class="source-citation">Moore, R.I. <em>The War on Heresy: Faith and Hatred in Christendom.</em> Harvard University Press, 2012. Cathar suppression and dietary practice as theological marker.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CHAPTER 8 -->
        <div class="chapter" id="ch8">
            <div class="chapter-header">
                <div class="chapter-number">8</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">The Babylonian Roots of Israel</h2>
                    <span class="chapter-timecode">32:13 – 34:20</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">Why the Altar Was Never Commanded</div>
                        <div class="block-quote">Genesis 22. Abraham from Ur. The knife raised and lowered. The ram in the thicket — and no divine command for it.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Genesis 22 (Abraham and Isaac)</div>
                                <div class="source-citation">God commands sacrifice of Isaac (v.2), withdraws at the last moment (v.12). Abraham sees ram in thicket and offers it (v.13). No second command for the ram — only Abraham's ingrained cultural habit.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com/genesis/22.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Genesis 22</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Genesis 11:28, 31 & Leonard Woolley, Ur excavation (1927)</div>
                                <div class="source-citation">Abraham born in Ur of the Chaldees, southern Mesopotamia. Center of moon-god Sin worship; animal sacrifice universal across ancient Near East by 3000 BCE.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Exodus 12:38 (The Mixed Multitude)</div>
                                <div class="source-citation">"A mixed multitude (erev rav) also went up with them" from Egypt. Non-Israelites carrying Mesopotamian and Egyptian religious customs into the wilderness tradition.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com/exodus/12-38.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Exodus 12:38</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Talmud, Zohar, Rashi on Exodus 32 (Golden Calf)</div>
                                <div class="source-citation">Exodus 32:1–4 records the golden calf incident. Rabbinic tradition identifies the erev rav (mixed multitude) as instigators. Apis bull-god from Egypt, not Israelite theology.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Amos 5:26 & Acts 7:42–43</div>
                                <div class="source-citation">Amos claims Israel carried "Moloch and Chiun (Saturn)" in the wilderness — Mesopotamian astral deities. Stephen quotes Amos before the Sanhedrin, accusing Israel of worshipping "Remphan" (Saturn). Gets stoned for it.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://biblehub.com/amos/5-26.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>BibleHub — Amos 5:26</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CHAPTER 9 -->
        <div class="chapter" id="ch9">
            <div class="chapter-header">
                <div class="chapter-number">9</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">Escape From Jerusalem</h2>
                    <span class="chapter-timecode">34:21 – 36:18</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">The Flight to Pella & The Suppression</div>
                        <div class="block-quote">The Jerusalem church was told to leave. 70 AD. They went east. They never came back.</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Irenaeus, Against Heresies 1.26.2 (c. 180 AD)</div>
                                <div class="source-citation">Irenaeus of Lyon. Within 100 years of crucifixion, the Catholic church declares Jesus's own sect (the Ebionites) heretical. Their crime: rejecting Paul, keeping Torah, using Hebrew Matthew, believing Jesus was a man (not pre-existing divine).</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers/0103126.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Full Text</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Council of Rome / Pope Damasus (4th century)</div>
                                <div class="source-citation">Imperial church legislates against "Judaizing" Christians — criminalizing Torah observance, Hebrew practice. Property seizure, eventually death penalty.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Codex Theodosianus 16.8 (Theodosius)</div>
                                <div class="source-citation">Imperial Roman legal code regulating "Judaizing" Christian practice. See Linder, <em>The Jews in Roman Imperial Legislation</em> (1987).</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Jerome, Epistula 112.13 (late 4th century)</div>
                                <div class="source-citation">Jerome describes Hebrew Christians "who want to be both Jews and Christians — neither one nor the other" — still keeping the Law, still practicing what James practiced, still refusing Gentile doctrine.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers/3001112.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Letter 112</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Eusebius, Church History 3.5.3 (c. 320 AD)</div>
                                <div class="source-citation">"The people of the church in Jerusalem were commanded by a divine oracle given by revelation before the war to depart and settle in a city of Perea called Pella." 70 AD flight before the Roman siege.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers/250103.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Church History 3.5</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Epiphanius, Panarion 29.7–8 (c. 375 AD)</div>
                                <div class="source-citation">Independent confirmation: "All the disciples settled in Pella after their remove from Jerusalem — Christ having told them to abandon Jerusalem." Describes them as descendants of original disciples, law-keepers, still in the Trans-Jordan.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Eusebius, Church History 3.11, 3.32</div>
                                <div class="source-citation">Simeon (Simon), cousin of Jesus, succeeds James as leader of Jerusalem church after exile. Martyred under Trajan around 107 AD. Blood succession: Jesus → James → Simeon → the Desposyni.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                        <a href="http://newadvent.org/fathers/250103.htm" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>New Advent — Church History 3</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">James Tabor, The Jesus Dynasty (2006)</div>
                                <div class="source-citation">Tabor, James D. Simon & Schuster, 2006. "The Jesus Dynasty" thesis: family succession from Jesus to James to Simeon through the Desposyni, documented in hostile and friendly sources.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-contested">Contested</span>
                            </div>
                        </div>
                        <a href="https://www.jamestabor.com/" class="source-link">
                            <span class="link-icon">🔗</span>
                            <span>James Tabor's Research</span>
                        </a>
                    </li>
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">Julius Africanus, Epistle to Aristides (via Eusebius, HE 1.7)</div>
                                <div class="source-citation">Julius Africanus. Names "Desposyni" (those who belong to the Master) — blood relatives of Jesus continuing to lead communities and being tracked by emperors into the 2nd–3rd centuries.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </div>

        <!-- CLOSING -->
        <div class="chapter" id="closing">
            <div class="chapter-header">
                <div class="chapter-number">✕</div>
                <div class="chapter-info">
                    <h2 class="chapter-title">Closing Thoughts</h2>
                    <span class="chapter-timecode">36:19 – 37:57</span>
                </div>
            </div>
            <div class="block">
                <div class="block-header">
                    <div class="block-title">
                        <div class="block-heading">The Name That Survived Erasure</div>
                        <div class="block-quote">"You cannot erase a name when it's been written in that many places, by that many enemies, across that many centuries."</div>
                    </div>
                </div>
                <ul class="sources-list">
                    <li class="source-item">
                        <div class="source-main">
                            <div class="source-text">
                                <div class="source-title">The Synthesis: Talmud, Quran, Syriac Christianity</div>
                                <div class="source-citation">Notzrim (Hebrew curse). Nasara (Quranic name, 14 times). Nasrani (Syrian Christian self-designation, India). One root across three languages, three hostile traditions, six centuries. All sources cited above.</div>
                            </div>
                            <div class="source-badge">
                                <span class="legend-badge badge-verified">Established</span>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </div>

        <div class="footnote">
            <div class="footnote-header">Document Notes</div>
            <p><strong>Verification Tiers:</strong> Every source labeled <span class="legend-badge badge-verified">Established</span> (documented facts), <span class="legend-badge badge-contested">Contested</span> (real scholarship with genuine disagreement), or <span class="legend-badge badge-contested">Reconstruction</span> (scholarly interpretation requiring caveats). </p>
            <p><strong>Primary Sources:</strong> Free libraries used: <a href="http://earlychristianwritings.com">earlychristianwritings.com</a>, <a href="http://newadvent.org/fathers">newadvent.org/fathers</a>, <a href="http://sefaria.org">sefaria.org</a>, <a href="http://perseus.tufts.edu">perseus.tufts.edu</a>, <a href="http://biblehub.com">biblehub.com</a> (interlinear).</p>
            <p><strong>Chapter Structure & Timecodes:</strong> Reorganized by final edit with YouTube-ready timecodes. All sources mapped to final chapter sequence. Total runtime: ~37:57. Everything traces to a primary source with direct URLs where available.</p>
            <p><strong>Compiled:</strong> July 2026 from Florez Media Production Tracker (Notion MCP Integration). Ready for public Substack release or editorial reference.</p>
        </div>

    </div>
</body>
</html>
