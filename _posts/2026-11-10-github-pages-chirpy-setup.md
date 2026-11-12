---
title: "[오픈소스소프트웨어] GitHub Pages와 Jekyll Chirpy 테마를 활용한 기술 블로그 구축"
date: 2026-11-10 11:55:00 +0900
categories: [과제, 오픈소스소프트웨어]
tags: [opensource, github-pages, jekyll, chirpy]
---

## 개요

**오픈소스소프트웨어** 강의 과제의 일환으로 개인 기술 블로그(`https://hanwoo0209.github.io`)를 구축

---

## 사용한 오픈소스 테마 정보

* **테마 이름:** Jekyll Theme Chirpy (MIT License)
* **테마 원본 GitHub 저장소:** [cotes2020/jekyll-theme-chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)
* **블로그 구축용 스타터 저장소:** [cotes2020/chirpy-starter](https://github.com/cotes2020/chirpy-starter)
* **공식 설치 및 적용 가이드:** [Chirpy Getting Started 공식 문서](https://chirpy.cotes.page/posts/getting-started/)

---

## 블로그 구축 및 배포 과정

1. **저장소 생성 (`Use this template`)**
   * `chirpy-starter` 템플릿 저장소를 기반으로 `hanwoo0209.github.io` 리포지토리 생성
2. **GitHub Actions 기반 배포 설정**
   * 저장소의 **Settings > Pages** 메뉴에서 빌드 소스를 `GitHub Actions`로 지정하여, 코드 푸시 시 자동으로 사이트가 빌드되고 배포되도록 구성
3. **환경 설정 파일(`_config.yml`) 커스터마이징**
   * `lang: ko-KR`, `timezone: Asia/Seoul` 설정으로 테마 UI에 한국어 환경 적용.
   * 블로그 제목(`title`), 한 줄 소개(`tagline`), 도메인(`url`), GitHub 계정 정보 및 프로필 이미지(`avatar`) 경로 등을 개인 환경에 맞게 수정
4. **페이지 및 프로필 구성**
   * `_data/contact.yml`에서 사용할 소셜 연락처 아이콘 정리, `_tabs/about.md`에 자기소개 페이지를 작성

---

## 참고 링크

* **Jekyll 공식 홈페이지:** [https://jekyllrb.com/](https://jekyllrb.com/)
* **Chirpy 테마 GitHub:** [https://github.com/cotes2020/jekyll-theme-chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)
* **Chirpy 테마 데모 사이트:** [https://chirpy.cotes.page/](https://chirpy.cotes.page/)
* **Chirpy 테마 적용 가이드:** [https://chirpy.cotes.page/posts/getting-started/](https://chirpy.cotes.page/posts/getting-started/)
