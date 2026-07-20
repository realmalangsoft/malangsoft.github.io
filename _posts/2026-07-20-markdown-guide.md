---
layout: default
title: 정적 웹사이트와 마크다운의 장점
date: 2026-07-20
description: 복잡한 DB 없이 빠른 로딩과 마크다운의 편안함에 대해 이야기합니다.
---

<article class="post-container">
  <header class="post-header">
    <h1 class="post-title">{{ page.title }}</h1>
    <div class="post-meta">{{ page.date | date: "%Y년 %m월 %d일" }}</div>
  </header>

  <div class="post-content">
    <p>정적 웹사이트(Static Site)는 서버나 데이터베이스 없이 HTML, CSS 파일만으로 전 세계 어디서나 빠른 속도로 웹사이트를 제공합니다.</p>

    <h3>왜 마크다운인가요?</h3>
    <ul>
      <li><strong>간결한 문법</strong>: HTML 태그를 일일이 열고 닫을 필요 없이 <code>#</code>, <code>-</code>, <code>**</code> 만으로 글 작성 가능</li>
      <li><strong>이동성</strong>: 어떤 에디터나 블로그 플랫폼에서도 그대로 활용 가능</li>
      <li><strong>GitHub 통합</strong>: 코드를 다루듯 <code>git push</code> 만으로 즉시 배포 가능</li>
    </ul>

    <div style="margin-top: 3rem;">
      <a href="{{ '/' | relative_url }}" class="project-link">← 메인 페이지로 돌아가기</a>
    </div>
  </div>
</article>
