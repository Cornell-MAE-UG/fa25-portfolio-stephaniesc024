--- 
layout: project
title: SLF Prototype
--- 


<p><b>Table of Contents</b></p>
<ul>
  <li><a href="#client-pitch">Client Pitch</a></li>
  <li><a href="#functional-prototype">Functional Prototype</a></li>
</ul>
<hr>
<h2 id="client-pitch">Client Pitch</h2>
<p align="center"><b>Problem Statement</b></p>
<p>During mechanical grape harvest, spotted lantern flies (SLF) remain on the vines and can be collected with the fruit, contaminating loads. Even minimal contamination is unacceptable: as few as 1–2 SLFs (~0.5–1 g each) can contaminate a 1000 g core sample, triggering shipment rejection. With deliveries occurring every 10 minutes at roughly 22 tons per load, a single rejected shipment results in substantial product loss, contributing to an estimated $14.3 million of damages across the Lake Erie and Finger Lakes regions in the first three years of infestation. Current solutions, such as chemical treatments or post-harvest separation, are either ineffective during active harvest, reduce yield, or are operationally inefficient. The challenge is therefore to deter SLF from vines before or during harvest, or to separate them from harvested material, without damaging grape quality or reducing yield.</p>
<hr>
<p align="center"><b>Why This Matters to the End-User</b></p>
<p>Solving this problem would allow vineyards to avoid yield loss from post-harvest washing, reduce SLF contamination in harvested loads, and eliminate the need for additional chemical treatments during a critical harvest window. By preventing shipment rejections and harvest slowdowns, the solution would preserve grape quality, protect the winery's reputation, and reduce significant economic losses.</p>
<hr>
<p align="center"><b>Proposed Directions</b></p>
<p><b>Smoke Machine Attached to Harvester</b> — Attach a smoke (or similar gas) delivery system to the front of the harvester to temporarily deter SLFs from the vines immediately before harvest. The goal is to use a non-lethal substance to clear the vines without relying on pesticides, potentially by rerouting harvester exhaust or using a small gas canister with forward-facing nozzles. Key risks/unknowns include whether SLFs will consistently fly away when exposed to smoke or exhaust, whether exposure could affect grape quality, and whether harvesters have sufficient space and power capacity to support the system.</p>
<p><b>Bristles as a Filter</b> — Install a system of brush bristles along the inner conveyor of the harvester to mechanically filter SLFs from grapes immediately after harvest. The bristles would comb over the harvested material, allowing grapes and juice to pass while removing SLFs from the harvest. Key risks/unknowns include whether the bristles can reliably filter out SLFs without blocking or damaging grapes, and whether they are durable enough for long-term use.</p>
<hr>
<p align="center"><b>Our Questions</b></p>
<ul>
  <li><b>Will SLF consistently disperse when exposed to smoke or exhaust?</b> — Determines whether or not we move forward with the gas or bristle solution.</li>
  <li><b>Are there grape regulatory or flavor concerns regarding smoke or gas exposure?</b> — Clarifies feasibility of the smoke solution, ensuring regulations and flavor are not compromised.</li>
  <li><b>Given a known deterrent, how long will it take for SLFs to return to the vines?</b> — Important for designing the potency, speed, and distribution of our solution.</li>
  <li><b>What are the constraints to the modification of the harvester?</b> — Ensures feasibility of attaching a tank to the front of the harvester.</li>
  <li><b>Is there space in the internal compartment of most grape harvesters to add enough bristles to be an effective filter?</b> — Determines whether we move forward with the bristle solution.</li>
</ul>
<hr>
<p align="center"><b>Works Cited</b></p>
<p>Bekelja, K., &amp; Russo, J. <em>Spotted Lanternfly Discussion</em>. Zoom meeting recording, MAE 2250, Spring 2026.</p>
<p>Cornell University. "<a href="https://news.cornell.edu/stories/2025/01/spotted-SLFs-could-cost-nys-grape-industry-millions">Spotted SLFs Could Cost NYS Grape Industry Millions.</a>" <em>Cornell Chronicle</em>, January 2025.</p>
<hr>

<h2 id="functional-prototype">Functional Prototype</h2>

<p align="center"><b>Purpose of the Prototype</b></p>

<p>This functional prototype focuses on the gear-driven rotation system for gas dispersion — the core mechanical mechanism of our smoke-based SLF deterrent. The goal was to verify that a handle-driven spur gear system could reliably rotate a nozzle through a constrained 90-degree range of motion, smoothly and repeatedly, simulating how the nozzle would sweep gas across grape vines during harvest.</p>

<hr>

<p align="center"><b>Design Documentation</b></p>

<p><b>Parts List</b></p>

<table>
  <thead>
    <tr>
      <th>Part</th>
      <th>McMaster Code</th>
      <th>Qty</th>
      <th>Unit Cost</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Steel Hex Head Screw for Wood, Zinc-Plated, M12 × 45mm</td><td>97498A172</td><td>1</td><td>$9.43</td><td></td></tr>
    <tr><td>Vibration-Damping Routing Clamp, Zinc-Plated, 7/8" ID</td><td>11355T26</td><td>2</td><td>$4.15</td><td></td></tr>
    <tr><td>Black-Oxide Alloy Steel Socket Head Screw, 10-24, 5/16" Long</td><td>91864A032</td><td>1</td><td>$6.12</td><td>Pack of 10</td></tr>
    <tr><td>4" diameter PLA Printed Gears</td><td>60455K51</td><td>2</td><td>$3.99</td><td>RPL Printed</td></tr>
    <tr><td>Soft Masterkleer PVC Tubing, 1" ID, 1-1/2" OD</td><td>5233K48</td><td>2</td><td>$9.88</td><td>Found in Recycling</td></tr>
    <tr><td>Push-to-Connect Fitting, 1/4" Tube Stem OD, 3/16" Barb</td><td>51055K57</td><td>1</td><td>$2.21</td><td>Found in Recycling</td></tr>
    <tr><td>1/2" × 12" Wooden Slabs</td><td>—</td><td>1</td><td>$3.00</td><td>Taylor Design Studio</td></tr>
    <tr><td>24" Wooden Shaft, 1/4" diameter</td><td>—</td><td>1</td><td>$3.00</td><td>Taylor Design Studio</td></tr>
    <tr><td>Tape</td><td>—</td><td>1</td><td>$0.00</td><td></td></tr>
    <tr><td><b>Total</b></td><td></td><td></td><td><b>$59.80</b></td><td></td></tr>
  </tbody>
</table>

<p><p>
<p><b>Fabrication Steps</b></p>

<ol>
  <li>Cut the 12" × 12" wooden slab into three equal-width sections and glue them together with wood glue, clamped at four corners for 24 hours.</li>
  <li>Cut the PVC tube to approximately 8 inches to reduce excess and keep the mechanism manageable.</li>
  <li>Cut the 24" wooden shaft into four 6-inch pieces for rotation constraints, and one 8-inch piece to serve as a handle.</li>
  <li>3D printed two 4" spur gears from McMaster CAD at the RPL, with a larger center hole added to reduce rotational inertia.</li>
  <li>Drill 27/64" holes into the wooden base for the gear axles and glue them in place. Push the wooden shafts through the gears so they can freely rotate.</li>
  <li>Attach the 8" PVC tube horizontally to one gear using tape (clamps received were an incorrect dimension).</li>
  <li>Attach the 8" wooden shaft horizontally to the other gear using tape to serve as the handle.</li>
  <li>Drill 1/4" holes on each side of the handle shaft and glue in the two 6-inch wooden shafts as rotation constraints.</li>
</ol>

<p><b>Design vs. Fabrication Discrepancies</b></p>

<ul>
  <li><em>Tape instead of clamps:</em> The clamps ordered were much larger than expected due to a miscommunication between tube radius and diameter. The team has since standardized on always communicating using diameter (the engineering convention).</li>
  <li><em>No wood screws through gear centers:</em> The screw order was delayed. To prevent this in the future, the team will push forward ordering deadlines on the project schedule.</li>
</ul>


<p align="center">
  <img src="/fa25-portfolio-stephaniesc024/assets/images/prototypesketch.jpg" alt="Prototype front view" width="600">
</p>
<p><b>Assembly Instructions</b></p>

<ol>
  <li>Fasten both gears to the wooden board with screws so their teeth mesh together.</li>
  <li>Fasten the PVC tube for gas dispersion to one gear.</li>
  <li>Fasten the handle to the other gear to allow for controlled rotation.</li>
  <li>Insert wooden constraint shafts into the wooden board to limit the rotation range of the gears.</li>
</ol>

<hr>

<p align="center"><b>Design Tests</b></p>

<p><b>Test 1: Rotation Smoothness</b></p>
<ul>
  <li><em>Part tested:</em> Gears</li>
  <li><em>What it tests:</em> Whether the handle-driven gears rotate the nozzle smoothly without binding, slipping, or excessive friction</li>
  <li><em>Method:</em> Handle was rotated through the full range of motion while observing gear motion for slip, jerky motion, or interference</li>
  <li><em>Results:</em> 20 full 360° rotations completed with no slippage or binding. Proper gear placement was necessary to achieve this.</li>
  <li><em>Conclusion:</em> To allow slight tolerance for positioning error, gear tooth height will be increased by 5 mm in the next iteration.</li>
</ul>

<p><b>Test 2: Aiming Range</b></p>
<ul>
  <li><em>Part tested:</em> Tube/Nozzle</li>
  <li><em>What it tests:</em> Whether the gear system allows the nozzle to cover the desired sweep range</li>
  <li><em>Method:</em> Handle was turned from one extreme to the other and total angular rotation of the nozzle was measured</li>
  <li><em>Results:</em> 10 full back-and-forth cycles completed, achieving a constrained range of motion of 90° with 0 instances of slipping or binding.</li>
  <li><em>Conclusion:</em> The constraint method was effective. For greater robustness, wooden cylinder constraints will be replaced with larger-diameter aluminum rods and the base will be upgraded to aluminum.</li>
</ul>

<p><b>Test 3: Repeated-Use Durability</b></p>
<ul>
  <li><em>Part tested:</em> Screws, gears, and wooden board assembly</li>
  <li><em>What it tests:</em> Whether the mechanism maintains functionality after repeated use without loosening, slipping, or increasing friction</li>
  <li><em>Method:</em> Handle cycled a minimum of 20 times at 20 RPM while observing changes in motion smoothness, gear interface, and structural stability</li>
  <li><em>Results:</em> 20 full cycles at 20 RPM showed no clear signs of wear and tear.</li>
  <li><em>Conclusion:</em> The initial design holds up, but is primarily wood and tape. For the final design, constraint shafts and base will be converted to aluminum, and screws will replace wooden sticks for holding gears in place.</li>
</ul>

<p><b>Test 4: Tube Stability</b></p>
<ul>
  <li><em>Part tested:</em> Pipe clamp / tube attachment</li>
  <li><em>What it tests:</em> Whether the gas tube remains securely attached and doesn't interfere with nozzle rotation</li>
  <li><em>Method:</em> Tube rotated through the full range of motion observing attachment for twisting, sagging, or resistance. Painter's tape used as substitute due to clamp ordering issue.</li>
  <li><em>Results:</em> Through approximately 20 full cycles at varying speeds, painter's tape held without detaching or interfering with gear teeth.</li>
  <li><em>Conclusion:</em> Since tape is significantly weaker than the intended clamps, this gives strong confidence the proper clamps will hold once received.</li>
</ul>

<p><b>Test 5: Structural Stability</b></p>
<ul>
  <li><em>Part tested:</em> Wood mounting board</li>
  <li><em>What it tests:</em> Whether the wooden base remains rigid and maintains gear alignment during use</li>
  <li><em>Method:</em> Handle rotated through 10 full cycles at 20 RPM while a 10 N force was applied to the tube to simulate harvester stress</li>
  <li><em>Results:</em> No flexing, shifting, or misalignment observed. Gears remained tightly meshed with no slippage.</li>
  <li><em>Conclusion:</em> The base does not flex or place significant stress on the mechanism. An aluminum base will still be used in the next iteration for long-term durability.</li>
</ul>

<hr>

<p align="center"><b>Success Criteria</b></p>

<p>Our main goal for this iteration is to ensure the gear rotation system for gas dispersion is effective and durable. A successful prototype demonstrates the ability to move the nozzle in a periodic sweeping motion to achieve adequate gas dispersion across the vines.</p>

<table>
  <thead>
    <tr>
      <th>Criterion</th>
      <th>What It Assesses</th>
      <th>Measurement Method</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>After continuous testing for over 1 minute with gears spinning at least 90°, all gears spin without interference or skipping</td>
      <td>Long-term gear reliability across multiple harvests</td>
      <td>Observe gear mesh through 20+ cycles at 20 RPM; record any skipping or interference events</td>
    </tr>
    <tr>
      <td>After continuous testing for over 1 minute with gears spinning at least 90°, all parts remain structurally intact</td>
      <td>Structural durability to avoid ongoing farmer maintenance</td>
      <td>Inspect all joints, fasteners, and the base after 20+ cycles for loosening, cracking, or detachment</td>
    </tr>
    <tr>
      <td>Nozzle achieves an approximate 90° range of motion without significant resistance</td>
      <td>Effective gas dispersion sweep across the vine rows</td>
      <td>Measure angular range of nozzle travel; confirm smooth rotation with no notable friction or resistance</td>
    </tr>
  </tbody>
</table>


<p><p>
<p><b>Exhibit Demo:</b> Upon spinning the handle, the nozzle rotates through a 90° arc driven by the spur gear system — directly demonstrating the range-of-motion and smoothness criteria in a single visible action.</p>

<p align="center">
  <img src="/fa25-portfolio-stephaniesc024/assets/images/prototypepic1.jpg" alt="Prototype view 1" width="350">
  <img src="/fa25-portfolio-stephaniesc024/assets/images/prototypepic2.jpg" alt="Prototype view 2" width="350">
</p>
