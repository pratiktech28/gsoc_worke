[![Physics Validation CI](https://github.com/pratiktech28/gsoc_worke/actions/workflows/main.yml/badge.svg)](https://github.com/pratiktech28/gsoc_worke/actions/workflows/main.yml)

<img width="600" height="73" alt="download" src="https://github.com/user-attachments/assets/28b100c6-5029-4377-a1c9-058108523009" />

<img width="307" height="164" alt="download" src="https://github.com/user-attachments/assets/b12e084e-02f3-45c3-b922-709006ea4ce0" />

![download](https://github.com/user-attachments/assets/3ac69d7a-cc0a-49c6-823e-dd7f6718f8ab)



<div align="center">
  <h1>🔱 gprMax Physics Validation & Automation Suite 🚀</h1>
  <p><strong>Architecting an automated CI/CD pipeline for physics-driven electromagnetic wave simulations.</strong></p>
</div>

<hr />

<h3>🚀 Core Automation Features</h3>
<div>
  <ul>
    <li><strong>Automated Physics Testing:</strong> Every <code>push</code> triggers a Python suite that compares current simulations against "Golden" reference data.</li>
    <li><strong>NRMSE Validation:</strong> High-precision error calculation using <strong>Normalized Root Mean Square Error</strong> to ensure 2% threshold compliance.</li>
    <li><strong>Visual Artifact Generation:</strong> Automated creation of <code>physics_report.png</code> for visual wave analysis.</li>
  </ul>
</div>

<hr />

<h3>🔱 Implementation Details</h3>

<div style="background-color: #f6f8fa; padding: 15px; border-radius: 6px;">
  <p><strong>1. Physics Kernel Logic:</strong></p>
  <p>The validation script ensures model convergence using the following mathematical approach:</p>
  <p align="center">
    <em>RMSE = √mean((ref - sim)²)</em> <br>
    <strong>NRMSE = RMSE / (max(ref) - min(ref))</strong>
  </p>
</div>

<br />

<div>
  <p><strong>2. CI/CD Workflow (GitHub Actions):</strong></p>
  <p>The pipeline operates on a <strong>Fail-Safe</strong> mechanism to prevent regression in kernel optimization.</p>
</div>

<hr />

<h3>📊 Project Roadmap & Execution</h3>

<table width="100%">
  <thead>
    <tr align="left">
      <th><strong>Milestone</strong></th>
      <th><strong>Task Description</strong></th>
      <th><strong>Status</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>01</strong></td>
      <td>Basic GitHub Actions Setup</td>
      <td>✅ <strong>COMPLETED</strong></td>
    </tr>
    <tr>
      <td><strong>02</strong></td>
      <td>NRMSE Physics Logic Integration</td>
      <td>✅ <strong>COMPLETED</strong></td>
    </tr>
    <tr>
      <td><strong>03</strong></td>
      <td>Automated Artifact Generation</td>
      <td>🔄 <em>IN_PROGRESS</em></td>
    </tr>
    <tr>
      <td><strong>04</strong></td>
      <td>Parallel Pad Simulation Scaling</td>
      <td>📅 <em>PLANNED</em></td>
    </tr>
  </tbody>
</table>

<br />

<div align="center">
  <p><em>Built with Passion by Pratik Sharma | GSoC 2026 Contributor</em></p>
</div>
