<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Amazon Employee Profile</title>

<style>
/* ===== GLOBAL ===== */
body{
  margin:0;
  font-family: Arial, Helvetica, sans-serif;
  background:#0f1111;
  color:#ffffff;
}
.container{
  max-width:1200px;
  margin:auto;
  padding:20px;
}
h2,h3,h4{margin:6px 0}
p{line-height:1.6}

/* ===== HEADER ===== */
.header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  background:#131921;
  padding:18px 25px;
  border-radius:12px;
}
.header-left{
  display:flex;
  align-items:center;
  gap:15px;
}
.header img{height:32px}
.header-title{
  font-size:14px;
  color:#ddd;
}
.header-title b{color:#fff}
.status{
  background:#232f3e;
  padding:8px 16px;
  border-radius:20px;
  font-size:13px;
  color:#00ff99;
}

/* ===== CARDS ===== */
.card{
  background:#1a1f2b;
  border-radius:14px;
  padding:22px;
  margin-top:22px;
}

/* ===== PROFILE ===== */
.profile{
  display:flex;
  gap:25px;
  align-items:center;
}
.avatar{
  width:130px;
  height:130px;
  background:#232f3e;
  border-radius:24px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:38px;
  font-weight:bold;
  color:#ff9900;
}
.tag{
  display:inline-block;
  background:#232f3e;
  padding:7px 16px;
  border-radius:20px;
  font-size:13px;
  margin-top:6px;
}

/* ===== GRID ===== */
.grid{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:15px;
  margin-top:18px;
}
.box{
  background:#232f3e;
  padding:16px;
  border-radius:12px;
  font-size:14px;
}

/* ===== TABLE ===== */
.table{
  width:100%;
  border-collapse:collapse;
  margin-top:10px;
}
.table th,.table td{
  padding:12px;
  border-bottom:1px solid #2f3b4f;
  text-align:left;
  font-size:14px;
}
.table th{
  color:#ff9900;
  font-weight:bold;
}

/* ===== SKILLS ===== */
.skills{
  display:flex;
  flex-wrap:wrap;
  gap:10px;
}
.skill{
  background:#232f3e;
  padding:8px 16px;
  border-radius:20px;
  font-size:13px;
}

/* ===== KPI ===== */
.kpi-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:15px;
}
.kpi{
  background:#232f3e;
  padding:16px;
  border-radius:12px;
}
.progress{
  height:8px;
  background:#444;
  border-radius:10px;
  overflow:hidden;
  margin-top:8px;
}
.progress span{
  display:block;
  height:100%;
  background:#ff9900;
}

/* ===== FOOTER ===== */
.footer{
  text-align:center;
  margin-top:30px;
  font-size:13px;
  color:#aaa;
}
</style>
</head>

<body>
<div class="container">

<!-- ================= HEADER ================= -->
<div class="header">
  <div class="header-left">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Amazon Logo">
    <div class="header-title">
      <b>Amazon</b> Employee Portal<br>
      Internal Profile & Performance System
    </div>
  </div>
  <div class="status">Active Employee</div>
</div>

<!-- ================= PROFILE ================= -->
<div class="card">
  <div class="profile">
    <div class="avatar">MK</div>
    <div>
      <h2>FNU Maliha Khanam</h2>
      <div class="tag">Data Engineer</div>
      <p><b>Working Since:</b> February 2025</p>
      <p><b>Employee Status:</b> Full-Time | Good Standing</p>
    </div>
  </div>

  <div class="grid">
    <div class="box"><b>Employee ID</b><br>AMZ-DE-2025-017</div>
    <div class="box"><b>Department</b><br>Data & Analytics</div>
    <div class="box"><b>Team</b><br>Data Platform Engineering</div>
    <div class="box"><b>Location</b><br>Illinois, USA</div>
  </div>
</div>

<!-- ================= CONTACT ================= -->
<div class="card">
  <h3>Contact Information</h3>
  <table class="table">
    <tr><th>Email</th><td>malikhanam1713@gmail.com</td></tr>
    <tr><th>Phone</th><td>618-217-8807</td></tr>
    <tr><th>Work Mode</th><td>Hybrid (Office & Remote)</td></tr>
    <tr><th>Shift</th><td>Monday – Friday (9:00 AM – 5:00 PM)</td></tr>
  </table>
</div>

<!-- ================= PROFESSIONAL SUMMARY ================= -->
<div class="card">
  <h3>Professional Summary</h3>
  <p>
    Data Engineer at Amazon with experience in designing, developing, and maintaining scalable
    data pipelines and enterprise data platforms. Strong expertise in ETL/ELT workflows, data
    warehousing, and quality assurance. Actively collaborates with analytics, product, and
    business teams to deliver reliable and actionable data solutions.
  </p>
</div>

<!-- ================= PERFORMANCE ================= -->
<div class="card">
  <h3>Performance Overview</h3>
  <div class="kpi-grid">
    <div class="kpi">
      <b>Attendance</b>
      <p>98%</p>
      <div class="progress"><span style="width:98%"></span></div>
    </div>
    <div class="kpi">
      <b>Data Quality Score</b>
      <p>95%</p>
      <div class="progress"><span style="width:95%"></span></div>
    </div>
    <div class="kpi">
      <b>On-Time Delivery</b>
      <p>92%</p>
      <div class="progress"><span style="width:92%"></span></div>
    </div>
  </div>
</div>

<!-- ================= RESPONSIBILITIES ================= -->
<div class="card">
  <h3>Key Responsibilities</h3>
  <ul>
    <li>Design and maintain batch and streaming data pipelines.</li>
    <li>Ensure data quality, integrity, and governance standards.</li>
    <li>Develop optimized data models for analytics and reporting.</li>
    <li>Collaborate with data scientists and analysts.</li>
    <li>Monitor pipeline performance and resolve incidents.</li>
  </ul>
</div>

<!-- ================= SKILLS ================= -->
<div class="card">
  <h3>Technical Skills</h3>
  <div class="skills">
    <div class="skill">Python</div>
    <div class="skill">SQL</div>
    <div class="skill">ETL / ELT Pipelines</div>
    <div class="skill">Data Warehousing</div>
    <div class="skill">Data Modeling</div>
    <div class="skill">AWS Cloud Services</div>
    <div class="skill">Big Data Processing</div>
    <div class="skill">Data Quality & Monitoring</div>
  </div>
</div>

<!-- ================= PROJECTS ================= -->
<div class="card">
  <h3>Major Projects</h3>
  <table class="table">
    <tr>
      <th>Project</th>
      <th>Description</th>
      <th>Status</th>
    </tr>
    <tr>
      <td>Sales Analytics Pipeline</td>
      <td>Built automated pipelines to support enterprise sales reporting.</td>
      <td>Completed</td>
    </tr>
    <tr>
      <td>Data Quality Framework</td>
      <td>Implemented validation checks and alerting systems.</td>
      <td>Live</td>
    </tr>
    <tr>
      <td>Warehouse Optimization</td>
      <td>Improved query performance and reduced data latency.</td>
      <td>In Progress</td>
    </tr>
  </table>
</div>

<!-- ================= FOOTER ================= -->
<div class="footer">
  © 2026 Amazon Employee Portal — Student Assignment (Demo Only)<br>
  This website is created strictly for educational purposes and is not an official Amazon system.
</div>

</div>
</body>
</html>