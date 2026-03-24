<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dharti Dhan Urban Bank | Live Cloud System</title>
    <style>
        :root { --primary: #1b5e20; --soil: #4e342e; --gold: #fbc02d; --glass: rgba(255, 255, 255, 0.98); }
        
        body {
            margin: 0; font-family: 'Segoe UI', Tahoma, sans-serif;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url("https://images.unsplash.com/photo-1500382017468-9049fed747ef?q=80&w=2000") no-repeat center center fixed;
            background-size: cover; display: flex; justify-content: center; align-items: center; min-height: 100vh;
        }

        .container { width: 1200px; height: 92vh; background: var(--glass); border-radius: 30px; display: flex; box-shadow: 0 40px 80px rgba(0,0,0,0.6); overflow: hidden; }
        
        .sidebar { width: 320px; background: var(--primary); color: white; padding: 40px; display: flex; flex-direction: column; border-right: 5px solid var(--gold); }
        .nav-link { background: rgba(255,255,255,0.1); border: none; color: white; padding: 15px; margin-top: 10px; border-radius: 12px; cursor: pointer; text-align: left; font-weight: bold; transition: 0.3s; }
        .nav-link:hover { background: var(--gold); color: var(--soil); }
        
        .main-content { flex: 1; padding: 30px; overflow-y: auto; background: #fdfdfd; }
        
        .view { display: none; animation: fadeIn 0.4s ease; }
        .active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; } }

        .row { display: flex; gap: 15px; margin-bottom: 12px; }
        .col { flex: 1; }
        label { font-size: 11px; font-weight: bold; color: var(--soil); text-transform: uppercase; margin-bottom: 5px; display: block; }
        input, select { width: 100%; padding: 12px; border: 1px solid #ccc; border-radius: 10px; box-sizing: border-box; font-size: 14px; }
        .btn { background: var(--primary); color: white; padding: 16px; width: 100%; border: none; border-radius: 12px; font-weight: bold; cursor: pointer; font-size: 16px; margin-top: 10px; }
        .btn:disabled { background: #999; cursor: not-allowed; }

        .atm-card {
            width: 380px; height: 230px; background: linear-gradient(135deg, #1b5e20, #4e342e, #1b5e20);
            border-radius: 20px; color: white; padding: 25px; position: relative; margin: 20px auto;
            box-shadow: 0 15px 35px rgba(0,0,0,0.4); border: 1px solid rgba(255,255,255,0.2);
        }
        .chip { width: 50px; height: 40px; background: linear-gradient(45deg, #fbc02d, #ffeb3b); border-radius: 8px; margin: 20px 0; }
        
        table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        th, td { border: 1px solid #eee; padding: 15px; text-align: left; }
        th { background: var(--primary); color: white; }

        .pb-wrapper { border: 2px solid var(--soil); padding: 30px; background: white; display: grid; grid-template-columns: 140px 1fr 140px; gap: 20px; }
        .pb-photo { width: 130px; height: 160px; border: 2px solid #333; object-fit: cover; background: #eee; }
        .pb-sig { width: 130px; height: 50px; border-bottom: 2px solid #000; object-fit: contain; }

        @media print {
            .no-print, .sidebar { display: none !important; }
            .container { width: 100%; box-shadow: none; }
            .pb-wrapper { border: 1px solid #000; position: absolute; top: 0; left: 0; width: 100%; }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="sidebar">
        <div>
            <h1 style="color:var(--gold); margin:0; font-size:32px;">DHARTI DHAN</h1>
            <p style="letter-spacing: 2px;">Urban Bank Ltd.</p>
        </div>
        
        <div id="holderMenu" style="display:none; margin-top:40px;">
            <p style="font-size:12px; color:var(--gold);">HOLDER SERVICES</p>
            <button class="nav-link" onclick="showView('viewPassbook')">📜 Digital Passbook</button>
            <button class="nav-link" onclick="showView('viewATM')">💳 ATM Card Facility</button>
            <button class="nav-link" onclick="showView('viewStatement')">📊 Bank Statement</button>
            <button class="nav-link" style="margin-top:50px; background:var(--soil);" onclick="location.reload()">Logout</button>
        </div>
    </div>

    <div class="main-content">
        <div id="viewGate" class="view active">
            <h2 style="color:var(--primary);">Central Management System</h2>
            <div style="display:grid; grid-template-columns: 1fr 1fr; gap:20px; margin-top:40px;">
                <div style="background:white; padding:50px 20px; border-radius:25px; text-align:center; cursor:pointer; border:1px solid #ddd;" onclick="showView('viewOffLogin')">
                    <h3>BANK OFFICER</h3><p>Registration & KYC</p>
                </div>
                <div style="background:white; padding:50px 20px; border-radius:25px; text-align:center; cursor:pointer; border:1px solid #ddd;" onclick="showView('viewHoldLogin')">
                    <h3>BANK HOLDER</h3><p>Personal Banking</p>
                </div>
            </div>
        </div>

        <div id="viewOffLogin" class="view">
            <h2>Officer Login</h2>
            <input type="password" id="offPin" placeholder="Enter System PIN (1234)">
            <button class="btn" onclick="loginOfficer()">Unlock Registry</button>
        </div>

        <div id="viewReg" class="view">
            <h2 style="color:var(--primary);">Phase I: Farmer Enrollment</h2>
            <div class="row">
                <div class="col"><label>Full Name</label><input type="text" id="regName" placeholder="ROHIT RAJU KAMBLE"></div>
                <div class="col"><label>Mobile Number</label><input type="text" id="regMob" maxlength="10" placeholder="98XXXXXXXX"></div>
            </div>
            <div class="row">
                <div class="col"><label>Aadhar (12 Digit)</label><input type="text" id="regAadhar" maxlength="12" placeholder="0000 0000 0000"></div>
                <div class="col"><label>PAN Card</label><input type="text" id="regPan" placeholder="ABCDE1234F"></div>
                <div class="col"><label>Date of Birth</label><input type="date" id="regDob"></div>
            </div>
            <div class="row">
                <div class="col"><label>District</label><select id="dist" onchange="loadTalukas()"><option value="">Select District</option></select></div>
                <div class="col"><label>Taluka</label><select id="tal" onchange="setPin()"><option value="">Select Taluka</option></select></div>
                <div class="col"><label>Pincode</label><input type="text" id="regPin" readonly style="background:#eee;"></div>
            </div>
            <div class="row">
                <div class="col"><label>Passport Photo</label><input type="file" onchange="encode(this, 'pData')"></div>
                <div class="col"><label>Digital Signature</label><input type="file" onchange="encode(this, 'sData')"></div>
            </div>
            <button class="btn" id="regBtn" onclick="savePhase1()">Create Account & Sync Phase III</button>
        </div>

        <div id="viewHoldLogin" class="view">
            <h2>Phase II: Holder Login</h2>
            <input type="text" id="hId" placeholder="User ID (Last 6 of Aadhar)">
            <input type="password" id="hPass" placeholder="Password (NAME2004)">
            <button class="btn" id="loginBtn" onclick="loginHolder()">Open Vault</button>
        </div>

        <div id="viewPassbook" class="view">
            <div class="pb-wrapper">
                <img id="pbImg" class="pb-photo">
                <div style="padding: 0 20px;">
                    <h2 style="margin:0; color:var(--primary);">DHARTI DHAN BANK</h2>
                    <p style="font-size:12px; margin-bottom:20px;">Branch: <span id="pbBranch"></span> | IFSC: DDUB00412</p>
                    <p><b>Name:</b> <span id="pbName"></span></p>
                    <p><b>Mobile:</b> <span id="pbMob"></span></p>
                    <p><b>A/C No:</b> <span id="pbAc"></span></p>
                    <p><b>Customer ID:</b> <span id="pbUid"></span></p>
                </div>
                <div style="text-align:right;">
                    <img id="pbSig" class="pb-sig">
                    <p style="font-size:10px;">Auth. Signature</p>
                    <img src="https://api.qrserver.com/v1/create-qr-code/?size=80x80&data=VERIFIED" style="margin-top:20px;">
                </div>
            </div>
            <button class="btn no-print" onclick="window.print()">Print Official Passbook</button>
        </div>

        <div id="viewATM" class="view">
            <h2>Phase II: Digital ATM Facility</h2>
            <div class="atm-card">
                <div style="display:flex; justify-content:space-between; align-items:center;">
                    <span style="font-weight:bold; font-size:14px;">DHARTI DHAN URBAN BANK</span>
                    <span style="font-style:italic;">RuPay</span>
                </div>
                <div class="chip"></div>
                <div id="cardNum" style="font-size:20px; letter-spacing:4px; text-shadow:1px 1px 2px #000;">XXXX XXXX XXXX 0000</div>
                <div style="display:flex; justify-content:space-between; margin-top:20px; font-size:14px;">
                    <span id="cardName">HOLDER NAME</span>
                    <span>VAL 12/30</span>
                </div>
            </div>
        </div>

        <div id="viewStatement" class="view">
            <h2>Phase II: Bank Statement</h2>
            <table>
                <thead><tr><th>Date</th><th>Particulars</th><th>Type</th><th>Amount (₹)</th></tr></thead>
                <tbody>
                    <tr><td>24/03/2026</td><td>PM-KISAN SUBSIDY</td><td>CR</td><td>2,000.00</td></tr>
                    <tr><td>20/03/2026</td><td>FERTILIZER PURCHASE</td><td>DR</td><td>1,450.00</td></tr>
                    <tr><td>12/03/2026</td><td>GRAIN MARKET CREDIT</td><td>CR</td><td>24,500.00</td></tr>
                </tbody>
            </table>
        </div>
    </div>
</div>

<script>
    // PHASE III API LINK
    const SCRIPT_URL = "https://script.google.com/macros/s/AKfycbxucYUwlwT9mlyHvP0E0uji0keaXoNbOOgXBhCcIpJVTIVXmFvY1m2GynfBrG6HLhui/exec";

    const mhData = {
        "Ahmednagar": {"Ahmednagar": "414001", "Sangamner": "422605"},
        "Akola": {"Akola": "444001"},
        "Amravati": {"Amravati": "444601"},
        "Beed": {"Beed": "431122"},
        "Buldhana": {"Buldhana": "443001"},
        "Chhatrapati Sambhajinagar": {"Chhatrapati Sambhajinagar": "431001"},
        "Jalgaon": {"Jalgaon": "425001"},
        "Jalna": {"Jalna": "431203", "Ambad": "431204", "Bhokardan": "431114", "Partur": "431501"},
        "Latur": {"Latur": "413512"},
        "Nagpur": {"Nagpur": "440001"},
        "Nashik": {"Nashik": "422001"},
        "Pune": {"Haveli": "411001", "Baramati": "413102"},
        "Solapur": {"Solapur": "413001"},
        "Thane": {"Thane": "400601"}
    };

    let bankDB_internal = { pData:"", sData:"" };

    window.onload = () => {
        const d = document.getElementById('dist');
        Object.keys(mhData).sort().forEach(dist => d.options.add(new Option(dist, dist)));
    };

    function loadTalukas() {
        const d = document.getElementById('dist').value;
        const t = document.getElementById('tal');
        t.innerHTML = '<option value="">Select Taluka</option>';
        if(mhData[d]) Object.keys(mhData[d]).sort().forEach(tal => t.options.add(new Option(tal, tal)));
    }

    function setPin() {
        const d = document.getElementById('dist').value;
        const t = document.getElementById('tal').value;
        if(d && t) document.getElementById('regPin').value = mhData[d][t];
    }

    function showView(id) {
        document.querySelectorAll('.view').forEach(v => v.classList.remove('active'));
        document.getElementById(id).classList.add('active');
    }

    function loginOfficer() {
        if(document.getElementById('offPin').value === "1234") showView('viewReg');
        else alert("Wrong PIN!");
    }

    function encode(input, type) {
        const reader = new FileReader();
        reader.onload = (e) => { bankDB_internal[type] = e.target.result; };
        reader.readAsDataURL(input.files[0]);
    }

    // UPDATED SAVE TO GOOGLE SHEETS
    async function savePhase1() {
        const name = document.getElementById('regName').value;
        const aadhar = document.getElementById('regAadhar').value;
        const dob = document.getElementById('regDob').value;

        if(!name || !aadhar || !dob) { alert("Fill all fields!"); return; }

        const payload = {
            name: name,
            mobile: document.getElementById('regMob').value,
            aadhar: aadhar,
            pan: document.getElementById('regPan').value,
            dob: dob,
            dist: document.getElementById('dist').value,
            tal: document.getElementById('tal').value,
            pin: document.getElementById('regPin').value,
            pData: bankDB_internal.pData,
            sData: bankDB_internal.sData,
            ac: "1100" + Math.floor(100000 + Math.random()*900000),
            uid: aadhar.slice(-6),
            pass: name.substring(0,4).toUpperCase() + dob.split('-')[0]
        };

        const btn = document.getElementById('regBtn');
        btn.innerText = "Syncing with Cloud Database...";
        btn.disabled = true;

        try {
            await fetch(SCRIPT_URL, {
                method: 'POST',
                mode: 'no-cors',
                body: JSON.stringify(payload)
            });
            alert(`Account Created & Synced!\nUser ID: ${payload.uid}\nPassword: ${payload.pass}`);
            location.reload();
        } catch (e) {
            alert("Sync Failed!");
            btn.disabled = false;
            btn.innerText = "Create Account & Sync Phase III";
        }
    }

    // UPDATED FETCH FROM GOOGLE SHEETS
    async function loginHolder() {
        const id = document.getElementById('hId').value;
        const pass = document.getElementById('hPass').value;
        const btn = document.getElementById('loginBtn');

        btn.innerText = "Accessing Secure Vault...";
        btn.disabled = true;

        try {
            const response = await fetch(SCRIPT_URL);
            const users = await response.json();
            const user = users.find(u => u.uid == id && u.pass == pass);

            if (user) {
                document.getElementById('holderMenu').style.display = "block";
                document.getElementById('pbName').innerText = user.name;
                document.getElementById('pbMob').innerText = user.mobile;
                document.getElementById('pbAc').innerText = user.ac;
                document.getElementById('pbUid').innerText = user.uid;
                document.getElementById('pbBranch').innerText = user.dist + " / " + user.tal;
                document.getElementById('pbImg').src = user.pData;
                document.getElementById('pbSig').src = user.sData;
                document.getElementById('cardName').innerText = user.name;
                document.getElementById('cardNum').innerText = "5081 9901 4402 " + user.uid;
                showView('viewPassbook');
            } else { alert("Invalid Credentials!"); }
        } catch (e) {
            alert("Database Connection Error!");
        } finally {
            btn.disabled = false;
            btn.innerText = "Open Vault";
        }
    }
</script>
</body>
</html>
