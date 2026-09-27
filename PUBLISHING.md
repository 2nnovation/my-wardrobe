# 모바일 옷장

현재 로컬 옷장 화면을 GitHub Pages에 게시한 정적 보기 페이지입니다.
현재 보유, 위시리스트, archive, 프로필, 메모가 HTML에 포함됩니다.
모든 방문자가 볼 수 있는 공개 데이터입니다. 사용자 공개 승인: 2026-09-28.

사이트에서 선택한 항목이나 내려받은 작업 요청은 원본 옷장 DB를 직접 수정하지 않습니다.
원본 수정은 로컬 Work에서 진행한 뒤 화면과 이미지를 다시 게시합니다.

로컬 갱신 순서: 옷장에서 wardrobe.ps1 validate/rebuild → export_pages.py 실행 → 변경 확인 → 일반 commit/push.
저장소: https://github.com/2nnovation/my_wardrobe
예상 사이트: https://2nnovation.github.io/my_wardrobe/
Pages 설정: main 브랜치, /(root), Deploy from a branch.
