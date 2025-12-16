# RideOn FE - Vercel 배포용 레포

RideOn 프론트엔드의 Vercel 배포를 위한 개인 레포지토리입니다.

**배포 주소**: https://saessakbori.site

## 레포지토리 설명

- **메인 개발 레포**: [2025-All4Land-RideOn/FE](https://github.com/2025-All4Land-RideOn/FE)
- **이 레포의 목적**: Vercel 무료 배포를 위한 정적 빌드 파일 호스팅
- **업데이트 방식**: 메인 레포에서 빌드 후 자동 배포

## 배포 프로세스

1. 메인 레포에서 개발 및 커밋
2. GitHub Actions를 통해 빌드 (`npm run build`)
3. 빌드 결과물(`dist/`) 자동으로 이 레포에 push
4. Vercel이 자동으로 감지하여 배포

## 주의사항

- 이 레포의 파일은 자동 생성되므로 직접 수정하지 않음
- 모든 개발 작업은 메인 레포에서 진행
- 이 레포는 배포 목적으로만 사용
