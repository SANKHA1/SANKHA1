👋 Hi, I’m Sankha

👀 I’m interested in Deep Learning and Data engineering

🌱 I’m working in the field of Generative AI

💞️ I’m looking to collaborate with talented developers on Machine Learning Tech Stack, API development or anything that involves new things to learn.

📫 Reach me out sankhasubhramukherjee@gmail.com





<a href="https://github.com/SANKHA1">
   <img src="https://github-readme-stats.vercel.app/api?username=SANKHA1&show_icons=true&count_private=true&theme=dracula" />

</a>


<a href="https://github.com/SANKHA1">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SANKHA1&layout=compact&theme=dracula" />
</a>




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.jsdelivr.net/npm/echarts@5.3.2/dist/echarts.min.js"></script>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #272727;
      color: #fff;
      font-family: 'Fira Code', monospace;
    }
    .chart-container, .stats-container {
      width: 45%;
      height: 45%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .chart-container {
      margin-right: 5%;
    }
  </style>
</head>
<body>
  <div class="chart-container">
    <div id="main" style="width: 100%; height: 100%;"></div>
  </div>
  <div class="stats-container">
    <a href="https://github.com/BidishaDas">
      <img src="https://github-readme-stats.vercel.app/api?username=BidishaDas&show_icons=true&count_private=true&theme=dracula" />
    </a>
  </div>
  <script>
  const chartDom = document.getElementById('main');
const myChart = echarts.init(chartDom);
const option = {
  title: {
    text: 'Bidisha Das\' Most Used Languages',
    left: 'center',
    top: 20,
    textStyle: {
      color: '#fff',
      fontSize: 24,
      fontWeight: 'bold'
    }
  },
  tooltip: {
    trigger: 'item'
  },
  legend: {
    orient: 'vertical',
    left: 'left',
    top: 'bottom',
    textStyle: {
      color: '#fff'
    }
  },
  series: [
    {
      name: 'Languages',
      type: 'pie',
      radius: ['40%', '70%'],
      avoidLabelOverlap: false,
      itemStyle: {
        borderRadius: 10,
        borderColor: '#fff',
        borderWidth: 2
      },
      label: {
        show: false,
        position: 'center'
      },
      emphasis: {
        label: {
          show: true,
          fontSize: '20',
          fontWeight: 'bold'
        }
      },
      labelLine: {
        show: false
      },
      data: [
        { value: 1048, name: 'JavaScript' },
        { value: 735, name: 'CSS' },
        { value: 580, name: 'HTML' },
        { value: 484, name: 'Python' },
        { value: 300, name: 'Java' },
        { value: 220, name: 'C++' },
        { value: 150, name: 'Other' }
      ]
    }
  ]
};

myChart.setOption(option);
</script>
