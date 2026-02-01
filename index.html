<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Furkan Koruk | AR-OS v1.3.0</title>
    <script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Rajdhani:wght@500;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --neon-blue: #00f2ff;
            --neon-purple: #bc13fe;
            --terminal-green: #33ff33;
        }

        body { margin: 0; overflow: hidden; font-family: 'Rajdhani', sans-serif; }

        /* Sağ Taraf Versiyon HUD (Aynen Korundu) */
        .version-hud {
            position: fixed;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
            z-index: 1000; /* Kameranın üstünde durması için */
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .version-item {
            background: rgba(10, 11, 16, 0.8);
            border-right: 4px solid var(--neon-purple);
            padding: 10px 15px;
            display: flex;
            align-items: center;
            gap: 10px;
            font-family: 'Orbitron', sans-serif;
            font-size: 0.7rem;
            color: white;
            clip-path: polygon(10% 0, 100% 0, 100% 100%, 0% 100%);
            transition: 0.4s;
            border: 1px solid rgba(0, 242, 255, 0.2);
        }

        .version-item.active {
            border-right-color: var(--neon-blue);
            box-shadow: -5px 0 15px rgba(0, 242, 255, 0.3);
            transform: translateX(-5px);
        }

        .version-item button {
            background: #222;
            border: 1px solid var(--neon-blue);
            color: var(--neon-blue);
            cursor: pointer;
            padding: 2px 6px;
            font-family: 'Orbitron';
            font-size: 0.5rem;
        }

        /* Üst Bilgi Paneli */
        .ar-status {
            position: fixed;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 1000;
            background: rgba(0,0,0,0.7);
            color: var(--neon-blue);
            padding: 10px 20px;
            border: 1px solid var(--neon-blue);
            font-family: 'Orbitron';
            font-size: 0.8rem;
            text-align: center;
            pointer-events: none;
        }

        /* Modal / ASCII Table */
        .modal {
            display: none;
            position: fixed;
            z-index: 2000;
            left: 0; top: 0; width: 100%; height: 100%;
            background: rgba(0,0,0,0.9);
        }

        .modal-content {
            background: #050505;
            margin: 15% auto;
            padding: 20px;
            border: 1px solid var(--neon-blue);
            width: 85%; max-width: 500px;
        }

        .ascii-table {
            color: var(--terminal-green);
            font-family: 'Courier New', monospace;
            white-space: pre-wrap;
            background: #000;
            padding: 10px;
            font-size: 0.75rem;
            border: 1px solid #222;
        }

        .close-btn { color: #ff0055; float: right; cursor: pointer; font-size: 1.5rem; }
    </style>
</head>

<body>

    <div class="ar-status">
        SYSTEM: AR_MODE_ACTIVE <br>
        <span style="font-size: 0.6rem; color: #fff;">TARGET: HIRO_MARKER</span>
    </div>

    <div class="version-hud">
        <div class="version-item">
            <span>V1.1.0</span>
            <button onclick="openModal('v110')">INFO</button>
        </div>
        <div class="version-item">
            <span>V1.2.0</span>
            <button onclick="openModal('v120')">INFO</button>
        </div>
        <div class="version-item active">
            <span>V1.3.0</span>
            <button onclick="openModal('v130')">INFO</button>
        </div>
    </div>

    <div id="versionModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal()">×</span>
            <h2 style="font-family:'Orbitron'; color:var(--neon-blue); font-size:0.9rem; margin-bottom:10px;">> DEPLOYMENT_LOG</h2>
            <pre id="modalText" class="ascii-table"></pre>
        </div>
    </div>

    <a-scene embedded arjs="sourceType: webcam; debugUIEnabled: false;">
        
        <a-marker preset="hiro">
            <a-box position="0 0.5 0" 
                   material="color: #00f2ff; opacity: 0.6; transparent: true; side: double;" 
                   animation="property: rotation; to: 0 360 0; loop: true; dur: 4000">
                
                <a-box position="0 0 0" scale="0.4 0.4 0.4" 
                       material="color: #bc13fe; emissive: #bc13fe; emissiveIntensity: 2;">
                </a-box>

                <a-text value="FURKAN KORUK" position="-0.8 1 0" color="#00f2ff" width="4" font="exo2bold"></a-text>
            </a-box>

            <a-plane rotation="-90 0 0" width="1.5" height="1.5" color="#00f2ff" opacity="0.1"></a-plane>
        </a-marker>

        <a-entity camera></a-entity>
    </a-scene>

    <script>
        const versionData = {
            'v110': `
+---------------------------------------+
| NEON INTERFACE - v1.1.0               |
+---------------------------------------+
| [OK] Cyberpunk UI Elements            |
| [OK] HUD Side Panel                   |
+---------------------------------------+`,

            'v120': `
+---------------------------------------+
| TECH MODULES - v1.2.0                 |
+---------------------------------------+
| [OK] Unity/C#/Python Bars             |
| [OK] Power Level Integration          |
+---------------------------------------+`,

            'v130': `
+---------------------------------------+
| AR EXPANSION - v1.3.0                 |
+---------------------------------------+
| [NEW] Augmented Reality Core          |
| [NEW] 3D Neon Cube Projection         |
| [NEW] Hiro Marker Recognition         |
+---------------------------------------+
| STATUS: AUGMENTED REALITY ONLINE      |
+---------------------------------------+`
        };

        function openModal(ver) {
            document.getElementById('modalText').innerText = versionData[ver];
            document.getElementById('versionModal').style.display = "block";
        }

        function closeModal() {
            document.getElementById('versionModal').style.display = "none";
        }

        window.onclick = function(event) {
            if (event.target == document.getElementById('versionModal')) closeModal();
        }
    </script>
</body>
</html>
