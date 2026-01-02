# wedding-invitation-lucky-satya[index.html](https://github.com/user-attachments/files/24410456/index.html)
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="2685.3">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; min-height: 14.0px}
  </style>
</head>
<body>
<p class="p1">&lt;!DOCTYPE html&gt;</p>
<p class="p1">&lt;html lang="en"&gt;</p>
<p class="p1">&lt;head&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;meta charset="UTF-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;title&gt;Lucky &amp; Satya: Online Exhibition&lt;/title&gt;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;link rel="preconnect" href="https://fonts.googleapis.com"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;link rel="preconnect" href="https://fonts.gstatic.com" crossorigin&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400&amp;family=Playfair+Display:ital,wght@0,400;0,500;1,400&amp;display=swap" rel="stylesheet"&gt;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;style&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>:root {</p>
<p class="p1"><span class="Apple-converted-space">            </span>--bg-color: #F9F7F2;<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>--text-main: #3D3935;<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>--text-muted: #7A746E;<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>--accent: #A69080;<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>--border: rgba(61, 57, 53, 0.1);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>* { margin: 0; padding: 0; box-sizing: border-box; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>html { scroll-behavior: smooth; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>body {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background-color: var(--bg-color);</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: var(--text-main);</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-family: 'Inter', sans-serif;</p>
<p class="p1"><span class="Apple-converted-space">            </span>line-height: 1.6;</p>
<p class="p1"><span class="Apple-converted-space">            </span>overflow-x: hidden;</p>
<p class="p1"><span class="Apple-converted-space">            </span>-webkit-font-smoothing: antialiased;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>h1, h2, h3, .serif { font-family: 'Playfair Display', serif; font-weight: 400; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.container { max-width: 800px; margin: 0 auto; padding: 0 2rem; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>section {</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 100px 0;</p>
<p class="p1"><span class="Apple-converted-space">            </span>opacity: 0;</p>
<p class="p1"><span class="Apple-converted-space">            </span>transform: translateY(30px);</p>
<p class="p1"><span class="Apple-converted-space">            </span>transition: all 1.2s cubic-bezier(0.22, 1, 0.36, 1);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>section.visible { opacity: 1; transform: translateY(0); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>/* Audio Toggle */</p>
<p class="p1"><span class="Apple-converted-space">        </span>#music-control {</p>
<p class="p1"><span class="Apple-converted-space">            </span>position: fixed;</p>
<p class="p1"><span class="Apple-converted-space">            </span>bottom: 2rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>right: 2rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>z-index: 100;</p>
<p class="p1"><span class="Apple-converted-space">            </span>cursor: pointer;</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--bg-color);</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 1px solid var(--text-main);</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 12px 18px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 0.65rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>letter-spacing: 2px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>text-transform: uppercase;</p>
<p class="p1"><span class="Apple-converted-space">            </span>transition: all 0.3s ease;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>#music-control:hover { background: var(--text-main); color: var(--bg-color); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>/* 1. Opening Wall */</p>
<p class="p1"><span class="Apple-converted-space">        </span>.hero {</p>
<p class="p1"><span class="Apple-converted-space">            </span>height: 100vh;</p>
<p class="p1"><span class="Apple-converted-space">            </span>display: flex;</p>
<p class="p1"><span class="Apple-converted-space">            </span>flex-direction: column;</p>
<p class="p1"><span class="Apple-converted-space">            </span>justify-content: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>align-items: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>text-align: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-bottom: 1px solid var(--border);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.hero h1 { font-size: 3rem; margin-bottom: 1.5rem; letter-spacing: -1px; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.hero p { font-size: 0.8rem; letter-spacing: 4px; text-transform: uppercase; color: var(--text-muted); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>/* 2. Curatorial Note */</p>
<p class="p1"><span class="Apple-converted-space">        </span>.curatorial-note { text-align: center; max-width: 600px; margin: 0 auto; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.curatorial-note h2 { font-style: italic; margin-bottom: 2.5rem; font-size: 2rem; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.curatorial-note p { font-size: 1.1rem; color: var(--text-main); margin-bottom: 2rem; font-weight: 300; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>/* 3. Works on Display (Gallery) */</p>
<p class="p1"><span class="Apple-converted-space">        </span>.work-item { margin-bottom: 180px; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.work-image {</p>
<p class="p1"><span class="Apple-converted-space">            </span>width: 100%;</p>
<p class="p1"><span class="Apple-converted-space">            </span>height: 500px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>background-color: #e5e5e5;</p>
<p class="p1"><span class="Apple-converted-space">            </span>object-fit: cover;</p>
<p class="p1"><span class="Apple-converted-space">            </span>filter: grayscale(100%);</p>
<p class="p1"><span class="Apple-converted-space">            </span>transition: filter 0.8s ease;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-bottom: 2rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 1px solid var(--border);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>.work-item:hover .work-image { filter: grayscale(0%); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.work-label { border-left: 1px solid var(--text-main); padding-left: 1.5rem; max-width: 450px; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.work-label h3 { font-size: 1.4rem; margin-bottom: 0.7rem; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.work-label p { font-size: 0.9rem; color: var(--text-muted); font-weight: 300; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>/* 4. The Moment */</p>
<p class="p1"><span class="Apple-converted-space">        </span>.moment { background-color: #F2EFE9; text-align: center; padding: 140px 20px; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.countdown { display: flex; justify-content: center; gap: 2.5rem; margin: 3.5rem 0; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.countdown-item span { display: block; font-size: 2rem; font-family: 'Playfair Display', serif; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.countdown-item label { font-size: 0.6rem; text-transform: uppercase; letter-spacing: 2px; color: var(--text-muted); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.event-card { margin: 4rem auto; max-width: 500px; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.event-card h3 { font-size: 2.2rem; margin-bottom: 1rem; }</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>.btn {</p>
<p class="p1"><span class="Apple-converted-space">            </span>display: inline-block;</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 1.2rem 2.5rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 1px solid var(--text-main);</p>
<p class="p1"><span class="Apple-converted-space">            </span>text-decoration: none;</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: var(--text-main);</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 0.75rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>letter-spacing: 2px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>text-transform: uppercase;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-top: 2rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>transition: all 0.4s ease;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>.btn:hover { background-color: var(--text-main); color: var(--bg-color); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>/* 5. RSVP &amp; Family */</p>
<p class="p1"><span class="Apple-converted-space">        </span>.attendance { text-align: center; padding: 150px 0; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>.family-note { margin-top: 120px; font-size: 0.85rem; color: var(--text-muted); line-height: 2; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>footer {</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 60px 0;</p>
<p class="p1"><span class="Apple-converted-space">            </span>text-align: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 0.7rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>letter-spacing: 2px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-top: 1px solid var(--border);</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: var(--text-muted);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>@media (max-width: 600px) {</p>
<p class="p1"><span class="Apple-converted-space">            </span>.hero h1 { font-size: 2.2rem; }</p>
<p class="p1"><span class="Apple-converted-space">            </span>.work-image { height: 350px; }</p>
<p class="p1"><span class="Apple-converted-space">            </span>.countdown { gap: 1.2rem; }</p>
<p class="p1"><span class="Apple-converted-space">            </span>.curatorial-note h2 { font-size: 1.6rem; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/style&gt;</p>
<p class="p1">&lt;/head&gt;</p>
<p class="p1">&lt;body&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;audio id="bgm" loop&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;source src="https://www.bensound.com/bensound-music/bensound-betterdays.mp3" type="audio/mpeg"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/audio&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;button id="music-control" onclick="toggleMusic()"&gt;Play Sound&lt;/button&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="hero visible"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;p&gt;A Curated Phase of Life&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;h1&gt;Lucky &amp; Satya&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;p&gt;21 . 05 . 2026 — Surabaya&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;section class="curatorial-note"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h2&gt;Curatorial Note&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p&gt;Pernikahan bukanlah sebuah muara, melainkan salah satu fase transisi dalam proses panjang menjadi manusia.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p&gt;Melalui pameran singkat ini, kami mengundang Anda untuk menyaksikan satu titik dari garis panjang yang sedang kami tarik bersama.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;section class="gallery"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="work-item"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;img src="https://images.unsplash.com/photo-1518131359073-ad293c3f90c9?auto=format&amp;fit=crop&amp;w=1200" alt="Roots" class="work-image"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="work-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;h3&gt;I. Roots&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;p&gt;Dua latar belakang yang berbeda, tumbuh dalam diam, mencari arah masing-masing sebelum akhirnya bersinggungan di satu frekuensi yang tenang.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="work-item"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;img src="https://images.unsplash.com/photo-1494438639946-1ebd1d20bf85?auto=format&amp;fit=crop&amp;w=1200" alt="Convergence" class="work-image"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="work-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;h3&gt;II. Convergence&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;p&gt;Pertemuan bukan tentang peleburan identitas, melainkan tentang ruang baru yang sengaja diciptakan untuk tumbuh berdampingan tanpa saling menghalangi cahaya.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="work-item"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;img src="https://images.unsplash.com/photo-1526047932273-341f2a7631f9?auto=format&amp;fit=crop&amp;w=1200" alt="Becoming" class="work-image"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="work-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;h3&gt;III. Becoming&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;p&gt;Langkah awal menuju fase berikutnya. Sebuah komitmen yang tidak terburu-buru, melainkan penuh kesadaran dan penerimaan atas segala proses.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/section&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="moment"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h2 class="serif"&gt;The Moment&lt;/h2&gt;</p>
<p class="p2"><span class="Apple-converted-space">            </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="countdown" class="countdown"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="countdown-item"&gt;&lt;span id="days"&gt;00&lt;/span&gt;&lt;label&gt;Days&lt;/label&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="countdown-item"&gt;&lt;span id="hours"&gt;00&lt;/span&gt;&lt;label&gt;Hours&lt;/label&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="countdown-item"&gt;&lt;span id="mins"&gt;00&lt;/span&gt;&lt;label&gt;Mins&lt;/label&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="countdown-item"&gt;&lt;span id="secs"&gt;00&lt;/span&gt;&lt;label&gt;Secs&lt;/label&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="event-card"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p style="text-transform: uppercase; letter-spacing: 3px; font-size: 0.7rem; margin-bottom: 15px;"&gt;Ceremony &amp; Reception&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;h3&gt;Thursday, May 21st, 2026&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p&gt;10:00 WIB — Finish&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p style="margin-top: 10px; font-style: italic;"&gt;The Heritage Gallery, Surabaya&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;a href="https://maps.google.com" target="_blank" class="btn"&gt;View Map Location&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;section class="attendance"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h2 class="serif"&gt;Presence&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p style="margin-top: 20px; font-weight: 300;"&gt;Your presence is the only gift we require. Let us know if you can join this phase.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;a href="https://wa.me/628123456789?text=I%20will%20attend%20the%20exhibition" class="btn"&gt;Confirm Attendance&lt;/a&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="family-note"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p&gt;Turut Mengundang:&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p style="color: var(--text-main); font-weight: 400;"&gt;Keluarga Besar Bpk. Ika &amp; Ibu Fidyani&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p style="color: var(--text-main); font-weight: 400;"&gt;Keluarga Besar Bpk. Satya &amp; Ibu Oktabrian&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;section class="curatorial-note" style="padding-bottom: 100px;"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p style="font-style: italic; opacity: 0.7;"&gt;"Sebab hidup adalah pameran dari keputusan-keputusan kecil yang kita ambil setiap hari."&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p style="font-size: 0.7rem; margin-top: 3rem; letter-spacing: 2px; text-transform: uppercase;"&gt;Until the day arrives.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/section&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;footer&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>LUCKY &amp; SATYA — 2026</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/footer&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;script&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>// 1. Reveal Animation on Scroll</p>
<p class="p1"><span class="Apple-converted-space">        </span>const observerOptions = { threshold: 0.15 };</p>
<p class="p1"><span class="Apple-converted-space">        </span>const observer = new IntersectionObserver((entries) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>entries.forEach(entry =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">                </span>if (entry.isIntersecting) {</p>
<p class="p1"><span class="Apple-converted-space">                    </span>entry.target.classList.add('visible');</p>
<p class="p1"><span class="Apple-converted-space">                </span>}</p>
<p class="p1"><span class="Apple-converted-space">            </span>});</p>
<p class="p1"><span class="Apple-converted-space">        </span>}, observerOptions);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>document.querySelectorAll('section').forEach(section =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>observer.observe(section);</p>
<p class="p1"><span class="Apple-converted-space">        </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// 2. Countdown Logic</p>
<p class="p1"><span class="Apple-converted-space">        </span>const targetDate = new Date("May 21, 2026 10:00:00").getTime();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const updateTimer = () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>const now = new Date().getTime();</p>
<p class="p1"><span class="Apple-converted-space">            </span>const diff = targetDate - now;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">            </span>if (diff &lt;= 0) {</p>
<p class="p1"><span class="Apple-converted-space">                </span>document.getElementById("countdown").innerHTML = "The Exhibition has started.";</p>
<p class="p1"><span class="Apple-converted-space">                </span>return;</p>
<p class="p1"><span class="Apple-converted-space">            </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">            </span>document.getElementById("days").innerText = Math.floor(diff / (1000 * 60 * 60 * 24));</p>
<p class="p1"><span class="Apple-converted-space">            </span>document.getElementById("hours").innerText = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));</p>
<p class="p1"><span class="Apple-converted-space">            </span>document.getElementById("mins").innerText = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));</p>
<p class="p1"><span class="Apple-converted-space">            </span>document.getElementById("secs").innerText = Math.floor((diff % (1000 * 60)) / 1000);</p>
<p class="p1"><span class="Apple-converted-space">        </span>};</p>
<p class="p1"><span class="Apple-converted-space">        </span>setInterval(updateTimer, 1000);</p>
<p class="p1"><span class="Apple-converted-space">        </span>updateTimer();</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// 3. Audio Control</p>
<p class="p1"><span class="Apple-converted-space">        </span>const audio = document.getElementById('bgm');</p>
<p class="p1"><span class="Apple-converted-space">        </span>const musicBtn = document.getElementById('music-control');</p>
<p class="p1"><span class="Apple-converted-space">        </span>function toggleMusic() {</p>
<p class="p1"><span class="Apple-converted-space">            </span>if (audio.paused) {</p>
<p class="p1"><span class="Apple-converted-space">                </span>audio.play();</p>
<p class="p1"><span class="Apple-converted-space">                </span>musicBtn.innerText = "Pause Sound";</p>
<p class="p1"><span class="Apple-converted-space">            </span>} else {</p>
<p class="p1"><span class="Apple-converted-space">                </span>audio.pause();</p>
<p class="p1"><span class="Apple-converted-space">                </span>musicBtn.innerText = "Play Sound";</p>
<p class="p1"><span class="Apple-converted-space">            </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/script&gt;</p>
<p class="p1">&lt;/body&gt;</p>
<p class="p1">&lt;/html&gt;</p>
</body>
</html>
