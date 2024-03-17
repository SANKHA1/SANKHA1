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
    .chart-container {
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
  </style>
</head>
<body>
  <div class="chart-container">
    <div id="main" style="width: 100%; height: 100%;"></div>
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
      series: [
        {
          name: 'Languages',
          type: 'pie',
          radius: ['40%', '70%'],
          avoidLabelOverlap: false,
          itemStyle: {
            borderRadius: 10,
            borderColor: '#fff',
