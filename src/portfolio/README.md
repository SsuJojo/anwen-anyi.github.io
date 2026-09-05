---
title: 作品集
containerClass: portfolio-page
sidebar: false
editLink: false
lastUpdated: false
contributors: false
---

<div class="portfolio-shell">
  <section class="portfolio-hero">
    <p class="portfolio-kicker">SSUJO_ / SELECTED WORK</p>
    <h1>把想法推进到<br>能跑、能演示、能解决问题。</h1>
    <p class="portfolio-lede">我做 AI 应用、自动化和全栈原型。每个项目先把核心链路跑通，再持续打磨成可靠的产品。</p>
    <div class="portfolio-actions">
      <a class="portfolio-button portfolio-button--primary" href="https://github.com/SsuJojo">查看 GitHub</a>
      <a class="portfolio-button" href="#ai-interview">从作品开始</a>
    </div>
    <p class="portfolio-scroll">向下浏览 6 个代表项目</p>
  </section>

  <section id="ai-interview" class="portfolio-case portfolio-case--featured">
    <div class="portfolio-copy">
      <p class="portfolio-index">01 / AI PRODUCT</p>
      <h2>AI Interview</h2>
      <p class="portfolio-summary">从简历分析、岗位匹配到模拟问答和复盘报告的一体化 AI 面试平台；同时提供在线 Demo 与桌面端发布包。</p>
      <ul class="portfolio-points">
        <li>完整覆盖“上传简历 → 选岗 → 面试 → 复盘”核心路径</li>
        <li>Vue + FastAPI + SQLite，兼容桌面端与容器化部署</li>
        <li>正在推进中英双语体验与更稳定的会话能力</li>
      </ul>
      <div class="portfolio-links">
        <a href="https://aiiv.zszs.uno">在线体验</a>
        <a href="https://github.com/SsuJojo/AI-Interview-Release">项目仓库</a>
      </div>
    </div>
    <figure class="portfolio-shot">
      <img src="https://raw.githubusercontent.com/SsuJojo/AI-Interview-Release/main/assets/screenshots/interview.png" alt="AI Interview 的面试界面截图">
      <figcaption>AI Interview · 实际产品界面</figcaption>
    </figure>
  </section>

  <section class="portfolio-case portfolio-case--blue">
    <div class="portfolio-copy">
      <p class="portfolio-index">02 / FULL-STACK WEB</p>
      <h2>JZHW Canteen</h2>
      <p class="portfolio-summary">校园食堂 Web 产品。把菜单、点赞排行、预约、推荐、后台管理和内容审核串成一条完整业务链路。</p>
      <ul class="portfolio-points">
        <li>面向真实场景，而不是只做静态页面</li>
        <li>覆盖用户端、管理端与内容治理</li>
        <li>Next.js · React · PostgreSQL</li>
      </ul>
      <div class="portfolio-links">
        <a href="https://ct.jzhw.zszs.uno">访问产品</a>
        <a href="https://github.com/SsuJojo/JZHW_Canteen">项目仓库</a>
      </div>
    </div>
    <div class="portfolio-art portfolio-art--canteen" aria-hidden="true"><span>MENU</span><span>RANKING</span><span>RESERVE</span></div>
  </section>

  <section class="portfolio-case portfolio-case--dark">
    <div class="portfolio-copy">
      <p class="portfolio-index">03 / REMOTE INPUT</p>
      <h2>web-inputer</h2>
      <p class="portfolio-summary">把手机浏览器变成 Windows 电脑的远程键盘、文本、剪贴板和鼠标输入面板。</p>
      <ul class="portfolio-points">
        <li>带鉴权的 WebSocket 通信、重连与控制锁</li>
        <li>针对跨设备输入这个小摩擦，做成可直接用的工具</li>
        <li>Python · FastAPI · Vue · Windows</li>
      </ul>
      <div class="portfolio-links">
        <a href="https://github.com/SsuJojo/web-inputer">项目仓库</a>
      </div>
    </div>
    <div class="portfolio-art portfolio-art--input" aria-hidden="true"><span>PHONE</span><i>→</i><span>PC</span></div>
  </section>

  <section class="portfolio-case portfolio-case--violet">
    <div class="portfolio-copy">
      <p class="portfolio-index">04 / AI AUTOMATION</p>
      <h2>Roco Market Watcher</h2>
      <p class="portfolio-summary">一条从网页内容抓取、LLM 结构化理解，到规则匹配并触发通知的自动化监控管线。</p>
      <ul class="portfolio-points">
        <li>将“网页有变化时我想知道”变成可配置的自动任务</li>
        <li>内容获取、LLM 解析和决策通知分层处理</li>
        <li>Python · FastAPI · LLM · Automation</li>
      </ul>
      <div class="portfolio-links">
        <a href="https://github.com/SsuJojo/Roco-Market-Watcher">项目仓库</a>
      </div>
    </div>
    <div class="portfolio-art portfolio-art--watch" aria-hidden="true"><span>FETCH</span><i>→</i><span>STRUCTURE</span><i>→</i><span>NOTIFY</span></div>
  </section>

  <section class="portfolio-case portfolio-case--warm">
    <div class="portfolio-copy">
      <p class="portfolio-index">05 / PRODUCT PROTOTYPE</p>
      <h2>MirrorSelf</h2>
      <p class="portfolio-summary">围绕餐食与外卖分享场景的轻量全栈产品原型，包含前端体验、API、持久化与 Docker 部署。</p>
      <ul class="portfolio-points">
        <li>从真实生活场景出发验证产品想法</li>
        <li>Vue · Go · Fiber · PocketBase · Docker</li>
      </ul>
      <div class="portfolio-links">
        <a href="https://github.com/SsuJojo/MirrorSelf">项目仓库</a>
      </div>
    </div>
    <div class="portfolio-art portfolio-art--mirror" aria-hidden="true"><span>SHARE</span><span>MEALS</span><span>IDEAS</span></div>
  </section>

  <section class="portfolio-case portfolio-case--green">
    <div class="portfolio-copy">
      <p class="portfolio-index">06 / AGENT TOOLING</p>
      <h2>everything-skill</h2>
      <p class="portfolio-summary">把 Voidtools Everything 的全盘文件检索能力封装成 Agent Skill，让 AI 可以调用真实的 Windows 本机搜索。</p>
      <ul class="portfolio-points">
        <li>不是模拟工具调用，而是让 Agent 接入真实能力</li>
        <li>清晰描述能力边界与使用方式，方便复用</li>
        <li>Agent Skill · Windows · Automation</li>
      </ul>
      <div class="portfolio-links">
        <a href="https://github.com/SsuJojo/everything-skill">项目仓库</a>
      </div>
    </div>
    <div class="portfolio-art portfolio-art--search" aria-hidden="true"><span>C:\</span><span>everything</span><span>result found</span></div>
  </section>

  <section class="portfolio-end">
    <p class="portfolio-kicker">MORE WORK IN PROGRESS</p>
    <h2>先把核心链路做出来，<br>再把它做得更好。</h2>
    <a class="portfolio-button portfolio-button--primary" href="https://github.com/SsuJojo?tab=repositories">浏览全部项目</a>
  </section>
</div>
