
  <h1>🎯 Wordle Game</h1>
  <p>
    An interactive <strong>Wordle</strong> clone built with 
    <strong>HTML, CSS, JavaScript, and Tailwind CSS</strong>.<br>
    Guess the hidden word within a limited number of tries. Smooth animations and transitions provide instant visual feedback for each guess.
  </p>

  <div class="box">
    <h2>✨ Features</h2>
    <ul>
      <li>🎮 Classic Wordle gameplay (fixed attempts, per-letter feedback).</li>
      <li>🧠 Validates guesses against a word list.</li>
      <li>⚡ Smooth animations & transitions for reveal/flip/shake effects.</li>
      <li>🎨 Responsive UI with Tailwind utility classes.</li>
      <li>📱 Works on desktop & mobile.</li>
    </ul>
  </div>

  <div class="box">
    <h2>🛠 Tech Stack</h2>
    <ul>
      <li><strong>HTML</strong> – Structure</li>
      <li><strong>CSS / Tailwind CSS</strong> – Styling & responsiveness</li>
      <li><strong>JavaScript (ES6)</strong> – Game logic & UI updates</li>
    </ul>
  </div>

  <div class="box">
    <h2>📂 Project Structure</h2>
    <pre><code>wordle-game/
├─ index.html       # App shell and board
├─ script.js        # Game logic and interactions
├─ style.css        # Optional custom styles
├─ words.json       # (Optional) Word list / dictionary
└─ README.md</code></pre>
  </div>

  <div class="box">
    <h2>🚀 Getting Started</h2>
    <h3>Option A — Quick Start (CDN)</h3>
    <ol>
      <li><strong>Clone the repository</strong>
        <pre><code>git clone https://github.com/dev-wth-vikrant/wordle-game.git
cd wordle-game</code></pre>
      </li>
      <li><strong>Open</strong> <code>index.html</code> directly in your browser OR run a local server (recommended for fetch of <code>words.json</code>).</li>
      <ul>
        <li>VS Code: Install <strong>Live Server</strong> → Right-click <code>index.html</code> → <em>Open with Live Server</em></li>
        <li>Python:
          <pre><code>python -m http.server 5500</code></pre>
          Visit <code>http://localhost:5500</code>
        </li>
      </ul>
    </ol>

    <h3>Option B — Tailwind Build</h3>
    <ol>
      <li>Install <strong>Node.js</strong> if not installed.</li>
      <li>Install dependencies:
        <pre><code>npm install</code></pre>
      </li>
      <li>Build Tailwind with watcher:
        <pre><code>npx tailwindcss -i ./src/input.css -o ./style.css --watch</code></pre>
      </li>
      <li>Run a local server and open <code>index.html</code>.</li>
    </ol>
  </div>

  <div class="box">
    <h2>🎮 How to Play</h2>
    <ul>
      <li>Enter a valid word and press <strong>Enter</strong>.</li>
      <li>Tiles flip to reveal feedback:
        <ul>
          <li>🟩 Correct letter &amp; position</li>
          <li>🟨 Letter exists but wrong position</li>
          <li>⬜ Letter not in the word</li>
        </ul>
      </li>
      <li>Use on-screen or physical keyboard.</li>
      <li>Win by guessing within allowed attempts!</li>
    </ul>
  </div>

  <div class="box">
    <h2>🔧 Configuration</h2>
    <ul>
      <li><strong>Attempts</strong>: Update <code>MAX_TRIES</code> in <code>script.js</code>.</li>
      <li><strong>Word Length</strong>: Update <code>WORD_LENGTH</code> and word list.</li>
      <li><strong>Dictionary</strong>: Replace <code>words.json</code> or inline array.</li>
    </ul>
  </div>

  <div class="box">
    <h2>📸 Preview</h2>
    <p>(Add screenshot or GIF here: <code>/assets/preview.gif</code>)</p>
  </div>

  <div class="box">
    <h2>✅ Roadmap</h2>
    <ul>
      <li>Difficulty modes (Easy/Medium/Hard)</li>
      <li>Daily challenge (word of the day)</li>
      <li>Keyboard hints & accessibility improvements</li>
      <li>Sound effects & haptics</li>
      <li>Multi-language word lists</li>
    </ul>
  </div>

  <div class="box">
    <h2>🤝 Contributing</h2>
    <p>Contributions, issues, and feature requests are welcome!</p>
    <ol>
      <li>Fork the repo</li>
      <li>Create a feature branch</li>
      <li>Submit a PR with a clear description</li>
    </ol>
  </div>

  <div class="box">
    <h2>📜 License</h2>
    <p>Distributed under the <strong>MIT License</strong>. See <code>LICENSE</code> for details.</p>
  </div>

  <div class="box">
    <h2>🙌 Acknowledgements</h2>
    <ul>
      <li>Inspired by the original <strong>Wordle</strong> game.</li>
      <li>Tailwind CDN for quick setup.</li>
    </ul>
  </div>

  <div class="author">
    <h2>👨‍💻 Author</h2>
    <p><strong>Vikrant Yadav</strong><br>
    📧 <a href="mailto:vikrantydv997@gmail.com">vikrantydv997@gmail.com</a><br>
    🔗 <a href="https://github.com/dev-wth-vikrant" target="_blank">GitHub</a> • 
    <a href="https://www.linkedin.com/in/vikrant-yadavv/" target="_blank">LinkedIn</a></p>
  </div>
