# 이덴플랜잇 GitHub Pages 배포

현재 반영 사항: 생성 사진 3종, 한글 제목 나눔스퀘어 네오 Bold, 본문 Pretendard, 영문 메인 제목 최초 디자인 복원.

1. GitHub에서 새 Public 저장소(예: edenplanit)를 만들고 README 추가를 선택합니다.
2. Add file > Upload files에서 이 폴더 안의 index.html, images 폴더를 함께 올립니다. 바깥 폴더나 ZIP 파일을 올리지 마세요.
3. Commit changes로 저장합니다.
4. Settings > Pages > Build and deployment > Source를 Deploy from a branch로 선택합니다.
5. Branch는 main, 폴더는 /(root)로 지정하고 Save를 누릅니다.
6. 배포가 완료되면 Settings > Pages에 표시되는 Visit site 주소로 접속합니다.

파일 구조:
index.html
images/classroom.png
images/workshop.png
images/workspace.png

웹폰트는 CDN에서 불러옵니다. index.html을 브라우저에서 열어 미리 확인할 수 있습니다.
문의 양식은 데모입니다. GitHub Pages는 HTML/CSS/JS 정적 호스팅이므로 실제 문의 저장은 외부 API/폼 서비스 등 별도 연결이 필요합니다.
기존 Sites 공개 주소와 GitHub Pages 주소는 별개입니다.