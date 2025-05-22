<!-- 美化版 GitHub 统计卡片集合 -->
<div class="github-stats-container" style="max-width: 1000px; margin: 0 auto; padding: 20px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;">
  <!-- 标题区域 -->
  <div class="header" style="text-align: center; margin-bottom: 30px;">
    <h2 style="font-size: 28px; color: #333; margin-bottom: 10px;">GitHub 数据统计</h2>
    <p style="color: #666; font-size: 16px;">展示代码活跃度、技术栈和项目数据</p>
  </div>

  <!-- 主要统计卡片 -->
  <div class="card-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-bottom: 30px;">
    <!-- 总览卡片 -->
    <div class="stat-card" style="background: #fff; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); overflow: hidden; transition: transform 0.3s ease, box-shadow 0.3s ease;">
      <div class="card-header" style="background: #f8f9fa; padding: 15px; text-align: center;">
        <h3 style="margin: 0; color: #333; font-size: 18px;">活跃度概览</h3>
      </div>
      <div class="card-body" style="padding: 20px; text-align: center;">
        <img src="https://github-readme-stats.vercel.app/api?username=longlonglink&show_icons=true&theme=tokyonight" 
             alt="GitHub Stats" 
             style="width: 100%; max-width: 400px; border-radius: 8px;">
      </div>
    </div>

    <!-- 语言分布卡片 -->
    <div class="stat-card" style="background: #fff; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); overflow: hidden; transition: transform 0.3s ease, box-shadow 0.3s ease;">
      <div class="card-header" style="background: #f8f9fa; padding: 15px; text-align: center;">
        <h3 style="margin: 0; color: #333; font-size: 18px;">编程语言分布</h3>
      </div>
      <div class="card-body" style="padding: 20px; text-align: center;">
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=longlonglink&theme=tokyonight&layout=compact&langs_count=8" 
             alt="Top Languages" 
             style="width: 100%; max-width: 400px; border-radius: 8px;">
      </div>
    </div>
  </div>

  <!-- 访客与技术栈区域 -->
  <div class="secondary-stats" style="background: #fff; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); padding: 25px; margin-bottom: 30px;">
    <div class="section-header" style="margin-bottom: 20px; border-bottom: 1px solid #eee; padding-bottom: 15px;">
      <h3 style="margin: 0; color: #333; font-size: 20px;">项目数据</h3>
    </div>
    
    <!-- 访客计数 -->
    <div class="visitor-count" style="text-align: center; margin-bottom: 25px;">
      <img src="https://img.shields.io/badge/访客计数-1000+-blue.svg" 
           alt="Visitor Count" 
           style="height: 30px; margin: 0 auto; display: block;">
    </div>
    
    <!-- 技术栈徽章 -->
    <div class="tech-stack" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 15px;">
      <div class="badge" style="background: #E34F26; color: white; border-radius: 4px; padding: 8px 15px; display: flex; align-items: center; transition: transform 0.2s ease;">
        <i class="fa-brands fa-html5" style="margin-right: 8px; font-size: 18px;"></i>
        <span>HTML5</span>
      </div>
      <div class="badge" style="background: #1572B6; color: white; border-radius: 4px; padding: 8px 15px; display: flex; align-items: center; transition: transform 0.2s ease;">
        <i class="fa-brands fa-css3-alt" style="margin-right: 8px; font-size: 18px;"></i>
        <span>CSS3</span>
      </div>
      <div class="badge" style="background: #F7DF1E; color: black; border-radius: 4px; padding: 8px 15px; display: flex; align-items: center; transition: transform 0.2s ease;">
        <i class="fa-brands fa-javascript" style="margin-right: 8px; font-size: 18px;"></i>
        <span>JavaScript</span>
      </div>
      <div class="badge" style="background: #20232A; color: #61DAFB; border-radius: 4px; padding: 8px 15px; display: flex; align-items: center; transition: transform 0.2s ease;">
        <i class="fa-brands fa-react" style="margin-right: 8px; font-size: 18px;"></i>
        <span>React</span>
      </div>
      <div class="badge" style="background: #3178C6; color: white; border-radius: 4px; padding: 8px 15px; display: flex; align-items: center; transition: transform 0.2s ease;">
        <i class="fa-brands fa-typescript" style="margin-right: 8px; font-size: 18px;"></i>
        <span>TypeScript</span>
      </div>
    </div>
  </div>

  <!-- 额外统计卡片 -->
  <div class="extra-stats" style="background: #fff; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); padding: 25px;">
    <div class="section-header" style="margin-bottom: 20px; border-bottom: 1px solid #eee; padding-bottom: 15px;">
      <h3 style="margin: 0; color: #333; font-size: 20px;">项目活跃度</h3>
    </div>
    <div class="activity-graph" style="text-align: center;">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=longlonglink&theme=github_dark" 
           alt="Repos Per Language" 
           style="width: 100%; max-width: 800px; border-radius: 8px; margin-bottom: 20px;">
    </div>
  </div>
</div>

<!-- 添加悬停动画效果 -->
<script>
  document.querySelectorAll('.stat-card, .badge').forEach(element => {
    element.addEventListener('mouseenter', () => {
      element.style.transform = 'translateY(-5px)';
      element.style.boxShadow = '0 10px 25px rgba(0,0,0,0.12)';
    });
    element.addEventListener('mouseleave', () => {
      element.style.transform = 'translateY(0)';
      element.style.boxShadow = '0 4px 20px rgba(0,0,0,0.08)';
    });
  });
</script>
