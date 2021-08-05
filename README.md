# xiat

![xiat](https://github.com/ASTRAL7X/xiat/actions/workflows/xiat.yml/badge.svg)

[GitHub Action](https://github.com/features/actions)으로 1일 1회, 커밋과 푸시를 자동화합니다.

xiat 심는 법
-
1. 저장소를 포크합니다.

2. [개인 접근 토큰 발급](https://github.com/settings/tokens/new) 페이지에 접속하고, ```workflow``` 범위를 고르고, 새 토큰을 발급합니다. 발급한 토큰 값은 복사합니다.

3. 저장소 ```Settings``` 탭의 ```Secrets``` 설정에 접속합니다.

4. ```New repository secret```을 클릭하고, 이름은 ```GH_TOKEN```, 값은 #2에서 발급한 토큰 값을 붙여넣고 새 Secret을 만듭니다.

5. 저장소 ```Actions``` 탭에서 Workflow를 켭니다.

6. 모든 준비가 끝났습니다. 잔디를 감상하세요.