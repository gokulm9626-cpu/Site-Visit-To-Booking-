
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Overall 2025 – Site Visit Month Wise Report</title>

<style>
body{
  font-family:Arial,Helvetica,sans-serif;
  background:linear-gradient(180deg,#eef2ff,#f8fafc);
  margin:20px;
}

/* HEADER */
.header{
  background:linear-gradient(135deg,#1e3c72,#2a6fd6);
  text-align:center;
  padding:35px 15px 40px;
  border-radius:12px;
  margin-bottom:25px;
  box-shadow:0 10px 25px rgba(0,0,0,.18);
}
.logo-circle{
  width:140px;height:140px;
  margin:0 auto 14px;
  border-radius:50%;
  background:#fff;
  display:flex;align-items:center;justify-content:center;
}
.logo-circle img{width:88%;border-radius:50%}
.office-name{font-size:26px;font-weight:700;color:#fff}
.tagline{font-size:14px;color:#dbe7ff;letter-spacing:3px}

/* KPI */
.kpi-container{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:18px;margin-bottom:25px;
}
.kpi-card{
  background:#f9fafb;
  border-radius:12px;
  padding:18px;text-align:center;
  box-shadow:0 6px 18px rgba(0,0,0,.12);
}
.kpi-title{font-size:13px;color:#6b7280}
.kpi-value{font-size:26px;font-weight:bold;color:#1e3c72}

/* FILTERS */
.filters{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:15px;margin-bottom:20px;
  background:#f9fafb;
  padding:15px;border-radius:8px;
}
.filters label{font-size:13px;font-weight:bold}
.filters select,.filters input{
  width:100%;padding:8px;border:1px solid #ccc;border-radius:4px;
}

/* TABLE */
table{width:100%;border-collapse:collapse;background:#fff}
th,td{
  border:1px solid #ddd;
  padding:8px;
  text-align:center;
  font-size:13px;
  color:#000;
}
th{font-weight:700;position:sticky;top:0}
tr:nth-child(even){background:#f8fafc}

th.sno,th.month{background:#3b82f6}
th.sitevisit{background:#f9b4ff}
th.booking,th.sqft{background:#dbeafe}
th.conv{background:#fff1c1}
th.live,th.livesqft{background:#d9f0c9}
th.cancel,th.cancelsqft{background:#ffd9b3}

.bar{height:8px;background:#e5e7eb;border-radius:6px;margin-top:4px}
.bar-fill{height:100%;background:linear-gradient(90deg,#2a6fd6,#1e3c72);border-radius:6px}

.total-row td{font-weight:700;background:#f1f5f9}

/* CHARTS */
.chart-section{
  margin-top:30px;
  background:#f9fafb;
  padding:20px;
  border-radius:12px;
}
.chart-title{
  font-size:16px;
  font-weight:bold;
  margin-bottom:15px;
  color:#1e3c72;
}
.chart-row{margin-bottom:14px}
.chart-label{font-size:13px;margin-bottom:4px}
.chart-bar{
  height:14px;
  background:#e5e7eb;
  border-radius:8px;
  overflow:hidden;
}
.chart-fill{height:100%}

.chart-visit{background:#2563eb}
.chart-booking{background:#16a34a}
.chart-conv{background:#f59e0b}
.chart-live{background:#22c55e}
.chart-cancel{background:#ef4444}
</style>
</head>

<body>

<div class="header">
  <div class="logo-circle"><img src="logo.png"></div>
  <div class="office-name">NAMMA FAMILY BUILDERS & DEVELOPERS PVT LTD</div>
  <div class="tagline">NFBD</div>
</div>

<h1 style="text-align:center">OVERALL 2025 – SITE VISIT MONTH WISE REPORT</h1>

<div class="kpi-container">
  <div class="kpi-card"><div class="kpi-title">TOTAL SITE VISITS</div><div id="kpiVisits" class="kpi-value">0</div></div>
  <div class="kpi-card"><div class="kpi-title">TOTAL BOOKINGS</div><div id="kpiBookings" class="kpi-value">0</div></div>
  <div class="kpi-card"><div class="kpi-title">TOTAL LIVE</div><div id="kpiLive" class="kpi-value">0</div></div>
  <div class="kpi-card"><div class="kpi-title">AVG CONVERSION %</div><div id="kpiConv" class="kpi-value">0%</div></div>
</div>

<div class="filters">
  <div><label>Month</label><select id="monthFilter" onchange="applyFilters()"><option value="">All</option></select></div>
  <div><label>Min Visit</label><input type="number" id="minVisit" onkeyup="applyFilters()"></div>
  <div><label>Min Conversion %</label><input type="number" id="minConversion" onkeyup="applyFilters()"></div>
</div>

<table>
<thead>
<tr>
  <th class="sno">S.No</th>
  <th class="month">Month</th>
  <th class="sitevisit">Site Visit</th>
  <th class="booking">Booking</th>
  <th class="sqft">Sqft</th>
  <th class="conv">Conv %</th>
  <th class="live">Live</th>
  <th class="livesqft">Live Sqft</th>
  <th class="cancel">Cancel</th>
  <th class="cancelsqft">Cancel Sqft</th>
</tr>
</thead>
<tbody id="reportBody"></tbody>
</table>

<!-- CHARTS BELOW TABLE -->
<div class="chart-section">
  <div class="chart-title">📊 Site Visit vs Booking</div>
  <div id="visitBookingChart"></div>
</div>

<div class="chart-section">
  <div class="chart-title">📈 Conversion % Performance</div>
  <div id="conversionPerfChart"></div>
</div>

<div class="chart-section">
  <div class="chart-title">✅ Live vs ❌ Cancel</div>
  <div id="liveCancelPerfChart"></div>
</div>

<script>
const data=[ /* SAME DATA – unchanged */ 
{month:"January",visit:349,booking:79,sqft:131071,conv:23,live:26,livesqft:32725,cancel:53,cancelsqft:98346},
{month:"February",visit:465,booking:104,sqft:150121,conv:22,live:42,livesqft:54906,cancel:62,cancelsqft:95215},
{month:"March",visit:580,booking:140,sqft:193010,conv:24,live:62,livesqft:87454,cancel:78,cancelsqft:105556},
{month:"April",visit:446,booking:133,sqft:178889,conv:30,live:43,livesqft:57885,cancel:90,cancelsqft:121004},
{month:"May",visit:393,booking:74,sqft:120117,conv:19,live:31,livesqft:44669,cancel:43,cancelsqft:75448},
{month:"June",visit:444,booking:114,sqft:159066,conv:26,live:41,livesqft:57148,cancel:73,cancelsqft:101918},
{month:"July",visit:423,booking:83,sqft:137968,conv:20,live:37,livesqft:60876,cancel:46,cancelsqft:77092},
{month:"August",visit:336,booking:69,sqft:115349,conv:21,live:33,livesqft:51182,cancel:36,cancelsqft:64167},
{month:"September",visit:362,booking:55,sqft:84586,conv:15,live:21,livesqft:31583,cancel:34,cancelsqft:53003},
{month:"October",visit:383,booking:55,sqft:84857,conv:14,live:33,livesqft:51904,cancel:22,cancelsqft:32953},
{month:"November",visit:483,booking:52,sqft:78462,conv:11,live:36,livesqft:54748,cancel:16,cancelsqft:23714},
{month:"December",visit:140,booking:11,sqft:13448,conv:8,live:8,livesqft:9986,cancel:3,cancelsqft:3462}
];

const tbody=document.getElementById("reportBody");
data.forEach(d=>monthFilter.innerHTML+=`<option>${d.month}</option>`);

function renderTable(arr){
  tbody.innerHTML="";
  let v=0,b=0,l=0,c=0,sq=0,lsq=0,csq=0,can=0;

  arr.forEach((d,i)=>{
    v+=d.visit;b+=d.booking;l+=d.live;c+=d.conv;
    sq+=d.sqft;lsq+=d.livesqft;csq+=d.cancelsqft;can+=d.cancel;

    tbody.innerHTML+=`
    <tr>
      <td>${i+1}</td><td>${d.month}</td>
      <td>${d.visit}<div class="bar"><div class="bar-fill" style="width:${(d.visit/600)*100}%"></div></div></td>
      <td>${d.booking}</td><td>${d.sqft}</td><td>${d.conv}%</td>
      <td>${d.live}</td><td>${d.livesqft}</td>
      <td>${d.cancel}</td><td>${d.cancelsqft}</td>
    </tr>`;
  });

  tbody.innerHTML+=`
  <tr class="total-row">
    <td colspan="2">TOTAL</td>
    <td>${v}</td><td>${b}</td><td>${sq}</td>
    <td>${Math.round(c/arr.length)}%</td>
    <td>${l}</td><td>${lsq}</td>
    <td>${can}</td><td>${csq}</td>
  </tr>`;

  kpiVisits.textContent=v;
  kpiBookings.textContent=b;
  kpiLive.textContent=l;
  kpiConv.textContent=Math.round(c/arr.length)+"%";

  renderCharts(arr);
}

function renderCharts(arr){
  visitBookingChart.innerHTML="";
  conversionPerfChart.innerHTML="";
  liveCancelPerfChart.innerHTML="";

  arr.forEach(d=>{
    visitBookingChart.innerHTML+=`
      <div class="chart-row">
        <div class="chart-label">${d.month} – Visit ${d.visit}, Booking ${d.booking}</div>
        <div class="chart-bar"><div class="chart-fill chart-visit" style="width:${(d.visit/600)*100}%"></div></div>
        <div class="chart-bar" style="margin-top:4px"><div class="chart-fill chart-booking" style="width:${(d.booking/150)*100}%"></div></div>
      </div>`;

    conversionPerfChart.innerHTML+=`
      <div class="chart-row">
        <div class="chart-label">${d.month} – ${d.conv}%</div>
        <div class="chart-bar"><div class="chart-fill chart-conv" style="width:${d.conv*3}%"></div></div>
      </div>`;

    liveCancelPerfChart.innerHTML+=`
      <div class="chart-row">
        <div class="chart-label">${d.month} – Live ${d.live}, Cancel ${d.cancel}</div>
        <div class="chart-bar"><div class="chart-fill chart-live" style="width:${(d.live/100)*100}%"></div></div>
        <div class="chart-bar" style="margin-top:4px"><div class="chart-fill chart-cancel" style="width:${(d.cancel/100)*100}%"></div></div>
      </div>`;
  });
}

function applyFilters(){
  const m=monthFilter.value;
  renderTable(data.filter(d=>
    (m===""||d.month===m) &&
    d.visit>=(minVisit.value||0) &&
    d.conv>=(minConversion.value||0)
  ));
}

renderTable(data);
</script>

</body>
</html>
