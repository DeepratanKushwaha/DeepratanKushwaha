<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src="./support.js"></script>
</head>
<body>
<x-dc>
<helmet>
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;600;700&display=swap" rel="stylesheet"/>
  <style>
    body { margin:0; background:#010409; }
    * { box-sizing:border-box; }
    @keyframes blink { 0%,49%{opacity:1} 50%,100%{opacity:0} }
    @keyframes floatIn { from{opacity:0; transform:translateY(14px)} to{opacity:1; transform:translateY(0)} }
    .gh-link { color:#58a6ff; text-decoration:none; }
    .gh-link:hover { text-decoration:underline; }
  </style>
</helmet>

<div style="min-height:100vh; background:radial-gradient(1200px 600px at 50% -10%, #0d1b2e 0%, #010409 60%); font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Helvetica,Arial,sans-serif; color:#c9d1d9; padding:0 0 60px;">

  <!-- top chrome bar -->
  <div style="position:sticky; top:0; z-index:20; display:flex; align-items:center; gap:14px; padding:12px 22px; background:#010409ee; backdrop-filter:blur(8px); border-bottom:1px solid #21262d;">
    <div style="width:14px;height:14px;border-radius:50%;background:#58a6ff;box-shadow:0 0 12px #58a6ff;"></div>
    <span style="font-family:'JetBrains Mono',monospace; font-size:13px; color:#8b949e;">github.com / <span style="color:#c9d1d9;">deepratankushwaha</span></span>
    <span style="margin-left:auto; font-family:'JetBrains Mono',monospace; font-size:11px; color:#3fb950; border:1px solid #2ea04326; background:#2ea04314; padding:3px 9px; border-radius:20px;">● README.md preview</span>
  </div>

  <div style="max-width:940px; margin:0 auto; padding:0 22px;">

    <!-- HEADER BANNER -->
    <div style="margin-top:26px; border-radius:14px; overflow:hidden; border:1px solid #21262d; position:relative; background:linear-gradient(120deg,#0d1117 0%,#11203a 45%,#1f6feb 110%);">
      <div style="padding:40px 38px 44px;">
        <div style="font-family:'JetBrains Mono',monospace; font-size:13px; color:#58a6ff; letter-spacing:2px; margin-bottom:10px;">$ ./hello --profile</div>
        <h1 style="margin:0; font-size:46px; line-height:1.05; font-weight:800; color:#fff; letter-spacing:-1px;">Deepratan Kushwaha</h1>
        <div style="margin-top:12px; font-size:18px; color:#c9d1d9; font-weight:500;">Data Scientist · Python Full-Stack Developer · Corporate Trainer</div>
      </div>
      <div style="position:absolute; right:-40px; bottom:-50px; width:240px; height:240px; border-radius:50%; background:radial-gradient(circle,#58a6ff55,transparent 70%); filter:blur(6px);"></div>
    </div>

    <!-- TYPING + BADGES -->
    <div style="text-align:center; margin-top:26px;">
      <div style="display:inline-flex; align-items:center; min-height:34px; font-family:'JetBrains Mono',monospace; font-size:21px; font-weight:600; color:#58a6ff;">
        <span>{{ typed }}</span>
        <span style="display:inline-block; width:11px; height:24px; background:#58a6ff; margin-left:3px; animation:blink 1s steps(1) infinite; vertical-align:middle;"></span>
      </div>
      <div style="display:flex; flex-wrap:wrap; gap:10px; justify-content:center; margin-top:20px;">
        <span style="font-family:'JetBrains Mono',monospace; font-size:12px; padding:5px 11px; border-radius:6px; background:#161b22; border:1px solid #30363d; color:#8b949e;">👁 Profile views <b style="color:#58a6ff;">{{ views }}</b></span>
        <a class="gh-link" style="font-family:'JetBrains Mono',monospace; font-size:12px; padding:5px 11px; border-radius:6px; background:#1f6feb; color:#fff;">✉ Email</a>
        <a class="gh-link" style="font-family:'JetBrains Mono',monospace; font-size:12px; padding:5px 11px; border-radius:6px; background:#0a66c2; color:#fff;">in LinkedIn</a>
        <span style="font-family:'JetBrains Mono',monospace; font-size:12px; padding:5px 11px; border-radius:6px; background:#161b22; border:1px solid #30363d; color:#c9d1d9;">📍 Jaipur, India</span>
      </div>
    </div>

    <!-- WHOAMI -->
    <h2 style="margin:46px 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> whoami</h2>
    <div style="border:1px solid #30363d; border-radius:10px; overflow:hidden; background:#0d1117;">
      <div style="display:flex; align-items:center; gap:7px; padding:9px 14px; background:#161b22; border-bottom:1px solid #21262d;">
        <span style="width:11px;height:11px;border-radius:50%;background:#ff5f56;"></span>
        <span style="width:11px;height:11px;border-radius:50%;background:#ffbd2e;"></span>
        <span style="width:11px;height:11px;border-radius:50%;background:#27c93f;"></span>
        <span style="margin-left:8px; font-family:'JetBrains Mono',monospace; font-size:11px; color:#8b949e;">deepratan.py</span>
      </div>
      <pre style="margin:0; padding:18px 20px; font-family:'JetBrains Mono',monospace; font-size:13.5px; line-height:1.7; color:#c9d1d9; overflow-x:auto;"><span style="color:#ff7b72;">class</span> <span style="color:#d2a8ff;">Deepratan</span>:
    <span style="color:#ff7b72;">def</span> <span style="color:#d2a8ff;">__init__</span>(<span style="color:#ffa657;">self</span>):
        <span style="color:#ffa657;">self</span>.role       = <span style="color:#a5d6ff;">"Data Scientist &amp; Corporate Trainer"</span>
        <span style="color:#ffa657;">self</span>.experience = <span style="color:#a5d6ff;">"5+ years"</span>
        <span style="color:#ffa657;">self</span>.focus      = [<span style="color:#a5d6ff;">"Full-stack Python"</span>, <span style="color:#a5d6ff;">"Data Science"</span>, <span style="color:#a5d6ff;">"ML / Gen-AI"</span>]
        <span style="color:#ffa657;">self</span>.students   = <span style="color:#79c0ff;">1500</span>   <span style="color:#8b949e;"># and counting</span>

    <span style="color:#ff7b72;">def</span> <span style="color:#d2a8ff;">say_hi</span>(<span style="color:#ffa657;">self</span>):
        <span style="color:#ff7b72;">return</span> <span style="color:#a5d6ff;">"Let's turn data into decisions. 🚀"</span></pre>
    </div>

    <!-- TECH STACK -->
    <h2 style="margin:46px 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> tech-stack</h2>
    <sc-for list="{{ stackGroups }}" as="grp" hint-placeholder-count="3">
      <div style="margin-bottom:16px;">
        <div style="font-family:'JetBrains Mono',monospace; font-size:12px; color:#8b949e; margin-bottom:9px; text-transform:uppercase; letter-spacing:1px;">{{ grp.label }}</div>
        <div style="display:flex; flex-wrap:wrap; gap:9px;">
          <sc-for list="{{ grp.items }}" as="t" hint-placeholder-count="5">
            <span style="display:inline-flex; align-items:center; gap:6px; font-family:'JetBrains Mono',monospace; font-size:13px; font-weight:600; padding:7px 13px; border-radius:8px; background:#161b22; border:1px solid #30363d; color:#c9d1d9; cursor:default; transition:transform .15s, border-color .15s, box-shadow .15s;" style-hover="transform:translateY(-3px); border-color:#58a6ff; box-shadow:0 6px 18px #58a6ff33; color:#fff;"><span style="width:8px;height:8px;border-radius:2px;background:{{ t.c }};"></span>{{ t.n }}</span>
          </sc-for>
        </div>
      </div>
    </sc-for>

    <!-- PROFICIENCY -->
    <h2 style="margin:46px 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> proficiency</h2>
    <div style="display:grid; grid-template-columns:1fr 1fr; gap:14px 28px;">
      <sc-for list="{{ skills }}" as="s" hint-placeholder-count="6">
        <div>
          <div style="display:flex; justify-content:space-between; font-family:'JetBrains Mono',monospace; font-size:13px; margin-bottom:6px;">
            <span style="color:#c9d1d9;">{{ s.name }}</span>
            <span style="color:#58a6ff; font-weight:700;">{{ s.shown }}%</span>
          </div>
          <div style="height:9px; border-radius:6px; background:#161b22; border:1px solid #21262d; overflow:hidden;">
            <div style="height:100%; width:{{ s.fill }}%; border-radius:6px; background:linear-gradient(90deg,#1f6feb,#58a6ff); box-shadow:0 0 10px #58a6ff66; transition:width 1.1s cubic-bezier(.22,1,.36,1);"></div>
          </div>
        </div>
      </sc-for>
    </div>

    <!-- GITHUB STATS -->
    <h2 style="margin:46px 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> github-stats</h2>
    <div style="display:grid; grid-template-columns:1.15fr 1fr; gap:16px;">
      <!-- stats card -->
      <div style="border:1px solid #30363d; border-radius:10px; background:#0d1117; padding:20px 22px;">
        <div style="font-family:'JetBrains Mono',monospace; font-size:15px; color:#58a6ff; font-weight:700; margin-bottom:16px;">Deepratan's GitHub Stats</div>
        <div style="display:flex; gap:20px; align-items:center;">
          <div style="flex:1; display:grid; gap:11px;">
            <sc-for list="{{ stats }}" as="st" hint-placeholder-count="5">
              <div style="display:flex; align-items:center; gap:9px; font-size:13.5px;">
                <span style="width:18px; text-align:center;">{{ st.icon }}</span>
                <span style="color:#c9d1d9; flex:1;">{{ st.label }}:</span>
                <b style="color:#fff; font-family:'JetBrains Mono',monospace;">{{ st.shown }}</b>
              </div>
            </sc-for>
          </div>
          <div style="width:84px; height:84px; border-radius:50%; display:flex; align-items:center; justify-content:center; background:conic-gradient(#58a6ff {{ ringPct }}deg,#21262d 0); flex-shrink:0;">
            <div style="width:64px;height:64px;border-radius:50%;background:#0d1117;display:flex;align-items:center;justify-content:center;font-family:'JetBrains Mono',monospace;font-size:22px;font-weight:800;color:#58a6ff;">A+</div>
          </div>
        </div>
      </div>
      <!-- top langs -->
      <div style="border:1px solid #30363d; border-radius:10px; background:#0d1117; padding:20px 22px;">
        <div style="font-family:'JetBrains Mono',monospace; font-size:15px; color:#58a6ff; font-weight:700; margin-bottom:16px;">Most Used Languages</div>
        <div style="display:grid; gap:13px;">
          <sc-for list="{{ langs }}" as="l" hint-placeholder-count="5">
            <div>
              <div style="display:flex; justify-content:space-between; font-size:12.5px; margin-bottom:5px;"><span style="color:#c9d1d9;">{{ l.name }}</span><span style="color:#8b949e; font-family:'JetBrains Mono',monospace;">{{ l.pct }}%</span></div>
              <div style="height:8px; border-radius:5px; background:#161b22; overflow:hidden;"><div style="height:100%; width:{{ l.fill }}%; background:{{ l.c }}; border-radius:5px; transition:width 1.1s cubic-bezier(.22,1,.36,1);"></div></div>
            </div>
          </sc-for>
        </div>
      </div>
    </div>

    <!-- CONTRIBUTION GRAPH -->
    <h2 style="margin:46px 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> contribution-activity</h2>
    <div style="border:1px solid #30363d; border-radius:10px; background:#0d1117; padding:22px; overflow-x:auto;">
      <div style="display:flex; gap:3px; min-width:740px;">
        <sc-for list="{{ weeks }}" as="wk" hint-placeholder-count="52">
          <div style="display:flex; flex-direction:column; gap:3px;">
            <sc-for list="{{ wk.days }}" as="d" hint-placeholder-count="7">
              <div title="{{ d.title }}" style="width:11px; height:11px; border-radius:2px; background:{{ d.color }}; transition:transform .12s;" style-hover="transform:scale(1.5);"></div>
            </sc-for>
          </div>
        </sc-for>
      </div>
      <div style="display:flex; align-items:center; gap:6px; justify-content:flex-end; margin-top:14px; font-family:'JetBrains Mono',monospace; font-size:11px; color:#8b949e;">
        Less
        <span style="width:11px;height:11px;border-radius:2px;background:#161b22;"></span>
        <span style="width:11px;height:11px;border-radius:2px;background:#0d3a66;"></span>
        <span style="width:11px;height:11px;border-radius:2px;background:#1f6feb;"></span>
        <span style="width:11px;height:11px;border-radius:2px;background:#58a6ff;"></span>
        <span style="width:11px;height:11px;border-radius:2px;background:#a5d6ff;"></span>
        More
      </div>
    </div>

    <!-- EXPERIENCE + EDUCATION -->
    <div style="display:grid; grid-template-columns:1fr 1fr; gap:16px; margin-top:46px;">
      <div>
        <h2 style="margin:0 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> experience</h2>
        <div style="border:1px solid #30363d; border-left:3px solid #58a6ff; border-radius:10px; background:#0d1117; padding:18px 20px;">
          <div style="font-size:15px; font-weight:700; color:#fff;">Data Scientist &amp; Corporate Trainer</div>
          <div style="font-size:13px; color:#58a6ff; margin:3px 0 2px;">GRRAS Solutions Pvt. Ltd · Jaipur</div>
          <div style="font-family:'JetBrains Mono',monospace; font-size:11px; color:#8b949e; margin-bottom:12px;">Feb 2023 – Present · 5+ yrs experience</div>
          <ul style="margin:0; padding-left:18px; font-size:13px; line-height:1.7; color:#c9d1d9;">
            <li>Taught <b style="color:#58a6ff;">1500+</b> students Python, DBs, web dev &amp; data science.</li>
            <li>Delivered corporate trainings &amp; industrial workshops across 6+ colleges.</li>
            <li>Authored training manuals, modules &amp; instructional materials.</li>
          </ul>
        </div>
      </div>
      <div>
        <h2 style="margin:0 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> education</h2>
        <div style="display:grid; gap:12px;">
          <div style="border:1px solid #30363d; border-radius:10px; background:#0d1117; padding:16px 18px;">
            <div style="font-size:14px; font-weight:700; color:#fff;">🎓 Master of Computer Application</div>
            <div style="font-size:12.5px; color:#8b949e; margin-top:4px;">S.S. Jain Subodh P.G. College · RTU, Kota</div>
          </div>
          <div style="border:1px solid #30363d; border-radius:10px; background:#0d1117; padding:16px 18px;">
            <div style="font-size:14px; font-weight:700; color:#fff;">🎓 Bachelor of Computer Application</div>
            <div style="font-size:12.5px; color:#8b949e; margin-top:4px;">S.S. Jain Subodh P.G. College · Univ. of Rajasthan</div>
          </div>
        </div>
      </div>
    </div>

    <!-- ACHIEVEMENTS -->
    <h2 style="margin:46px 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> achievements</h2>
    <div style="display:flex; flex-wrap:wrap; gap:11px;">
      <sc-for list="{{ achievements }}" as="a" hint-placeholder-count="4">
        <div style="display:flex; align-items:center; gap:10px; padding:12px 15px; border-radius:10px; background:#161b22; border:1px solid #30363d; transition:transform .15s, border-color .15s;" style-hover="transform:translateY(-3px); border-color:#58a6ff;">
          <span style="font-size:18px;">{{ a.icon }}</span>
          <div>
            <div style="font-size:13px; font-weight:700; color:#fff;">{{ a.title }}</div>
            <div style="font-size:11.5px; color:#8b949e;">{{ a.sub }}</div>
          </div>
        </div>
      </sc-for>
    </div>

    <!-- CONNECT -->
    <h2 style="margin:46px 0 16px; padding-bottom:8px; border-bottom:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:20px; color:#fff;"><span style="color:#58a6ff;">~/</span> connect</h2>
    <div style="display:flex; flex-wrap:wrap; gap:12px;">
      <a class="gh-link" href="/cdn-cgi/l/email-protection#c3a7a6a6b3b1a2b7a2ada8b6b0abb4a2ab83a4aea2aaafeda0acae" style="flex:1; min-width:180px; text-align:center; padding:15px; border-radius:10px; background:#1f6feb; color:#fff; font-weight:700; font-family:'JetBrains Mono',monospace; font-size:14px;">✉ Email</a>
      <a class="gh-link" href="https://www.linkedin.com/in/deepratankushwaha" style="flex:1; min-width:180px; text-align:center; padding:15px; border-radius:10px; background:#0a66c2; color:#fff; font-weight:700; font-family:'JetBrains Mono',monospace; font-size:14px;">in LinkedIn</a>
      <a class="gh-link" href="tel:+919887410890" style="flex:1; min-width:180px; text-align:center; padding:15px; border-radius:10px; background:#161b22; border:1px solid #30363d; color:#c9d1d9; font-weight:700; font-family:'JetBrains Mono',monospace; font-size:14px;">📞 +91 98874 10890</a>
    </div>

    <div style="text-align:center; margin-top:40px; padding-top:22px; border-top:1px solid #21262d; font-family:'JetBrains Mono',monospace; font-size:12px; color:#8b949e;">
      This is a live preview of <b style="color:#c9d1d9;">README.md</b> — the actual file (with GitHub widgets) is in your project, ready to paste.
    </div>

  </div>
</div>
</x-dc>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script type="text/x-dc" data-dc-script data-props="{&quot;$preview&quot;:{&quot;width&quot;:984,&quot;height&quot;:1400}}">
class Component extends DCLogic {
  state = { typed: "", animate: false, views: 0, statsShown: [0,0,0,0,0] };

  fullPhrases = [
    "Building with Python — full-stack & data",
    "Flask APIs · ML models · clean pipelines",
    "Taught 1500+ developers & data scientists",
    "Turning raw data into real decisions",
  ];

  statTargets = [128, 47, 86, 1500, 23];

  componentDidMount() {
    // typewriter
    this._p = 0; this._c = 0; this._del = false;
    this.type();
    // animate bars after a beat
    setTimeout(() => this.setState({ animate: true }), 250);
    // count-up profile views + stats
    this.countUp("views", 4217, 1400);
    this.statTargets.forEach((t, i) => this.countUpStat(i, t, 1400));
  }
  componentWillUnmount() { clearTimeout(this._tt); }

  type() {
    const phrase = this.fullPhrases[this._p];
    if (!this._del) {
      this._c++;
      if (this._c > phrase.length) { this._del = true; this._tt = setTimeout(() => this.type(), 1300); return; }
    } else {
      this._c--;
      if (this._c === 0) { this._del = false; this._p = (this._p + 1) % this.fullPhrases.length; }
    }
    this.setState({ typed: phrase.slice(0, this._c) });
    this._tt = setTimeout(() => this.type(), this._del ? 35 : 65);
  }

  countUp(key, target, dur) {
    const start = performance.now();
    const step = (now) => {
      const p = Math.min(1, (now - start) / dur);
      const e = 1 - Math.pow(1 - p, 3);
      this.setState({ [key]: Math.round(target * e) });
      if (p < 1) requestAnimationFrame(step);
    };
    requestAnimationFrame(step);
  }
  countUpStat(i, target, dur) {
    const start = performance.now();
    const step = (now) => {
      const p = Math.min(1, (now - start) / dur);
      const e = 1 - Math.pow(1 - p, 3);
      this.setState(s => { const a = s.statsShown.slice(); a[i] = Math.round(target * e); return { statsShown: a }; });
      if (p < 1) requestAnimationFrame(step);
    };
    requestAnimationFrame(step);
  }

  buildWeeks() {
    const colors = ["#161b22", "#0d3a66", "#1f6feb", "#58a6ff", "#a5d6ff"];
    const weeks = [];
    let seed = 7;
    const rand = () => { seed = (seed * 9301 + 49297) % 233280; return seed / 233280; };
    for (let w = 0; w < 52; w++) {
      const days = [];
      for (let d = 0; d < 7; d++) {
        const r = rand();
        // weight toward recent weeks being more active
        const bias = w / 52;
        let lvl = 0;
        const v = r * (0.55 + bias * 0.7);
        if (v > 0.78) lvl = 4; else if (v > 0.58) lvl = 3; else if (v > 0.38) lvl = 2; else if (v > 0.18) lvl = 1;
        days.push({ color: colors[lvl], title: lvl + " contributions" });
      }
      weeks.push({ days });
    }
    return weeks;
  }

  renderVals() {
    const an = this.state.animate;
    const skillDefs = [
      { name: "Python & Scripting", pct: 95 },
      { name: "Data Science / ML", pct: 82 },
      { name: "Deep Learning / NN", pct: 78 },
      { name: "RAG / LLM Pipelines", pct: 77 },
      { name: "Web Dev (Flask/HTML)", pct: 88 },
      { name: "Databases (SQL)", pct: 80 },
      { name: "Teaching & Mentoring", pct: 99 },
    ];
    const skills = skillDefs.map(s => ({ name: s.name, fill: an ? s.pct : 0, shown: an ? s.pct : 0 }));

    const langDefs = [
      { name: "Python", pct: 64, c: "#3572A5" },
      { name: "HTML", pct: 14, c: "#e34c26" },
      { name: "CSS", pct: 11, c: "#563d7c" },
      { name: "Jupyter", pct: 7, c: "#DA5B0B" },
      { name: "Shell", pct: 4, c: "#89e051" },
    ];
    const langs = langDefs.map(l => ({ ...l, fill: an ? l.pct : 0 }));

    const statMeta = [
      { icon: "⭐", label: "Total Stars Earned" },
      { icon: "🔀", label: "Total PRs" },
      { icon: "📝", label: "Total Commits (2026)" },
      { icon: "👨‍🎓", label: "Students Taught" },
      { icon: "📦", label: "Public Repos" },
    ];
    const stats = statMeta.map((m, i) => ({ ...m, shown: this.state.statsShown[i].toLocaleString() }));

    const stackGroups = [
      { label: "Languages & Web", items: [
        { n: "Python", c: "#ffd43b" }, { n: "Flask", c: "#c9d1d9" }, { n: "HTML5", c: "#e34f26" },
        { n: "CSS3", c: "#1572b6" }, { n: "Bootstrap", c: "#7952b3" },
      ]},
      { label: "Data Science, ML & AI", items: [
        { n: "NumPy", c: "#4d77cf" }, { n: "Pandas", c: "#150458" }, { n: "Matplotlib", c: "#58a6ff" },
        { n: "Seaborn", c: "#58a6ff" }, { n: "Machine Learning", c: "#f7931e" },
        { n: "Deep Learning", c: "#ff6f00" }, { n: "Neural Networks", c: "#ee4c2c" }, { n: "RAG", c: "#10a37f" }, { n: "Gen-AI", c: "#10a37f" },
      ]},
      { label: "Databases & Tools", items: [
        { n: "MySQL", c: "#00758f" }, { n: "SQLite", c: "#003b57" }, { n: "Git", c: "#f05032" },
        { n: "REST API", c: "#58a6ff" }, { n: "PowerShell", c: "#5391fe" }, { n: "VS Code", c: "#007acc" }, { n: "PyCharm", c: "#21d789" },
      ]},
    ];

    const achievements = [
      { icon: "🏅", title: "Microsoft Technology Associate", sub: "Python Programming" },
      { icon: "🟩", title: "HackerRank Certified", sub: "Python · Problem Solving" },
      { icon: "📊", title: "Data Analysis with Python", sub: "Patterns & insights from data" },
      { icon: "🐍", title: "Python for Data Science", sub: "Core DS concepts" },
    ];

    return {
      typed: this.state.typed,
      views: this.state.views.toLocaleString(),
      skills, langs, stats, stackGroups, achievements,
      weeks: this.buildWeeks(),
      ringPct: an ? 320 : 0,
    };
  }
}
</script>
</body>
</html>
