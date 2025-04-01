<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JEE Notes and Important Topics</title>
    <style>
        body { font-family: Arial, sans-serif; text-align:  center; }
        .container { max-width: 800px; margin: auto; padding: 20px; }
        .notes { text-align: left; }
        a { display: block; margin: 10px 0; color: blue; text-decoration: none; }
        .content { display: none; text-align: left; background: #f0f0f0; padding: 10px; margin: 10px 0; }
    </style>
    <script>
        function toggleContent(id) {
            var content = document.getElementById(id);
            content. style.display = content. style.display === "block" ? "none" : "block";
        }
    </script>
</head>
<body>
    <div class="container">
        <h1>JEE Notes and Important Topics</h1>
        <p>Find all chapters' notes and short notes here:</p>
        <div class="notes">
            <h2>Physics</h2>
            <a href="#" on click="toggleContent('kinematics')">Kinematics</a>
            <div id="kinematics" class="content">
                <p><strong>Notes:</strong> Kinematics deals with the motion of objects without considering the forces causing the motion.</p>
                <ul>
                    <li>v = u + at</li>
                    <li>s = ut + ½at²</li>
                    <li>v² = u² + 2as</li>
                </ul>
            </div><a href="#" on click="toggleContent('laws_of_motion')">Laws of Motion</a>
        <div id="laws_of_motion" class="content">
            <p><strong>Notes:</strong> Newton’s three laws of motion describe the relationship between a body and the forces acting on it.</p>
            <ul>
                <li>First Law: Law of Inertia</li>
                <li>Second Law: F = ma</li>
                <li>Third Law: Action = Reaction</li>
            </ul>
        </div>
        
        <a href="#" on click="toggleContent('thermodynamics')">Thermodynamics</a>
        <div id="thermodynamics" class="content">
            <p><strong>Notes:</strong> Thermodynamics deals with heat, work, and energy transformations.</p>
            <ul>

                <li>First Law: ΔU = Q - W</li>
                <li>Second Law: Entropy always increases</li>
                <li>PV = nRT (Ideal Gas Equation)</li>
            </ul>
        </div>
        
        <h2>Chemistry</h2>
        <a href="#" on 

click="toggleContent('atomic_structure')">Atomic Structure</a>
        <div id="atomic_structure" class="content">
            <p><strong>Notes:</strong> Atomic structure explains the composition of atoms, including protons, neutrons, and electrons.</p>
            <ul>
                <li>Bohr’s energy levels: E = -13.6/n² eV</li>
                <li>de Broglie Wavelength: λ = h/mv</li>
            </ul>
        </div>
        
        <a href="#" on click="toggleContent('chemical_bonding')">Chemical Bonding</a>
        <div id="chemical_bonding" class="content">
            <p><strong>Notes:</strong> Chemical bonding explains how atoms combine to form molecules.</p>
            <ul>
                <li>Ionic Bonding</li>
                <li>Covalent Bonding</li>
                <li>VSEPR Theory</li>
            </ul>
        </div>
        
        <h2>Mathematics</h2>
        <a href="#" on click="toggleContent('quadratic_equations')">Quadratic Equations</a>
        <div id="quadratic_equations" class="content">
            <p><strong>Notes:</strong> A quadratic equation is of the form ax² +bx + c = 0.</p>
            <ul>
                <li>Roots: x = (-b ± √(b²-4ac)) / 2a</li>
                <li>Sum of roots: -b/a</li>
                <li>Product of roots: c/a</li>
            </ul>
        </div>
        
        <a href="#" on click="toggleContent('trigonometry')">Trigonometry</a>
        <div id="trigonometry" class="content">
            <p><strong>Notes:</strong> Trigonometry deals with relationships between angles and sides of triangles.</p>
            <ul>
                <li>sin²θ + cos²θ = 1</li>
                <li>tanθ = sinθ/cosθ</li>
                <li>sin(90°- θ) = cosθ</li>
            </ul>
        </div>
    </div>
</div>

</body>
</html>
