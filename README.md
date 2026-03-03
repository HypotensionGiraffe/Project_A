# Git 연동 프로젝트

Git으로 버전 관리되는 프로젝트입니다.

## 최초 설정 (한 번만)

커밋을 하려면 Git 사용자 정보를 설정하세요:

```bash
git config --global user.email "your-email@example.com"
git config --global user.name "Your Name"
```

설정 후 초기 커밋:

```bash
git add .
git commit -m "Initial commit: Git 연동 프로젝트 설정"
```

## 시작하기

```bash
# 저장소 클론 (원격이 있는 경우)
git clone <repository-url>
cd git-project

# 변경사항 커밋
git add .
git commit -m "메시지"
git push
```

## 원격 저장소 연결

```bash
# GitHub 등 원격 저장소 추가
git remote add origin https://github.com/사용자명/저장소명.git

# 푸시
git push -u origin main
```
