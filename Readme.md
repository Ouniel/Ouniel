<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>欢迎来到我的GitHub</title>
    <style>
        .container { max-width: 960px; margin: 0 auto; padding: 2rem; }
        .header { display: flex; align-items: center; gap: 1rem; margin-bottom: 2rem; }
        .stats-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; }
        .tech-stack { display: flex; flex-wrap: wrap; gap: 0.5rem; margin: 1.5rem 0; }
        .tech-stack img { height: 24px; }
        .skill-icons { display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin: 1.5rem 0; }
        .activity-graph { margin-top: 2rem; }
    </style>
</head>
<body>
    <div class="container">
        <!-- 主标题 -->
        <div class="header">
            <img src="https://github.com/Ouniel.png?size=120" alt="头像" width="60">
            <h1>欢迎来到我的GitHub</h1>
        </div>

        <!-- 访问统计 -->
        <div class="stats">
            <a href="https://github.com/jxxxxxgl">
                <img src="https://komarev.com/ghpvc/?username=Ouniel&label=访客统计&color=red&style=flat&logo=github"
                     alt="GitHub访问量统计" style="float:right">
            </a>
        </div>

        <!-- 技术栈徽章 -->
        <div class="tech-stack">
            <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white">
            <img src="https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white">
            <img src="https://img.shields.io/badge/-Rust-DEA584?style=flat-square&logo=rust&logoColor=white">
            <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
        </div>

        <!-- 统计图表 -->
        <div class="stats-grid">
            <img src="https://github-readme-stats.vercel.app/api?username=Ouniel&show_icons=true&theme=radical">
            <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Ouniel&layout=compact&langs_count=8">
        </div>

        <!-- 技能展示 -->
        <h2>技能</h2>
        <div class="skill-icons">
            <div><img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"> Python</div>
            <div><img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png"> Docker</div>
            <div><img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/tensorflow/tensorflow.png"> TensorFlow</div>
        </div>

        <!-- 语言统计 -->
        <h2>语言分布</h2>
        <div class="tech-stack">
            <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/cpp/cpp.png" alt="C++">
            <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/json/json.png" alt="JSON">
            <img src="https://user-images.githubusercontent.com/29084184/218291286-3d84ebcb-c266-454b-bce2-b2f4ac01886f.png" alt="Djongo">
        </div>

        <!-- 活动图谱 -->
        <div class="activity-graph">
            <h2>活动记录</h2>
            <img src="https://github-readme-activity-graph.vercel.app/graph?username=Ouniel&theme=dracula" alt="贡献图谱">
        </div>
    </div>
</body>
</html>
