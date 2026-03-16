
<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;500;700&family=Crimson+Pro:ital,wght@0,300;0,400;1,300;1,400&display=swap');

  * { box-sizing: border-box; margin: 0; padding: 0; }

  .readme {
    font-family: 'JetBrains Mono', monospace;
    background: #0d1117;
    color: #c9d1d9;
    padding: 2.5rem 2rem;
    max-width: 780px;
    margin: 0 auto;
    min-height: 100vh;
    line-height: 1.7;
    border-radius: 8px;
  }

  .prompt-line {
    color: #58a6ff;
    font-size: 11px;
    letter-spacing: 0.08em;
    margin-bottom: 2rem;
    opacity: 0.7;
  }

  .prompt-line span { color: #3fb950; }

  .bio {
    font-family: 'Crimson Pro', serif;
    font-size: 17px;
    line-height: 1.85;
    color: #e6edf3;
    border-left: 2px solid #21262d;
    padding-left: 1.5rem;
    margin-bottom: 2.5rem;
    font-weight: 300;
  }

  .bio strong {
    font-family: 'JetBrains Mono', monospace;
    font-weight: 500;
    font-size: 14px;
    color: #79c0ff;
    background: #161b22;
    padding: 1px 6px;
    border-radius: 3px;
    border: 1px solid #30363d;
  }

  .section-label {
    font-size: 10px;
    letter-spacing: 0.15em;
    color: #484f58;
    text-transform: uppercase;
    margin-bottom: 1rem;
    margin-top: 2rem;
  }

  .icons-row {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    align-items: center;
    margin-bottom: 2rem;
  }

  .icon-chip {
    display: flex;
    align-items: center;
    gap: 8px;
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 6px;
    padding: 6px 12px;
    font-size: 12px;
    color: #8b949e;
    transition: border-color 0.15s, color 0.15s;
  }

  .icon-chip:hover { border-color: #58a6ff; color: #c9d1d9; }

  .icon-chip .ico { font-size: 16px; }

  .icon-chip.rust { color: #e07040; border-color: #3d2015; }
  .icon-chip.rust:hover { border-color: #e07040; }

  .icon-chip.go { color: #00ADD8; border-color: #003344; }
  .icon-chip.go:hover { border-color: #00ADD8; }

  .icon-chip.linux { color: #f0c040; border-color: #332e00; }
  .icon-chip.linux:hover { border-color: #f0c040; }

  .icon-chip.c { color: #6e96c4; border-color: #1c2d40; }
  .icon-chip.c:hover { border-color: #6e96c4; }

  .physicists {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    margin-bottom: 2.5rem;
  }

  .physicist-card {
    background: #0d1117;
    border: 1px solid #21262d;
    border-radius: 6px;
    padding: 0.75rem 1rem;
    flex: 1;
    min-width: 200px;
  }

  .physicist-card .name {
    font-size: 13px;
    font-weight: 500;
    color: #c9d1d9;
    margin-bottom: 4px;
  }

  .physicist-card .quote {
    font-family: 'Crimson Pro', serif;
    font-size: 14px;
    font-style: italic;
    color: #484f58;
    line-height: 1.5;
  }

  .physicist-card .field {
    font-size: 10px;
    color: #3fb950;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    margin-top: 6px;
    opacity: 0.7;
  }

  .stats-section {
    margin-bottom: 2rem;
  }

  .stats-section img {
    border-radius: 6px;
    border: 1px solid #21262d;
  }

  .connect-section {
    border-top: 1px solid #21262d;
    padding-top: 1.5rem;
    display: flex;
    align-items: center;
    gap: 1rem;
  }

  .connect-label {
    font-size: 10px;
    color: #484f58;
    letter-spacing: 0.15em;
    text-transform: uppercase;
  }

  .li-link {
    display: flex;
    align-items: center;
    gap: 8px;
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 6px;
    padding: 7px 14px;
    font-size: 12px;
    color: #8b949e;
    text-decoration: none;
    transition: border-color 0.15s, color 0.15s;
  }

  .li-link:hover {
    border-color: #0a66c2;
    color: #0a66c2;
  }

  .li-dot {
    width: 8px; height: 8px;
    border-radius: 50%;
    background: #0a66c2;
    opacity: 0.8;
    flex-shrink: 0;
  }

  .cursor {
    display: inline-block;
    width: 8px;
    height: 14px;
    background: #58a6ff;
    margin-left: 4px;
    vertical-align: middle;
    animation: blink 1.1s step-end infinite;
    opacity: 0.8;
  }

  @keyframes blink { 0%,100%{opacity:0.8} 50%{opacity:0} }

  .tux { font-size: 22px; }
</style>

<div class="readme">

  <div class="prompt-line"><span>benali@oujda</span>:~$ cat README.md<span class="cursor"></span></div>

  <div class="bio">
    hey, what's up. most people don't really look at github projects anymore, they just ask AI for the code. i use AI too, it's a great tool. but sometimes i still like to open <strong>vim at 2am</strong> and write code slowly, just to talk directly to the computer. this profile has a little of that work: projects from <strong>zone01 oujda (01-edu)</strong>, rust experiments, systems programming ideas, bootloader or networking stuff, random unfinished repos, and things that only exist because the idea sounded interesting. many projects are messy or incomplete and that's fine. writing code like this is a kind of meditation for me. if you enjoy that old-school side of programming too, feel free to explore the repos.
  </div>

  <div class="section-label">stack & tools</div>
  <div class="icons-row">
    <div class="icon-chip linux">
      <span style="font-size:20px">🐧</span>
      <span>Linux</span>
    </div>
    <div class="icon-chip rust">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M23.634 11.346l-1.002-.618a13.44 13.44 0 00-.028-.29l.863-.772a.377.377 0 00-.098-.618l-1.086-.484a12.87 12.87 0 00-.084-.28l.7-.908a.377.377 0 00-.166-.592l-1.144-.34a12.77 12.77 0 00-.14-.262l.52-1.025a.377.377 0 00-.23-.549l-1.176-.19a12.26 12.26 0 00-.192-.235l.328-1.12a.377.377 0 00-.288-.49l-1.185-.036a12.4 12.4 0 00-.24-.202l.128-1.188a.377.377 0 00-.34-.414l-1.168.122a12.5 12.5 0 00-.282-.162l-.074-1.19a.377.377 0 00-.386-.328l-1.127.278a12.86 12.86 0 00-.315-.117L15.19.484a.377.377 0 00-.42-.23l-1.06.43a13.28 13.28 0 00-.341-.068L13.024.002a.377.377 0 00-.443-.12l-.974.574a13.4 13.4 0 00-.358-.016L10.91.044a.377.377 0 00-.456.006l-.875.712a13.45 13.45 0 00-.358.016L8.246.204a.377.377 0 00-.442.12L7.46.618a13.27 13.27 0 00-.34.068L6.062.254a.377.377 0 00-.42.23L5.292.77a12.86 12.86 0 00-.315.117L3.85.608a.377.377 0 00-.386.328L3.39 2.126a12.5 12.5 0 00-.282.162L2.02 2.164a.377.377 0 00-.34.414l.128 1.188a12.4 12.4 0 00-.24.202L.383 3.804a.377.377 0 00-.288.49l.328 1.12a12.77 12.77 0 00-.192.235L.077 5.84a.377.377 0 00-.23.549l.52 1.025a12.77 12.77 0 00-.14.262L.083 7.816a.377.377 0 00-.166.592l.7.908a12.87 12.87 0 00-.084.28L.447 10.08a.377.377 0 00-.098.618l.863.772a13.44 13.44 0 00-.028.29L.182 12.378a.377.377 0 00.028.626l1.002.618a13.44 13.44 0 00.028.29l-.863.772a.377.377 0 00.098.618l1.086.484c.027.094.055.187.084.28l-.7.908a.377.377 0 00.166.592l1.144.34c.046.088.093.175.14.262l-.52 1.025a.377.377 0 00.23.549l1.176.19c.063.08.127.158.192.235l-.328 1.12a.377.377 0 00.288.49l1.185.036c.078.069.159.136.24.202l-.128 1.188a.377.377 0 00.34.414l1.168-.122c.092.056.187.11.282.162l.074 1.19a.377.377 0 00.386.328l1.127-.278c.104.04.21.08.315.117l.35 1.144a.377.377 0 00.42.23l1.06-.43c.112.024.226.047.341.068l.345 1.09a.377.377 0 00.443.12l.974-.574c.119.006.238.012.358.016l.34.998a.377.377 0 00.456.006l.875-.712c.12-.004.24-.01.358-.016l.974.574a.377.377 0 00.443-.12l.345-1.09c.115-.021.229-.044.341-.068l1.06.43a.377.377 0 00.42-.23l.35-1.144c.105-.037.21-.077.315-.117l1.127.278a.377.377 0 00.386-.328l.074-1.19a12.5 12.5 0 00.282-.162l1.168.122a.377.377 0 00.34-.414l-.128-1.188a12.4 12.4 0 00.24-.202l1.185-.036a.377.377 0 00.288-.49l-.328-1.12c.065-.077.13-.155.192-.235l1.144-.34a.377.377 0 00.166-.592l-.7-.908c.029-.093.057-.186.084-.28l1.086-.484a.377.377 0 00.098-.618l-.863-.772c.01-.097.019-.194.028-.29l1.002-.618a.377.377 0 00-.028-.626zM12 19.5a7.5 7.5 0 110-15 7.5 7.5 0 010 15z"/></svg>
      <span>Rust</span>
    </div>
    <div class="icon-chip go">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M1.811 10.231c-.047 0-.058-.023-.035-.055l.246-.315c.023-.032.081-.055.128-.055h4.172c.046 0 .058.032.035.063l-.199.303c-.023.033-.08.063-.127.063zM.047 11.306c-.047 0-.059-.023-.035-.055l.245-.316c.023-.031.081-.055.127-.055h5.328c.046 0 .058.024.047.063l-.093.28c-.012.047-.058.064-.105.064zm2.828 1.075c-.047 0-.059-.023-.035-.055l.163-.292c.023-.031.069-.062.127-.062h2.337c.046 0 .07.031.07.077l-.023.28c0 .047-.047.08-.082.08zm12.129-2.36c-.736.187-1.239.327-1.963.514-.176.046-.187.058-.34-.117-.174-.199-.303-.327-.548-.444-.737-.362-1.45-.257-2.115.175-.795.514-1.204 1.274-1.192 2.22.011.935.654 1.706 1.577 1.835.795.105 1.46-.175 1.987-.771.105-.128.198-.257.315-.409H9.937c-.245 0-.304-.152-.222-.35.152-.362.432-.968.596-1.274a.315.315 0 01.292-.187h5.503c-.023.316-.023.631-.07.947a4.983 4.983 0 01-.958 2.29c-.841 1.11-1.94 1.8-3.33 1.986-1.145.152-2.209-.07-3.143-.77-.865-.655-1.356-1.52-1.484-2.595-.152-1.274.222-2.419.993-3.424.83-1.086 1.928-1.776 3.272-2.02 1.098-.2 2.15-.07 3.096.571.62.41 1.063.97 1.356 1.648.07.105.023.164-.117.2zm3.868 6.461c-1.064-.024-2.034-.328-2.852-1.029a3.665 3.665 0 01-1.262-2.255c-.21-1.32.152-2.489.947-3.529.853-1.122 1.881-1.706 3.272-1.95 1.192-.21 2.314-.095 3.33.595.923.63 1.496 1.484 1.648 2.605.198 1.578-.257 2.863-1.344 3.962-.771.783-1.718 1.273-2.805 1.495-.315.06-.63.07-.934.106zm2.78-4.72c-.011-.153-.011-.27-.034-.387-.21-1.157-1.274-1.81-2.384-1.554-1.087.245-1.788 1.052-1.895 2.15-.09.904.479 1.843 1.39 2.185.779.293 1.543.199 2.22-.385.682-.573.948-1.344.703-2.009z"/></svg>
      <span>Go</span>
    </div>
    <div class="icon-chip c">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M16.5 12c0-2.485-2.015-4.5-4.5-4.5S7.5 9.515 7.5 12s2.015 4.5 4.5 4.5 4.5-2.015 4.5-4.5zm5.25 0C21.75 17.937 17.937 21.75 12 21.75S2.25 17.937 2.25 12 6.063 2.25 12 2.25 21.75 6.063 21.75 12z"/></svg>
      <span>C / Systems</span>
    </div>
  </div>

  <div class="section-label">minds i return to</div>
  <div class="physicists">
    <div class="physicist-card">
      <div class="name">Richard Feynman</div>
      <div class="quote">"If you can't explain it simply, you don't understand it well enough."</div>
      <div class="field">QED · path integrals · teaching</div>
    </div>
    <div class="physicist-card">
      <div class="name">Paul Dirac</div>
      <div class="quote">"A theory with mathematical beauty is more likely to be correct."</div>
      <div class="field">quantum mechanics · antimatter · elegance</div>
    </div>
  </div>

  <div class="section-label">languages</div>
  <div class="stats-section">
    <img
      src="https://github-readme-stats.vercel.app/api/top-langs?username=BenaliOssama&locale=en&hide_title=true&layout=compact&card_width=320&langs_count=6&theme=github_dark&hide_border=true"
      height="150"
      alt="languages graph"
    />
  </div>

  <div class="connect-section">
    <span class="connect-label">reach me</span>
    <a class="li-link" href="https://www.linkedin.com/in/oussama-benali-23959625a/" target="_blank">
      <span class="li-dot"></span>
      <span>oussama-benali</span>
    </a>
  </div>

</div>
