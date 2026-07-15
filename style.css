/* 基础重置 */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f5f7fa;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* 顶部简介区 */
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 80px 0;
    text-align: center;
    margin-bottom: 50px;
}

.hero h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
    font-weight: 700;
}

.subtitle {
    font-size: 1.2em;
    opacity: 0.9;
    margin-bottom: 20px;
}

.contact a {
    color: white;
    text-decoration: none;
    border-bottom: 1px solid rgba(255,255,255,0.3);
    transition: border-color 0.3s;
}

.contact a:hover {
    border-color: white;
}

/* 项目网格 */
.section-title {
    font-size: 1.8em;
    margin-bottom: 30px;
    color: #2d3748;
    position: relative;
    padding-bottom: 10px;
}

.section-title::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 60px;
    height: 4px;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    border-radius: 2px;
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
    gap: 30px;
    margin-bottom: 80px;
}

/* 项目卡片 */
.project-card {
    background: white;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.07);
    transition: all 0.3s ease;
    cursor: pointer;
    border: 1px solid #e2e8f0;
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 24px rgba(0,0,0,0.15);
    border-color: #cbd5e0;
}

.card-image {
    width: 100%;
    height: 220px;
    overflow: hidden;
    background: #edf2f7;
}

.card-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s;
}

.project-card:hover .card-image img {
    transform: scale(1.05);
}

.card-content {
    padding: 25px;
}

.card-tags {
    margin-bottom: 12px;
}

.tag {
    display: inline-block;
    padding: 4px 12px;
    background: #edf2f7;
    color: #4a5568;
    border-radius: 20px;
    font-size: 0.85em;
    margin-right: 8px;
    margin-bottom: 5px;
}

.card-title {
    font-size: 1.3em;
    color: #2d3748;
    margin-bottom: 12px;
    line-height: 1.3;
}

.card-desc {
    color: #718096;
    font-size: 0.95em;
    line-height: 1.6;
    margin-bottom: 20px;
    display: -webkit-box;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
    overflow: hidden;
}

.card-meta {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 15px;
    border-top: 1px solid #e2e8f0;
}

.date {
    color: #a0aec0;
    font-size: 0.9em;
}

.arrow {
    color: #667eea;
    font-weight: 600;
    font-size: 0.9em;
    transition: transform 0.3s;
}

.project-card:hover .arrow {
    transform: translateX(5px);
}

/* 页脚 */
footer {
    text-align: center;
    padding: 40px 0;
    color: #718096;
    border-top: 1px solid #e2e8f0;
    background: white;
}

/* 响应式 */
@media (max-width: 768px) {
    .projects-grid {
        grid-template-columns: 1fr;
        gap: 20px;
    }
    
    .hero h1 {
        font-size: 2em;
    }
    
    .hero {
        padding: 50px 0;
    }
}
