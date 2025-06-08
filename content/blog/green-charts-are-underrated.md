---
title: "Green Charts Are Underrated"
description: "Data visualisation in climate reporting"
date: 2025-06-08
tags: [visualisation, climate]
---

You can embed charts like this:

<iframe width="600" height="400" src="https://public.tableau.com/views/SampleDashboard/Sheet1" frameborder="0"></iframe>

Or use Chart.js:

```html
<canvas id="myChart" width="400" height="200"></canvas>
<script>
  new Chart(document.getElementById('myChart'), {
    type: 'bar',
    data: {
      labels: ['A', 'B', 'C'],
      datasets: [{ label: 'Demo', data: [12, 19, 3] }]
    }
  });
</script>
