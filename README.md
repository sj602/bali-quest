# 🌺 Bali Quest - 발리풍 마리오 웹게임

## 무료 배포 방법 (3가지)

### 1. GitHub Pages (추천 ⭐)
```bash
git init
git add .
git commit -m "init: bali quest game"
git remote add origin https://github.com/<your-id>/bali-quest.git
git push -u origin main
# Settings → Pages → Branch: main / root → Save
# URL: https://<your-id>.github.io/bali-quest
```

### 2. Netlify Drop
- netlify.com/drop 에서 폴더를 드래그 앤 드롭
- 즉시 URL 발급 (https://xxxx.netlify.app)

### 3. Vercel
```bash
npm i -g vercel
vercel  # 폴더 루트에서 실행
```

## 기술 스택
| 항목 | 내용 |
|------|------|
| 언어 | 순수 HTML5 + CSS3 + Vanilla JS |
| 렌더링 | Canvas 2D API |
| 외부 의존성 | Google Fonts (CDN) |
| 번들러 | 없음 (단일 파일) |
| 배포 비용 | 완전 무료 |

## 조작법
| 키 | 동작 |
|----|------|
| ← → / A D | 이동 |
| ↑ / Space / W | 점프 (누르고 있으면 높이 점프) |
| Z / Shift | 대시 |

## 게임 목표
- 🪙 황금 연꽃 코인 수집 (+100점)
- 🐒 원숭이 적 밟기 (+200점)
- 🌺 발리 사원 깃발 도달 (+1000점 + 보너스)
- ❤️ 목숨 3개 — 적에게 닿거나 용암에 빠지면 감소

## MVP 이후 추가 가능한 기능
- [ ] BGM (Web Audio API로 발리 가믈란 음악)
- [ ] 멀티 레벨 (Stage 2, 3)
- [ ] 파워업 아이템 (발리 크리스 단검 등)
- [ ] 로컬 스토리지 하이스코어
- [ ] 모바일 조이스틱 개선
- [ ] 스프라이트 시트 교체
