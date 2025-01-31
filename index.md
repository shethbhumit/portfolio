---
layout: default
title: Portfolio
---

<h1>Portfolio</h1>

<!-- Navigation Buttons -->
<div class="button-container">
    <button onclick="showSection('supply-chain')">Supply Chain Analytics</button>
    <button onclick="showSection('six-sigma')">Lean Six Sigma</button>
    <button onclick="showSection('deep-learning')">Deep Learning / LLM</button>
    <button onclick="showSection('machine-learning')">Machine Learning</button>
    <button onclick="showSection('nlp')">Natural Language Processing</button>
    <button onclick="showSection('data-viz')">Data Visualization</button>
    <button onclick="showSection('people-analytics')">People Analytics</button>
</div>

<!-- Dynamic Content Sections -->
<div id="supply-chain" class="content-section">{% include supply-chain.md %}</div>
<div id="six-sigma" class="content-section" style="display:none;">{% include six-sigma.md %}</div>
<div id="deep-learning" class="content-section" style="display:none;">{% include deep-learning.md %}</div>
<div id="machine-learning" class="content-section" style="display:none;">{% include machine-learning.md %}</div>
<div id="nlp" class="content-section" style="display:none;">{% include nlp.md %}</div>
<div id="data-viz" class="content-section" style="display:none;">{% include data-viz.md %}</div>
<div id="people-analytics" class="content-section" style="display:none;">{% include people-analytics.md %}</div>
