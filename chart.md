##### *hours of 7 days*

```dataviewjs
const chartData = {
    type: 'bar',
    data: {
        labels: ["Sat", "Sun", "Mon", "Tue", "Wed", "Thu", "Fri"],
        datasets: [{
            label: 'Study Hours',
            data: [3, 4.5, 2, 3],
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
###### *4 weeks timeshit*
Week1===>
Week2 ===>
Week3 ===>
Week4 ===>
#### *hours of months*
```dataviewjs
const chartData = {
    type: 'bar',
    data: {
        labels: ["January","February","March","April","May","June","July","August","September","October","November","December"],
        datasets: [{
            label: 'Study Hours',
            data: [],
            backgroundColor: '#4678a8'
        }]
    },
    options: {
        responsive: true,
        plugins: {
            title: {
                display: true,
                text: 'Monthly Study Progress'
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

