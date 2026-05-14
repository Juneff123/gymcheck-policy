# GymCheck 정책 페이지 호스팅 가이드

이 폴더를 그대로 새 GitHub repo (예: `gymcheck-policy`) 에 푸시하고,
**Settings → Pages → Source: `main` branch / `/ (root)`** 로 설정하면 즉시 호스팅됩니다.

발급되는 URL 형식:
```
https://<username>.github.io/gymcheck-policy/
https://<username>.github.io/gymcheck-policy/privacy-policy-ko/
https://<username>.github.io/gymcheck-policy/privacy-policy-en/
https://<username>.github.io/gymcheck-policy/terms-of-service-ko/
```

## 빠른 절차 (5분)

1. GitHub 에서 새 public repo 만들기 — 이름 `gymcheck-policy`
2. 로컬에서:
```bash
cd "/Users/junelee/어플개발/헬스 어플/gymcheckproject/docs/policy-hosting"
git init -b main
git add .
git commit -m "Initial policy pages"
git remote add origin https://github.com/<username>/gymcheck-policy.git
git push -u origin main
```
3. GitHub 웹: repo → Settings → Pages → Source = `Deploy from a branch` / Branch = `main` / Folder = `/ (root)` → Save
4. 약 1~2분 후 노출되는 URL 확인

## App Store Connect 에 입력
- **앱 정보 → 개인정보처리방침 URL**: `https://<username>.github.io/gymcheck-policy/privacy-policy-ko/`
- **지원 URL**: `https://<username>.github.io/gymcheck-policy/`
- 인앱 결제 등록 시 **이용약관 URL** 도 동일 패턴

## 앱 코드 측 갱신
`AppConfig.Links` 의 URL 도 실제 호스팅 URL 로 갱신:
```swift
static let privacyPolicy = "https://<username>.github.io/gymcheck-policy/privacy-policy-ko/"
static let termsOfService = "https://<username>.github.io/gymcheck-policy/terms-of-service-ko/"
```

## 정책 수정 후 재배포
이메일/주소/조항 변경 → md 파일만 수정 → `git push` → 자동 재배포 (수십 초).
