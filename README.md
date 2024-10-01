<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Analytics Dashboard</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>

    <header>
        <h1>Analytics Dashboard</h1>
        <div class="date-range">
            <label for="dateRange">Select Date Range:</label>
            <input type="date" id="startDate">
            <input type="date" id="endDate">
        </div>
    </header>

    <nav class="sidebar">
        <ul>
            <li><a href="#dashboard">Dashboard Overview</a></li>
            <li><a href="#dataSources">Data Sources</a></li>
            <li><a href="#reports">Reports</a></li>
            <li><a href="#settings">Settings</a></li>
        </ul>
    </nav>

    <main>
        <section class="kpi-summary">
            <div class="kpi-card">
                <h2>Total Revenue</h2>
                <p id="totalRevenue">$0</p>
            </div>
            <div class="kpi-card">
                <h2>Active
