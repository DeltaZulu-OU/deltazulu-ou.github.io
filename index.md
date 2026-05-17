---
layout: default
title: DeltaZulu — Practical security engineering
description: DeltaZulu OÜ is a small technology company based in Tallinn, Estonia, focused on cybersecurity, infrastructure, and defensive engineering.
---

<section class="hero">
  <div class="container">
    <div class="hero-head">
      <span class="eyebrow">DeltaZulu OÜ · Tallinn, Estonia</span>
      <h1 class="display">Practical security engineering for infrastructure that has to hold.</h1>
      <p class="lead">DeltaZulu is a small technology company focused on cybersecurity, infrastructure, and defensive engineering. We build tools and operational practice for teams that need their systems to keep working under pressure — not theatre, not buzzwords, not generic dashboards.</p>
      <div class="hero-actions">
        <a class="button button-primary" href="#contact">
          Contact us
          <span class="arrow" aria-hidden="true">→</span>
        </a>
        <a class="button button-secondary" href="https://github.com/DeltaZulu-OU" target="_blank" rel="noopener noreferrer">View on GitHub</a>
      </div>
    </div>

    <div class="hero-meta" aria-label="Company at a glance">
      <div class="hero-meta-item">
        <div class="k">Based in</div>
        <div class="v serif">Tallinn, Estonia</div>
      </div>
      <div class="hero-meta-item">
        <div class="k">Practice</div>
        <div class="v serif">Cybersecurity &amp; infrastructure</div>
      </div>
      <div class="hero-meta-item">
        <div class="k">Posture</div>
        <div class="v serif">Defensive, calibrated</div>
      </div>
      <div class="hero-meta-item">
        <div class="k">Status</div>
        <div class="v">FOSS active · Commercial follows</div>
      </div>
    </div>
  </div>
</section>

<section class="block" id="practice">
  <div class="container">
    <div class="section-head">
      <div class="section-head-left">
        <span class="eyebrow">Practice</span>
        <h2 class="section-title">Three areas, treated as one discipline.</h2>
      </div>
      <div class="section-head-right">
        <p class="body">Cybersecurity, infrastructure, and defensive engineering are not separate motions for us. They are the same problem at different layers: keeping systems trustworthy when something unexpected hits them.</p>
      </div>
    </div>

    <div class="practice-grid">
      <article class="pillar">
        <div class="num">01</div>
        <h3>Cybersecurity</h3>
        <p class="body">Practical, evidence-led security work — not posture theatre. We focus on the controls and telemetry that actually shape outcomes during an incident, and the audit artefacts buyers can defend in a review.</p>
        <div class="chip-row">
          <span class="chip">Threat exposure</span>
          <span class="chip">DNS-layer defence</span>
          <span class="chip">Evidence outputs</span>
        </div>
      </article>

      <article class="pillar">
        <div class="num">02</div>
        <h3>Infrastructure</h3>
        <p class="body">Networks, resolvers, edge services, identity boundaries — the load-bearing parts of an organisation's stack. We design, instrument, and harden infrastructure with operational realities in mind, not just topology diagrams.</p>
        <div class="chip-row">
          <span class="chip">Network design</span>
          <span class="chip">Hybrid deploys</span>
          <span class="chip">Resolver hygiene</span>
        </div>
      </article>

      <article class="pillar">
        <div class="num">03</div>
        <h3>Defensive engineering</h3>
        <p class="body">Detection, response, drills, and the tooling that makes them survivable at small-team scale. We build for the operator who is on-call at 02:00, not for the slide-deck audience three quarters later.</p>
        <div class="chip-row">
          <span class="chip">Detection</span>
          <span class="chip">Incident drills</span>
          <span class="chip">Runbooks</span>
        </div>
      </article>
    </div>
  </div>
</section>

<section class="block" id="build">
  <div class="container">
    <div class="build-block">
      <span class="eyebrow eyebrow-inverse">What we build</span>
      <h2 class="section-title">Tools for security ops, network visibility, infrastructure assurance, and defensive testing.</h2>
      <p class="lead">Some of this work is released openly. Some becomes the basis for commercial products. The throughline is the same: instrumentation and controls a small operations team can actually run, audit, and explain.</p>

      <div class="build-grid">
        <div class="build-item">
          <div class="ix">01</div>
          <div>
            <h4>Security operations</h4>
            <p>Day-to-day tooling for detection, triage, and response — built so a small team can keep pace without drowning in vendor consoles or low-signal alerts.</p>
          </div>
        </div>
        <div class="build-item">
          <div class="ix">02</div>
          <div>
            <h4>Network visibility</h4>
            <p>Resolver telemetry, DNS-layer signals, and traffic instrumentation that make the boring parts of a network legible — well before an investigation needs them.</p>
          </div>
        </div>
        <div class="build-item">
          <div class="ix">03</div>
          <div>
            <h4>Infrastructure assurance</h4>
            <p>Controls, checks, and evidence outputs aligned to compliance regimes (NIS2, DORA-adjacent). The kind of artefacts a procurement reviewer actually reads.</p>
          </div>
        </div>
        <div class="build-item">
          <div class="ix">04</div>
          <div>
            <h4>Defensive testing</h4>
            <p>Realistic exercises, attack-path validation, and tabletop scaffolding — the unglamorous discipline that turns a written runbook into something a team trusts at 02:00.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="block" id="open-source">
  <div class="container">
    <div class="section-head">
      <div class="section-head-left">
        <span class="eyebrow">Open source</span>
        <h2 class="section-title">Some of our work is published openly.</h2>
      </div>
      <div class="section-head-right">
        <p class="body">FOSS releases are how we share the parts of our practice that are most useful to peers and downstream users. They are not the company's commercial surface — they are the operational scaffolding under it.</p>
      </div>
    </div>

    <div class="os-grid">
      <a class="repo" href="https://github.com/DeltaZulu-OU/dzmac" target="_blank" rel="noopener noreferrer">
        <div class="repo-head">
          <span class="repo-name">DeltaZulu-OU/dzmac</span>
          <span class="repo-status">Active</span>
        </div>
        <div class="repo-tagline">Spoof MAC addresses on Windows — a focused TMAC reimplementation.</div>
        <p class="body">A Windows desktop application with both GUI and CLI for managing adapter MAC addresses. A from-scratch reimplementation of Technitium MAC Address Changer with a narrower, more maintainable feature scope.</p>
        <div class="repo-foot">
          <span><span class="lang-dot" style="background:#178600;"></span> C#</span>
          <span>GPL-3.0</span>
          <span class="mono">/dzmac</span>
        </div>
      </a>

      <a class="repo" href="https://github.com/DeltaZulu-OU/dznetcut" target="_blank" rel="noopener noreferrer">
        <div class="repo-head">
          <span class="repo-name">DeltaZulu-OU/dznetcut</span>
          <span class="repo-status">Active</span>
        </div>
        <div class="repo-tagline">LAN host discovery and authorised ARP-disruption testing.</div>
        <p class="body">A Windows LAN tool (GUI + CLI) for discovering hosts and running bounded, authorised ARP-disruption sessions. Built for internal labs, defensive validation, and incident-response diagnostics on owned infrastructure.</p>
        <div class="repo-foot">
          <span><span class="lang-dot" style="background:#178600;"></span> C#</span>
          <span>GPL-3.0 · MIT</span>
          <span class="mono">/dznetcut</span>
        </div>
      </a>

      <article class="repo">
        <div class="repo-head">
          <span class="repo-name">Technitium DNS Apps</span>
          <span class="repo-status">Active</span>
        </div>
        <div class="repo-tagline">Plugins for Technitium DNS Server — telemetry export and threat-intel ingestion.</div>
        <p class="body">A pair of plugins that extend Technitium DNS Server with operational integrations: pipeline-bounded query-log export to files, HTTP, and Syslog sinks; and a connector for ingesting MISP threat-intel indicators into DNS-layer enforcement.</p>
        <div class="repo-links">
          <a href="https://github.com/DeltaZulu-OU/LogExporterApp" target="_blank" rel="noopener noreferrer">
            <span class="mono">/LogExporterApp</span>
            <span class="desc">DNS query-log exporter</span>
          </a>
          <a href="https://github.com/DeltaZulu-OU/MispConnectorApp" target="_blank" rel="noopener noreferrer">
            <span class="mono">/MispConnectorApp</span>
            <span class="desc">MISP threat-intel connector</span>
          </a>
        </div>
        <div class="repo-foot">
          <span><span class="lang-dot" style="background:#178600;"></span> C#</span>
          <span>GPL-3.0</span>
          <span class="mono">2 repos</span>
        </div>
      </article>
    </div>

    <div class="os-foot">
      <p class="note-text">Three current releases under the DeltaZulu-OU organisation. More tooling, including resolver-side telemetry and defensive-testing scaffolds, follows the same publish-when-useful cadence.</p>
      <a class="button button-secondary" href="https://github.com/DeltaZulu-OU" target="_blank" rel="noopener noreferrer">
        Browse the GitHub org
        <span class="arrow" aria-hidden="true">→</span>
      </a>
    </div>
  </div>
</section>

<section class="block block-tight commercial" id="commercial">
  <div class="container">
    <div class="section-head section-head-tight">
      <div class="section-head-left">
        <span class="eyebrow">Commercial work</span>
        <h2 class="section-title">Hosted services and commercial products follow separately.</h2>
      </div>
      <div class="section-head-right">
        <p class="body">Our open-source work is the practice. Commercial offerings are deliberately announced apart from it — when they are mature enough to defend on their own terms, with their own positioning and support obligations.</p>
      </div>
    </div>

    <div class="commercial-card">
      <div class="commercial-card-left">
        <h3>The first commercial direction is protective DNS for regulated supply chains.</h3>
        <p class="body">It builds on the same resolver-telemetry and evidence-output work that runs through our open practice. When it is ready to stand on its own page, it will have one.</p>
      </div>
      <div class="commercial-card-right">
        <div class="product-row">
          <span class="tag mono">01</span>
          <div>
            <div class="name">DZNS · Protective DNS</div>
            <div class="desc">Filtering plus governed telemetry for compliance-pressured buyers.</div>
          </div>
          <span class="status-chip">Forthcoming</span>
        </div>
        <div class="product-row">
          <span class="tag mono">02</span>
          <div>
            <div class="name">Hosted operational services</div>
            <div class="desc">Managed defensive engagements for partner-led delivery.</div>
          </div>
          <span class="status-chip">Roadmap</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="block" id="contact">
  <div class="container">
    <div class="section-head">
      <div class="section-head-left">
        <span class="eyebrow">Contact</span>
        <h2 class="section-title">Talk to us about practical defensive work.</h2>
      </div>
      <div class="section-head-right">
        <p class="body">Direct enquiries about engagements, partnerships, or our published tooling are welcome. We reply individually — no marketing funnel, no qualification gauntlet.</p>
      </div>
    </div>

    <div class="contact-grid">
      <a class="contact-card" href="mailto:info@deltazulu.ee">
        <div class="k">Email</div>
        <div class="v">info@deltazulu.ee</div>
        <p class="body">For engagement enquiries, partnerships, and direct correspondence.</p>
        <div class="contact-arrow" aria-hidden="true">→</div>
      </a>
      <a class="contact-card" href="https://github.com/DeltaZulu-OU" target="_blank" rel="noopener noreferrer">
        <div class="k">GitHub</div>
        <div class="v">github.com/DeltaZulu-OU</div>
        <p class="body">Open-source releases and the operational tooling behind our practice.</p>
        <div class="contact-arrow" aria-hidden="true">→</div>
      </a>
      <a class="contact-card" href="https://www.linkedin.com/company/deltazulu" target="_blank" rel="noopener noreferrer">
        <div class="k">LinkedIn</div>
        <div class="v">linkedin.com/company/deltazulu</div>
        <p class="body">Company updates, hiring, and longer-form posts on defensive engineering.</p>
        <div class="contact-arrow" aria-hidden="true">→</div>
      </a>
    </div>
  </div>
</section>
