---
name: Experiment
about: 가설-설계-결과를 남기는 실험 이슈 (의료영상 지표 포함)
title: "[EXP] "
labels: ["type:experiment"]
---

## 1) 가설(Hypothesis)
- 예) SRAD 적용 시 CNR +10%, 지연 +≤5ms

## 2) 데이터/셋업
- 데이터 버전/폴더: …
- 전처리: …
- 환경: (Conda, CUDA, 드라이버)
- 고정 커밋/브랜치: …

## 3) 설계(변수/고정/반복)
- 변수: (kernel, bin size, gain, DR, compounding, batch, patch size …)
- 고정값: …
- 반복/seed: n=3
- 지표: **Dice, HD, NSD, CNR, SNR, SSIM, FPS, 지연(ms)**

## 4) 실행 커맨드
