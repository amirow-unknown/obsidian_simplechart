```dataviewjs
const chartData = {
    type: 'bar',
    data: {
        labels: ["Sat", "Sun", "Mon", "Tue", "Wed", "Thu", "Fri"],
        datasets: [{
            label: 'Study Hours',
            data: [3, 4.5, 2, 5, 10, 15, 11, ],
            backgroundColor: '#4678a8'
        }]
    },
    options: {
        responsive: true,
        plugins: {
            title: {
                display: true,
                text: 'Weekly Study Progress'
            }
        },
        scales: {
            y: {
                beginAtZero: true,
                title: {
                    display: true,
                    text: 'Hours'
                }
            }
        }
    }
}
window.renderChart(chartData, this.container)
```
