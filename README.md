<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JEE Notes and Important Topics</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .container { max-width: 800px; margin: auto; padding: 20px; }
        .notes { text-align: left; }
        a { display: block; margin: 10px 0; color: blue; text-decoration: none; }
        .content { display: none; text-align: left; background: #f0f0f0; padding: 10px; margin: 10px 0; }
        .sub-section { display: none; background: #e0e0e0; padding: 10px; margin: 5px 0; }
    </style>
    <script>
        function toggleContent(id) {
            var content = document.getElementById(id);
            content.style.display = content.style.display === "block" ? "none" : "block";
        }
        function toggleSubSection(id) {
            var content = document.getElementById(id);
            content.style.display = content.style.display === "block" ? "none" : "block";
        }
    </script>
</head>
<body>
    <div class="container">
        <h1>JEE Notes and Important Topics</h1>
        <p>Find all subjects, chapters, and notes here:</p>
        <div class="notes">
            <h2>Subjects</h2>
            <a href="#" onclick="toggleContent('physics')">Physics</a>
            <a href="#" onclick="toggleContent('chemistry')">Chemistry</a>
            <a href="#" onclick="toggleContent('mathematics')">Mathematics</a><div id="physics" class="content">
            <h3>Physics Chapters</h3>
            <a href="#" onclick="toggleContent('kinematics')">Kinematics</a>
            <a href="#" onclick="toggleContent('laws_of_motion')">Laws of Motion</a>
            <a href="#" onclick="toggleContent('thermodynamics')">Thermodynamics</a>
            <div id="kinematics" class="sub-section">
                <h4>Options</h4>
                <a href="#" onclick="toggleSubSection('kinematics_short')">Short Notes</a>
                <a href="#" onclick="toggleSubSection('kinematics_formulas')">Formulas</a>
                <div id="kinematics_short" class="sub-section">
                    <p>Short Notes: Motion in one, two, and three dimensions.</p>
                </div>
                <div id="kinematics_formulas" class="sub-section">
                    <ul>
                        <li>v = u + at</li>
                        <li>s = ut + ½at²</li>
                        <li>v² = u² + 2as</li>
                    </ul>
                </div>
            </div>
            <div id="laws_of_motion" class="sub-section">
                <h4>Options</h4>
                <a href="#" onclick="toggleSubSection('laws_of_motion_short')">Short Notes</a>
                <a href="#" onclick="toggleSubSection('laws_of_motion_formulas')">Formulas</a>
                <div id="laws_of_motion_short" class="sub-section">
                    <p>Short Notes: Newton's three laws of motion.</p>
                </div>
                <div id="laws_of_motion_formulas" class="sub-section">
                    <ul>
                        <li>F = ma</li>
                        <li>First Law: Inertia</li>
                        <li>Third Law: Action = Reaction</li>
                    </ul>
                </div>
            </div>
            <div id="thermodynamics" class="sub-section">
                <h4>Options</h4>
                <a href="#" onclick="toggleSubSection('thermodynamics_short')">Short Notes</a>
                <a href="#" onclick="toggleSubSection('thermodynamics_formulas')">Formulas</a>
                <div id="thermodynamics_short" class="sub-section">
                    <p>Short Notes: Laws of thermodynamics, work, heat, and energy.</p>
                </div>
                <div id="thermodynamics_formulas" class="sub-section">
                    <ul>
                        <li>ΔU = Q - W</li>
                        <li>PV = nRT</li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="chemistry" class="content">
            <h3>Chemistry Chapters</h3>
            <a href="#" onclick="toggleContent('atomic_structure')">Atomic Structure</a>
            <a href="#" onclick="toggleContent('chemical_bonding')">Chemical Bonding</a>
            <a href="#" onclick="toggleContent('organic_chemistry')">Organic Chemistry</a>
            <div id="atomic_structure" class="sub-section">
                <h4>Options</h4>
                <a href="#" onclick="toggleSubSection('atomic_structure_short')">Short Notes</a>
                <a href="#" onclick="toggleSubSection('atomic_structure_formulas')">Formulas</a>
                <div id="atomic_structure_short" class="sub-section">
                    <p>Short Notes: Structure of atom, Bohr model, and quantum mechanics.</p>
                </div>
                <div id="atomic_structure_formulas" class="sub-section">
                    <ul>
                        <li>E = -13.6/n² eV</li>
                        <li>λ = h/mv (de Broglie)</li>
                    </ul>
                </div>
            </div>
            <div id="chemical_bonding" class="sub-section">
                <h4>Options</h4>
                <a href="#" onclick="toggleSubSection('chemical_bonding_short')">Short Notes</a>
                <a href="#" onclick="toggleSubSection('chemical_bonding_formulas')">Formulas</a>
                <div id="chemical_bonding_short" class="sub-section">
                    <p>Short Notes: Types of chemical bonds: ionic, covalent, metallic.</p>
                </div>
                <div id="chemical_bonding_formulas" class="sub-section">
                    <ul>
                        <li>Bond Order = ½ (No. of bonding electrons - No. of anti-bonding electrons)</li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="mathematics" class="content">
            <h3>Mathematics Chapters</h3>
            <a href="#" onclick="toggleContent('quadratic_equations')">Quadratic Equations</a>
            <a href="#" onclick="toggleContent('trigonometry')">Trigonometry</a>
            <a href="#" onclick="toggleContent('calculus')">Calculus</a>
            <div id="quadratic_equations" class="sub-section">
                <h4>Options</h4>
                <a href="#" onclick="toggleSubSection('quadratic_short')">Short Notes</a>
                <a href="#" onclick="toggleSubSection('quadratic_formulas')">Formulas</a>
                <div id="quadratic_short" class="sub-section">
                    <p>Short Notes: Solving quadratic equations using factorization, completing the square, and quadratic formula.</p>
                </div>
                <div id="quadratic_formulas" class="sub-section">
                    <ul>
                        <li>x = (-b ± √(b²-4ac)) / 2a</li>
    </ul>
                </div>
            </div>
            <div id="trigonometry" class="sub-section">
                <h4>Options</h4>
                <a href="#" onclick="toggleSubSection('trigonometry_short')">Short Notes</a>
                <a href="#" onclick="toggleSubSection('trigonometry_formulas')">Formulas</a>
                <div id="trigonometry_short" class="sub-section">
                    <p>Short Notes: Trigonometric ratios and their applications in solving triangles.</p>
                </div>
                <div id="trigonometry_formulas" class="sub-section">
                    <ul>
                        <li>sin²θ + cos²θ = 1</li>
                        <li>tanθ = sinθ/cosθ</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

</body
