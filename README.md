<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sensuii | Portfolio</title>
    <link rel="stylesheet" href="Index.css">
</head>
<body>
    <nav class="mobile-nav">
        <details>
            <summary>Menu</summary>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#experience">Experience</a>
            <a href="#skills">Skills</a>
            <a href="#references">References</a>
        </details>
    </nav>
    <div class="layout">
        <aside class="sidebar">
            <div class="profile-card">
                <img src="sensuii.jpg" alt="John Patrick Garcia" class="profile-photo">
                <h1>John Patrick Garcia</h1>
                <p class="role">IT Support & Web Developer</p>
                <p class="about-small">Hands-on with systems, web tools, and support tasks that help people work better.</p>
            </div>

            <div class="sidebar-panel">
                <h2>Contact</h2>
                <p><strong>Phone</strong><br>09086976195</p>
                <p><strong>Email</strong><br>jpatricklgarcia@gmail.com</p>
                <p><strong>Location</strong><br>New Magdalena Homes Phase 3, Lot 3 Blk 6, Purok 6, Sto. Tomas, Subic, Zambales</p>
            </div>

            <div class="sidebar-panel">
                <h2>Education</h2>
                <div class="timeline-item">
                    <strong>2022 - 2025</strong>
                    <p>BS Information Technology,<br>Jesus Reigns Christian College</p>
                </div>
                <div class="timeline-item">
                    <strong>2019 - 2021</strong>
                    <p>Humanities & Social Sciences,<br>Jesus Reigns Christian Academy</p>
                </div>
                <div class="timeline-item">
                    <strong>2018 - 2019</strong>
                    <p>Mariano Marcos Memorial High School</p>
                </div>
            </div>

            <div class="sidebar-panel">
                <h2>Languages</h2>
                <ul class="list">
                    <li>English</li>
                    <li>Filipino</li>
                </ul>
            </div>
        </aside>

        <main class="content">
            <section class="hero-card" id="home">
                <p class="eyebrow">Portfolio</p>
                <h2>John Patrick Garcia</h2>
                <p>Practical IT support and web development experience with a focus on hardware repair, software setup, and clear communication.</p>
                <div class="hero-grid">
                    <div>
                        <h3>Core focus</h3>
                        <p>Supporting users, troubleshooting systems, and building dependable website experiences.</p>
                    </div>
                    <div>
                        <h3>What I enjoy</h3>
                        <p>Building websites, fixing hardware, learning new tools, and helping teams work smoothly.</p>
                    </div>
                </div>
            </section>

            <section class="card-panel" id="about">
                <h2>About Me</h2>
                <p>I am motivated by solving real problems, improving systems, and learning through hands-on work. I enjoy combining technical troubleshooting with practical web and IT skills to support both people and processes.</p>
                <p>Whether I am setting up a new workstation, repairing a computer, or building a simple website, I focus on being reliable, careful, and easy to work with. I want my work to make daily tasks smoother for others and help teams move faster.</p>
                <p>I also enjoy learning new tools and learning from every project. This helps me grow as a professional and gives me confidence to take on new challenges in IT and web development.</p>
                <div class="list-columns">
                    <div>
                        <h3>Strengths</h3>
                        <ul class="list">
                            <li>Problem solving</li>
                            <li>Technical troubleshooting</li>
                            <li>System setup</li>
                            <li>Attention to detail</li>
                        </ul>
                    </div>
                    <div>
                        <h3>Interests</h3>
                        <ul class="list">
                            <li>Web development</li>
                            <li>Hardware repair</li>
                            <li>Process improvement</li>
                            <li>Learning new technologies</li>
                        </ul>
                    </div>
                </div>
            </section>

            <section class="card-panel" id="experience">
                <h2>Experience</h2>
                <div class="experience-item">
                    <h3>IT Intern</h3>
                    <span>February 2025 – June 2025 · CMT Holdings</span>
                    <ul class="list">
                        <li>Built PCs, repaired CPUs, installed Windows 11</li>
                        <li>Documented workflows and supported team meetings</li>
                        <li>Backed up emails and deployed Microsoft 365</li>
                        <li>Assisted accounting with data encoding and system support</li>
                    </ul>
                </div>
                <div class="experience-item">
                    <h3>Assistant Mechanic</h3>
                    <span>Vehicle maintenance support</span>
                    <ul class="list">
                        <li>Collected tools and supported repair tasks</li>
                        <li>Changed oil, brakes, and tires</li>
                        <li>Performed vulcanizing work</li>
                    </ul>
                </div>
                <div class="experience-item">
                    <h3>Room Attendant</h3>
                    <span>Subic Bay Yacht Club (SBYC), 1 Month on Call</span>
                    <ul class="list">
                        <li>Housekeeping and room cleaning</li>
                        <li>Maintained bedding and polished floors</li>
                    </ul>
                </div>
            </section>

            <section class="card-panel" id="skills">
                <h2>Skills</h2>
                <div class="skill-grid">
                    <span>HTML</span>
                    <span>CSS</span>
                    <span>PHP</span>
                    <span>Hardware Repair</span>
                    <span>Microsoft 365</span>
                    <span>Communication</span>
                </div>
            </section>

            <section class="card-panel references-panel" id="references">
                <h2>References</h2>
                <div class="reference-grid">
                    <div>
                        <strong>Padilla, Ralph</strong>
                        <p>IT Manager · CMT Holdings</p>
                        <p>09171443684</p>
                        <p>ralp.padilla@thecmtholdings.com</p>
                    </div>
                    <div>
                        <strong>Mapoy, Karlo Val</strong>
                        <p>IT Supervisor · CMT Holdings</p>
                        <p>09453207779</p>
                    </div>
                </div>
            </section>
        </main>
    </div>
</body>
</html>


:root {
    --surface: #111827;
    --surface-soft: #1f2937;
    --text: #e2e8f0;
    --text-muted: #94a3b8;
    --primary: #60a5fa;
    --primary-soft: #0f172a;
    --border: #334155;
}

* {
    box-sizing: border-box;
}

html,
body {
    margin: 0;
    min-height: 100%;
}

body {
    font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
    background: linear-gradient(180deg, #020617 0%, #111827 100%);
    color: var(--text);
}

.layout {
    display: grid;
    grid-template-columns: 320px 1fr;
    gap: 24px;
    max-width: 1180px;
    margin: 0 auto;
    padding: 28px;
}

.sidebar,
.content {
    display: grid;
    gap: 22px;
}

.profile-card,
.sidebar-panel,
.card-panel,
.hero-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 28px;
    padding: 28px;
    box-shadow: 0 18px 36px rgba(0, 0, 0, 0.25);
}

.profile-card {
    text-align: center;
}

.profile-photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    border: 6px solid var(--surface);
    box-shadow: 0 20px 40px rgba(15, 23, 42, 0.1);
    margin-bottom: 20px;
    display: block;
}

.profile-card h1 {
    margin: 0;
    font-size: 1.9rem;
    letter-spacing: -0.02em;
}

.role {
    margin: 10px 0 0;
    color: var(--primary);
    font-weight: 700;
}

.about-small {
    margin: 16px 0 0;
    color: var(--text-muted);
    line-height: 1.75;
}

.sidebar-panel h2,
.hero-card h2,
.card-panel h2 {
    margin: 0 0 18px;
    font-size: 1.2rem;
}

.sidebar-panel p,
.timeline-item p,
.hero-card p,
.card-panel p,
.experience-item span,
.reference-grid p {
    margin: 0;
    color: var(--text-muted);
    line-height: 1.8;
}

.timeline-item {
    margin-bottom: 16px;
}

.timeline-item strong,
.experience-item h3,
.reference-grid strong,
.hero-card h3 {
    display: block;
    color: var(--text);
    margin-bottom: 8px;
}

.list {
    list-style: none;
    padding: 0;
    margin: 0;
}

.list li {
    position: relative;
    padding-left: 16px;
    margin-bottom: 12px;
    color: var(--text);
}

.list li::before {
    content: "";
    position: absolute;
    left: 0;
    top: 8px;
    width: 7px;
    height: 7px;
    border-radius: 50%;
    background: var(--primary);
}

.eyebrow {
    margin: 0 0 12px;
    color: var(--primary);
    font-size: 0.78rem;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    font-weight: 700;
}

.hero-card h2 {
    margin: 0;
    font-size: clamp(2rem, 3vw, 2.8rem);
}

.hero-grid {
    display: grid;
    gap: 18px;
}

.hero-grid h3 {
    margin: 0 0 10px;
    font-size: 1rem;
}

.hero-grid div {
    background: var(--surface-soft);
    border-radius: 18px;
    padding: 18px;
}

.card-panel {
    display: grid;
    gap: 18px;
}

.list-columns {
    display: grid;
    gap: 18px;
}

.list-columns h3 {
    margin: 0 0 12px;
    font-size: 1rem;
}

.experience-item {
    display: grid;
    gap: 12px;
    padding: 18px;
    background: var(--surface-soft);
    border-radius: 20px;
}

.experience-item span {
    color: var(--text-muted);
}

.skill-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 12px;
}

.skill-grid span {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 14px 16px;
    border-radius: 999px;
    background: var(--surface-soft);
    color: var(--text);
    font-weight: 600;
}

.references-panel {
    padding-bottom: 24px;
}

.reference-grid {
    display: grid;
    gap: 16px;
}

.reference-grid > div {
    padding: 18px;
    background: var(--surface-soft);
    border-radius: 18px;
}

@media (max-width: 1000px) {
    .mobile-nav {
        display: block;
    }

    .layout {
        grid-template-columns: 1fr;
        padding: 20px;
    }

    .sidebar {
        order: 2;
    }

    .content {
        order: 1;
    }

    .hero-card,
    .card-panel,
    .sidebar-panel,
    .profile-card {
        padding: 24px;
    }

    .hero-grid {
        grid-template-columns: 1fr;
    }

    .skill-grid {
        grid-template-columns: 1fr;
    }
}

.mobile-nav {
    display: none;
    background: rgba(17, 24, 39, 0.96);
    color: var(--text);
    padding: 12px 20px;
    border-bottom: 1px solid rgba(148, 163, 184, 0.18);
}

.mobile-nav details {
    cursor: pointer;
}

.mobile-nav summary {
    list-style: none;
    font-weight: 700;
    font-size: 0.95rem;
}

.mobile-nav summary::-webkit-details-marker {
    display: none;
}

.mobile-nav a {
    display: block;
    margin: 10px 0 0;
    color: var(--text);
    text-decoration: none;
    padding: 8px 0;
    border-top: 1px solid rgba(148, 163, 184, 0.18);
}

.mobile-nav a:first-of-type {
    margin-top: 12px;
    border-top: none;
}

.mobile-nav a:hover {
    color: var(--primary);
}

@media (max-width: 660px) {
    body {
        font-size: 0.95rem;
    }

    .layout {
        padding: 14px;
    }

    .profile-photo {
        width: 130px;
        height: 130px;
    }

    .hero-card,
    .card-panel,
    .sidebar-panel,
    .profile-card {
        padding: 20px;
    }

    .hero-card h2 {
        font-size: 2rem;
    }

    .skill-grid {
        grid-template-columns: 1fr;
    }

    .reference-grid {
        grid-template-columns: 1fr;
    }
}
