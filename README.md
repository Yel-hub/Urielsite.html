<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#101411">
<title>EmTech_Zara_ErianneUrielLegaspi | The Art of Chess</title>
<style>
:root{--bg:#101411;--panel:#19211b;--gold:#d6b36a;--cream:#f1e9d8;--muted:#a9b0a7;--line:#354239}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:var(--bg);color:var(--cream);font-family:Georgia,'Times New Roman',serif}a{color:inherit;text-decoration:none}
nav{position:sticky;top:0;z-index:5;background:#101411ed;backdrop-filter:blur(12px);border-bottom:1px solid var(--line);display:flex;justify-content:space-between;align-items:center;padding:17px 7%;font-family:Arial,sans-serif}
.brand{font-size:13px;letter-spacing:2px;color:var(--gold);font-weight:700}.links{display:flex;gap:20px;font-size:12px;letter-spacing:1px;text-transform:uppercase;color:var(--muted)}.links a:hover{color:var(--gold)}
.hero{min-height:85vh;padding:90px 8%;display:grid;grid-template-columns:1.1fr .9fr;gap:55px;align-items:center;background:radial-gradient(ellipse at 80% 45%,#26372a 0%,transparent 48%),linear-gradient(135deg,#101411,#151d17)}
.eyebrow{color:var(--gold);letter-spacing:4px;text-transform:uppercase;font:11px Arial,sans-serif}.hero h1{font-size:clamp(42px,6vw,78px);line-height:.98;margin:22px 0}.hero h1 span{color:var(--gold);font-style:italic}.hero p{max-width:540px;color:var(--muted);font:15px/1.8 Arial,sans-serif}.cta{display:inline-block;margin-top:24px;padding:14px 22px;background:var(--gold);color:#171a14;font:700 11px Arial,sans-serif;letter-spacing:1.5px;text-transform:uppercase}.cta:hover{background:#efcf8a}
.board-wrap{max-width:480px;margin:auto;padding:15px;background:#d6b36a;box-shadow:0 25px 80px #0008;transform:rotate(1.5deg)}.board{display:grid;grid-template-columns:repeat(8,1fr);aspect-ratio:1}.sq{display:grid;place-items:center;font-size:clamp(22px,4.5vw,45px);line-height:1}.sq:nth-child(16n+1),.sq:nth-child(16n+3),.sq:nth-child(16n+5),.sq:nth-child(16n+7),.sq:nth-child(16n+10),.sq:nth-child(16n+12),.sq:nth-child(16n+14),.sq:nth-child(16n+16){background:#eadfc9;color:#1c211c}.sq:nth-child(16n+2),.sq:nth-child(16n+4),.sq:nth-child(16n+6),.sq:nth-child(16n+8),.sq:nth-child(16n+9),.sq:nth-child(16n+11),.sq:nth-child(16n+13),.sq:nth-child(16n+15){background:#71856f;color:#f7f0df}
section{padding:85px 8%}.section-head{text-align:center;margin-bottom:45px}.section-head small{color:var(--gold);font:11px Arial,sans-serif;letter-spacing:3px;text-transform:uppercase}.section-head h2{font-size:clamp(30px,4vw,46px);margin:13px 0}.section-head p{font:14px/1.7 Arial,sans-serif;color:var(--muted);max-width:620px;margin:auto}
.about{background:#151c17}.about-grid{display:grid;grid-template-columns:1fr 1fr;gap:45px;align-items:center}.quote{font-size:clamp(25px,3vw,38px);line-height:1.25;color:var(--gold);font-style:italic}.about-copy{font:15px/1.9 Arial,sans-serif;color:var(--muted)}.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}.card{background:var(--panel);border:1px solid var(--line);padding:27px;min-height:220px;transition:.25s}.card:hover{transform:translateY(-6px);border-color:var(--gold)}.card{cursor:pointer}.card:focus-visible{outline:2px solid var(--gold);outline-offset:4px}.portfolio{background:#151c17}.portfolio-intro{font:14px/1.8 Arial,sans-serif;color:var(--muted);max-width:680px;margin:-20px auto 35px;text-align:center}.task-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:18px}.task-card{background:var(--panel);border:1px solid var(--line);padding:24px;position:relative}.task-card h3{font-size:21px;margin:8px 0}.task-card p{font:13px/1.7 Arial,sans-serif;color:var(--muted)}.task-number{font:11px Arial,sans-serif;letter-spacing:2px;color:var(--gold)}.task-card input[type=file]{display:block;width:100%;margin-top:16px;padding:12px;border:1px dashed #71856f;border-radius:6px;background:#111a14;color:var(--muted);font:12px Arial,sans-serif;cursor:pointer}.task-card input[type=file]::file-selector-button{border:0;background:var(--gold);color:#171a14;padding:9px 12px;margin-right:10px;border-radius:3px;font-weight:700;cursor:pointer}.file-entry{padding:7px 0;border-bottom:1px solid var(--line)}.file-entry:last-child{border-bottom:0}.file-meta{color:var(--muted);font-size:11px}.file-list{margin-top:10px;font:12px/1.6 Arial,sans-serif;color:var(--gold);overflow-wrap:anywhere}.portfolio-note{margin-top:25px;padding:17px;border:1px dashed #71856f;color:var(--muted);font:12px/1.7 Arial,sans-serif}.card .more{display:none;margin-top:12px;padding-top:12px;border-top:1px solid var(--line);color:var(--gold)}.card.open .more{display:block}.sq{cursor:pointer;transition:filter .15s}.sq.selected{outline:3px solid #d6b36a;outline-offset:-4px;filter:brightness(1.2)}.piece{font-size:42px;color:var(--gold)}.card h3{font-size:22px;margin:17px 0 9px}.card p{font:13px/1.8 Arial,sans-serif;color:var(--muted)}
.banner{background:linear-gradient(110deg,#26372a,#18221b);text-align:center}.banner h2{font-size:clamp(30px,4vw,48px);margin:0 0 15px}.banner p{font:14px/1.8 Arial,sans-serif;color:#c2c9be;max-width:650px;margin:0 auto}
footer{padding:28px 8%;border-top:1px solid var(--line);display:flex;justify-content:space-between;gap:15px;flex-wrap:wrap;color:var(--muted);font:11px Arial,sans-serif;letter-spacing:1px}
@media(max-width:800px){.hero{grid-template-columns:1fr;padding-top:65px}.board-wrap{max-width:390px;width:100%}.about-grid{grid-template-columns:1fr}.cards{grid-template-columns:1fr}.task-grid{grid-template-columns:1fr}.links{gap:12px;font-size:10px}.brand{font-size:10px}}
@media(max-width:480px){nav{padding:15px 5%}.links{gap:9px}.links a{font-size:9px}.links a:nth-child(2){display:none}.hero,section{padding-left:6%;padding-right:6%}.hero h1{font-size:47px}}
</style>
</head>
<body>
<nav><a class="brand" href="#">Z.E.L. ♛</a><div class="links"><a href="#about">About</a><a href="#pieces">The Pieces</a><a href="#portfolio">Portfolio</a><a href="#mindset">Mindset</a></div></nav>
<header class="hero">
 <div><div class="eyebrow">EmTech • Chess Edition</div><h1>Every move<br>tells a <span>story.</span></h1>
 <p>Welcome to a world of strategy, patience, and creativity. Explore the timeless game of chess through its pieces, principles, and the mindset behind every great move.</p>
 <a class="cta" href="#about">Explore the board ↓</a></div>
 <div class="board-wrap"><div class="board" id="chessboard" aria-label="Interactive decorative chessboard">
  <span class="sq">♜</span><span class="sq">♞</span><span class="sq">♝</span><span class="sq">♛</span><span class="sq">♚</span><span class="sq">♝</span><span class="sq">♞</span><span class="sq">♜</span>
  <span class="sq">♟</span><span class="sq">♟</span><span class="sq">♟</span><span class="sq">♟</span><span class="sq">♟</span><span class="sq">♟</span><span class="sq">♟</span><span class="sq">♟</span>
  <span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span>
  <span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span>
  <span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span>
  <span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span><span class="sq"></span>
  <span class="sq">♙</span><span class="sq">♙</span><span class="sq">♙</span><span class="sq">♙</span><span class="sq">♙</span><span class="sq">♙</span><span class="sq">♙</span><span class="sq">♙</span>
  <span class="sq">♖</span><span class="sq">♘</span><span class="sq">♗</span><span class="sq">♕</span><span class="sq">♔</span><span class="sq">♗</span><span class="sq">♘</span><span class="sq">♖</span>
 </div></div>
</header>
<section class="about" id="about"><div class="section-head"><small>01 / The Game</small><h2>More Than Just a Game</h2></div><div class="about-grid"><div class="quote">“Chess is the art of thinking ahead, staying calm, and making every move count.”</div><div class="about-copy">Chess is a battle of ideas played on 64 squares. Every decision has a purpose: protect your pieces, control important squares, recognize patterns, and plan for what comes next. It rewards focus, patience, discipline, and imagination.</div></div></section>
<section id="pieces"><div class="section-head"><small>02 / Know Your Army</small><h2>The Pieces & Their Power</h2><p>Each chess piece has a unique way of moving—and a unique role in your strategy.</p></div><div class="cards">
 <article class="card" tabindex="0" role="button" aria-expanded="false"><div class="piece">♔</div><h3>The King</h3><p>The most important piece. Protect your king and avoid checkmate at all costs.</p><div class="more">Moves one square in any direction. Castling is a special move shared with a rook.</div></article>
 <article class="card" tabindex="0" role="button" aria-expanded="false"><div class="piece">♕</div><h3>The Queen</h3><p>The most powerful piece, combining the movement of a rook and a bishop.</p><div class="more">Moves any number of squares horizontally, vertically, or diagonally.</div></article>
 <article class="card" tabindex="0" role="button" aria-expanded="false"><div class="piece">♖</div><h3>The Rook</h3><p>Moves horizontally and vertically. Rooks become especially powerful on open files.</p><div class="more">Moves any number of empty squares along a rank or file.</div></article>
 <article class="card" tabindex="0" role="button" aria-expanded="false"><div class="piece">♗</div><h3>The Bishop</h3><p>Moves diagonally and controls long paths across the board.</p><div class="more">Moves any number of empty squares diagonally and stays on the same square color.</div></article>
 <article class="card" tabindex="0" role="button" aria-expanded="false"><div class="piece">♘</div><h3>The Knight</h3><p>Moves in an L-shape and can jump over other pieces.</p><div class="more">Moves two squares in one direction and one square perpendicular to it.</div></article>
 <article class="card" tabindex="0" role="button" aria-expanded="false"><div class="piece">♙</div><h3>The Pawn</h3><p>Moves forward, captures diagonally, and can promote when it reaches the last rank.</p><div class="more">Usually moves one square forward, may move two squares on its first move, and captures diagonally.</div></article>
 </div></section>

<section class="portfolio" id="portfolio">
 <div class="section-head"><small>03 / Your Work, Your Moves</small><h2>Performance Task Portfolio</h2>
 <p>A collection of your school outputs, activities, projects, and reflections—organized like a chess game, one move at a time.</p></div>
 <p class="portfolio-intro">Use the spaces below to organize your performance tasks. You can choose multiple files of any type, including PPT, PPTX, PDF, DOCX, XLS, XLSX, PNG, JPG, videos, and more.</p>
 <div class="task-grid">
  <article class="task-card"><div class="task-number">TASK 01</div><h3>Written Activities</h3><p>Compile worksheets, written exercises, and activity sheets.</p><input type="file" multiple aria-label="Upload written activities" data-task="written"><div class="file-list" id="files-written">No files selected yet.</div></article>
  <article class="task-card"><div class="task-number">TASK 02</div><h3>Presentations</h3><p>Collect PowerPoint presentations, reports, and discussion materials.</p><input type="file" multiple aria-label="Upload presentations" data-task="presentations"><div class="file-list" id="files-presentations">No files selected yet.</div></article>
  <article class="task-card"><div class="task-number">TASK 03</div><h3>Projects & Performance Outputs</h3><p>Showcase your major projects, creative outputs, and practical activities.</p><input type="file" multiple aria-label="Upload projects" data-task="projects"><div class="file-list" id="files-projects">No files selected yet.</div></article>
  <article class="task-card"><div class="task-number">TASK 04</div><h3>Photos & Documentation</h3><p>Add pictures or documents that serve as evidence of your activities.</p><input type="file" multiple aria-label="Upload documentation" data-task="documentation"><div class="file-list" id="files-documentation">No files selected yet.</div></article>
  <article class="task-card"><div class="task-number">TASK 05</div><h3>Reflections & Learnings</h3><p>Keep your reflections, insights, and lessons learned throughout the subject.</p><input type="file" multiple aria-label="Upload reflections" data-task="reflections"><div class="file-list" id="files-reflections">No files selected yet.</div></article>
  <article class="task-card"><div class="task-number">TASK 06</div><h3>Additional Outputs</h3><p>Include other requirements, certificates, or supplementary activities.</p><input type="file" multiple aria-label="Upload additional outputs" data-task="additional"><div class="file-list" id="files-additional">No files selected yet.</div></article>
 </div>
 <div class="portfolio-note"><strong style="color:var(--gold)">Portfolio tip:</strong> Rename your files clearly before uploading—for example, “Task_01_Activity.pdf” or “Chess_Presentation.pptx”. All file types are accepted, including PowerPoint, Excel, Word, PDF, PNG, JPG, audio, and video. Selected file names and image previews appear here; files stay on your device and are not permanently uploaded or saved after you close or refresh the page.</div>
</section>

<section class="banner" id="mindset"><div class="eyebrow">04 / The Chess Mindset</div><h2>Think. Plan. Execute.</h2><p>Great chess is not about moving quickly. It is about understanding the position, considering your opponent's ideas, and choosing the move that best serves your plan. One thoughtful move can change everything.</p><a class="cta" href="#top" onclick="window.scrollTo({top:0,behavior:'smooth'});return false">Back to the top ↑</a></section>
<footer><span>© 2026 EMTECH_ZARA_ERIANNEURIELLEGASPI</span><span>♟ BUILT WITH STRATEGY & CREATIVITY ♟</span></footer>
<script>
document.querySelectorAll('.card').forEach(card => {
  const toggle = () => {
    const open = card.classList.toggle('open');
    card.setAttribute('aria-expanded', String(open));
  };
  card.addEventListener('click', toggle);
  card.addEventListener('keydown', event => {
    if (event.key === 'Enter' || event.key === ' ') {
      event.preventDefault();
      toggle();
    }
  });
});
document.querySelectorAll('input[type="file"][data-task]').forEach(input => {
  input.addEventListener('change', () => {
    const target = document.getElementById('files-' + input.dataset.task);
    const files = Array.from(input.files || []);
    target.replaceChildren();
    if (!files.length) {
      target.textContent = 'No files selected yet.';
      return;
    }
    files.forEach(file => {
      const entry = document.createElement('div');
      entry.className = 'file-entry';
      const name = document.createElement('div');
      name.textContent = '♙ ' + file.name;
      const meta = document.createElement('div');
      meta.className = 'file-meta';
      const size = file.size < 1024 * 1024 ? (file.size / 1024).toFixed(1) + ' KB' : (file.size / (1024 * 1024)).toFixed(2) + ' MB';
      meta.textContent = (file.type || 'File') + ' · ' + size;
      entry.append(name, meta);
      if (file.type.startsWith('image/')) {
        const preview = document.createElement('img');
        preview.alt = 'Preview of ' + file.name;
        preview.style.cssText = 'display:block;max-width:100%;max-height:150px;margin-top:8px;border-radius:5px';
        preview.src = URL.createObjectURL(file);
        entry.append(preview);
      }
      target.append(entry);
    });
  });
});
document.querySelectorAll('#chessboard .sq').forEach((square, index) => {
  square.setAttribute('title', String.fromCharCode(97 + index % 8) + (8 - Math.floor(index / 8)));
  square.addEventListener('click', () => {
    document.querySelectorAll('#chessboard .sq').forEach(s => s.classList.remove('selected'));
    square.classList.add('selected');
  });
});
</script>
</body></html>
