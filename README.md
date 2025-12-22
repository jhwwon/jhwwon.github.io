<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>Listify 프로젝트 소개</title>
  <style>
    body { font-family: 'Segoe UI', Arial, sans-serif; background: #f7f7fa; margin: 0; }
    .container { display: flex; max-width: 1100px; margin: 40px auto; background: #fff; border-radius: 16px; box-shadow: 0 2px 8px #0001; }
    .left, .right { padding: 32px; }
    .left { flex: 1; border-right: 1px solid #eee; }
    .right { flex: 1; }
    h1 { font-size: 2.2em; margin-bottom: 0.2em; }
    ul { margin: 1em 0; }
    .video { margin-bottom: 24px; }
    .links a { display: inline-block; margin: 8px 0; padding: 10px 18px; background: #2d7cf7; color: #fff; border-radius: 8px; text-decoration: none; font-weight: 500; }
    .links a:hover { background: #1a5bb8; }
    @media (max-width: 900px) {
      .container { flex-direction: column; }
      .left, .right { border-right: none; border-bottom: 1px solid #eee; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="left">
      <h1>Listify 🎶</h1>
      <p><b>음악 추천과 플레이리스트 관리가 한 곳에!</b></p>
      <ul>
        <li>회원가입 및 로그인 (JWT 인증)</li>
        <li>음악 추천 및 검색 (Spotify API 연동)</li>
        <li>플레이리스트 생성/관리</li>
        <li>음악 미리듣기(Spotify 웹 플레이어)</li>
        <li>사용자 프로필 관리 및 수정</li>
        <li>공지사항 확인</li>
      </ul>
      <h3>기술 스택</h3>
      <ul>
        <li>Frontend: React, Vite, TypeScript</li>
        <li>Backend: Python (Flask)</li>
        <li>Database: MySQL</li>
        <li>외부 API: Spotify API</li>
        <li>DevOps/Deployment: Docker</li>
      </ul>
    </div>
    <div class="right">
      <div class="video">
        <h3>프로젝트 소개 영상</h3>
        <iframe width="100%" height="220" src="https://www.youtube.com/embed/프로젝트소개영상ID" frameborder="0" allowfullscreen></iframe>
      </div>
      <div class="video">
        <h3>시연 영상</h3>
        <iframe width="100%" height="220" src="https://www.youtube.com/embed/시연영상ID" frameborder="0" allowfullscreen></iframe>
      </div>
      <div class="links">
        <a href="https://your-deploy-url.com" target="_blank">배포 사이트 바로가기 🚀</a><br>
        <a href="https://your-ppt-url.com" target="_blank">프로젝트 발표자료(PPT) 📑</a>
      </div>
    </div>
  </div>
</body>
</html>
