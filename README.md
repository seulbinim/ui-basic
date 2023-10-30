###### UI 실습 - 기본 편

## 저장소 복제하기 (likelion-8 폴더 안에 복제를 권장)

```sh
git clone https://github.com/seulbinim/ui-basic.git
```

## 복제한 저장소로 이동

```sh
cd ui-basic
```

## 복제한 저장소의 리모트 브랜치 조회하기

```sh
git remote update
git branch -r
```

## 복제한 저장소의 ssam 브랜치 가져오기

```sh
git checkout -t origin/ssam
```

## ssam 브랜치의 업데이트 된 내용을 로컬로 가져오기

```sh
git pull --set-upstream origin ssam
```
