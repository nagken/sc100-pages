# Flashcards - SC-100

> Click any card to reveal the answer. Use the Domain pager bottom-right to switch between exam areas.

<section class="fc-section" data-fc-title="Design Zero Trust Strategy and Architecture">
<h2>1 - Design Zero Trust Strategy and Architecture</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Six Zero Trust pillars?</div><div class="fc-a">Identity, Endpoints, Apps, Data, Infrastructure, Network.</div></div>

<div class="flashcard"><div class="fc-q">What is MCRA?</div><div class="fc-a">Microsoft Cybersecurity Reference Architectures - the diagram set mapping all MS security products to Zero Trust pillars.</div></div>

<div class="flashcard"><div class="fc-q">What replaced the Azure Security Benchmark?</div><div class="fc-a">Microsoft Cloud Security Benchmark (MCSB) - multi-cloud.</div></div>

<div class="flashcard"><div class="fc-q">Three phases of ransomware strategy?</div><div class="fc-a">Prepare (immutable backup, PIM, EDR), limit blast radius (tier-0 isolation, segmentation), recover (clean-room rebuild).</div></div>

<div class="flashcard"><div class="fc-q">Where do you start a Zero Trust journey?</div><div class="fc-a">Identity - it is foundational and unlocks downstream pillars.</div></div>

<div class="flashcard"><div class="fc-q">CAF Secure vs WAF Security?</div><div class="fc-a">CAF Secure = methodology for the journey; WAF Security = architectural quality attributes for the workload.</div></div>

<div class="flashcard"><div class="fc-q">Two outputs of a security strategy engagement?</div><div class="fc-a">Target-state architecture (MCRA-mapped) and prioritized roadmap with quick wins + long-term initiatives.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Evaluate GRC Strategies and Security Operations">
<h2>2 - Evaluate GRC Strategies and Security Operations</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Where do you see PCI-DSS compliance posture in Azure?</div><div class="fc-a">Defender for Cloud -> Regulatory compliance dashboard.</div></div>

<div class="flashcard"><div class="fc-q">What controls regulatory compliance evaluation in DfC?</div><div class="fc-a">Built-in Azure Policy initiatives mapped to standards.</div></div>

<div class="flashcard"><div class="fc-q">Difference between Sentinel and Defender XDR?</div><div class="fc-a">Sentinel = custom SIEM/SOAR for any source; XDR = native automated MS detection + response.</div></div>

<div class="flashcard"><div class="fc-q">What is Defender Experts for Hunting?</div><div class="fc-a">Managed proactive threat-hunting service; MS analysts work in your tenant.</div></div>

<div class="flashcard"><div class="fc-q">First step in IR maturity model?</div><div class="fc-a">Have an IR plan (NIST 800-61) and rehearse it (tabletop exercises).</div></div>

<div class="flashcard"><div class="fc-q">Where do you author SOAR logic?</div><div class="fc-a">Sentinel playbooks (Logic Apps) triggered by automation rules.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Design Security for Infrastructure">
<h2>3 - Design Security for Infrastructure</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">How do you secure a non-Azure VM with Microsoft tooling?</div><div class="fc-a">Onboard via Azure Arc + enable Defender for Servers Plan 2 -> auto-installs MDE.</div></div>

<div class="flashcard"><div class="fc-q">What does Defender for Containers protect?</div><div class="fc-a">AKS posture, image scans (ACR), admission control, runtime detections.</div></div>

<div class="flashcard"><div class="fc-q">Difference between Enterprise IoT and OT in Defender for IoT?</div><div class="fc-a">OT = passive sensor on industrial network; Enterprise IoT = managed via Defender XDR for printers/IP cams/etc.</div></div>

<div class="flashcard"><div class="fc-q">Where do you see AWS/GCP posture in Microsoft tooling?</div><div class="fc-a">Defender for Cloud after enabling the multicloud connector.</div></div>

<div class="flashcard"><div class="fc-q">What is Just-in-Time VM access?</div><div class="fc-a">Defender for Servers feature - opens NSG ports temporarily on demand and approval.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Design Strategy for Data and Applications">
<h2>4 - Design Strategy for Data and Applications</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Three states of data and their controls?</div><div class="fc-a">At rest (encryption + CMK), in transit (TLS), in use (confidential computing TEE).</div></div>

<div class="flashcard"><div class="fc-q">CMK vs BYOK?</div><div class="fc-a">CMK = key generated/managed in Azure under customer control. BYOK = key generated outside and imported.</div></div>

<div class="flashcard"><div class="fc-q">What is double-key encryption?</div><div class="fc-a">Two keys - one Microsoft, one customer-controlled - both required to decrypt. For highly regulated data.</div></div>

<div class="flashcard"><div class="fc-q">What is Defender for DevOps?</div><div class="fc-a">Pipeline posture across GitHub + Azure DevOps surfaced in Defender for Cloud.</div></div>

<div class="flashcard"><div class="fc-q">How do you prevent secret leakage in repos?</div><div class="fc-a">GitHub Advanced Security secret scanning + push protection.</div></div>

<div class="flashcard"><div class="fc-q">What is Microsoft Purview Insider Risk Management?</div><div class="fc-a">Behavioral analytics for risky user actions (data theft, security violations) - signal sources include HR, M365, devices.</div></div>

</div>
</section>

---

[Master Index](00-MASTER-INDEX.md)
