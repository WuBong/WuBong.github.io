---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
---
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <title>이미지 슬라이더</title>
    <style>
        .carousel-item img {
            width: 100%; /* 이미지를 컨테이너에 맞게 조정 */
            height: 500px; /* 원하는 높이 설정 */
            object-fit: cover; /* 이미지 비율 유지하면서 크기 조정 */
        }
    </style>
</head>
<body>

<div id="imageCarousel" class="carousel slide" data-ride="carousel">
    <div class="carousel-inner">
        <div class="carousel-item active">
            <img src="/images/unity.jpg" class="d-block" alt="AI 이미지">
            <div class="carousel-caption d-none d-md-block">
                <h5>AI</h5>
                <p>의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발</p>
            </div>
        </div>
        <div class="carousel-item">
            <img src="/images/directx.jpg" class="d-block" alt="Medical AI 이미지">
            <div class="carousel-caption d-none d-md-block">
                <h5>Medical AI</h5>
                <p>의료AI를 통한 질병 진단 및 환경 개선</p>
            </div>
        </div>
        <div class="carousel-item">
            <img src="/images/healthcare.jpg" class="d-block" alt="Healthcare 이미지">
            <div class="carousel-caption d-none d-md-block">
                <h5>Healthcare</h5>
                <p>의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</p>
            </div>
        </div>
        <div class="carousel-item">
            <img src="/images/rock.jpg" class="d-block" alt="Aerospace 이미지">
            <div class="carousel-caption d-none d-md-block">
                <h5>Aerospace</h5>
                <p>항공우주에 적용 가능한 특성화 AI 기술 개발</p>
            </div>
        </div>
    </div>
    <a class="carousel-control-prev" href="#imageCarousel" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">이전</span>
    </a>
    <a class="carousel-control-next" href="#imageCarousel" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">다음</span>
    </a>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
