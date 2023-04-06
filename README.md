# fastapi_mastery
FastAPI tutorial 학습부터, 실전에서 쓰이는 최적성능까지 모두 마스터할 정보를 기록한다.

## 기본학습 참고자료
- 박응용 저자의 '점프 투 FastAPI'

## 목표 
- 1. FastApi(BE) + Svelte(FE)로 python fastapi로 웹서비스를 구축해본다. : 기본API사용법, OAuth로그인, Logging, FastAPI와 uvicorn(ASGI타입 Application Server을 연동테스트.
    - Target Folder : ./fastapi_tutorial
    
- 2. FastAPI 최적성능을 위한 환경구성 : 
    - Target Folder : ./fastapi_be_perf
    - 참고자료 : https://travisluong.medium.com/fastapi-vs-fastify-vs-spring-boot-vs-gin-benchmark-b672a5c39d6c
    - 'FastAPI + asyncpg + ujson + gunicorn 8w (4831 req/sec)' 환경을 구축하여 테스트해본다.
    
- 3. Flask 최적성능 vs FastAPI 최적성능 환경을 비교해본다.
    - Target Folder : ./flask_be_perf
    - Target Folder : ./fastapi_flask_compare
    - Flask 최적성능 : Flask + psycopg2 + gunicorn 4w

- 4. Top으로 선정된 환경으로 `데이터학습용 Stock시세' 제공 서비스API 를 개발한다.
    - Target Folder : ./fastapi_restapi_be
    - zipline 백테스트 환경에 최적화,
    - 데이터분석가가 이용하기 편하게,
    - 국내시세 모든 방식을 제공.

- 5. BE뿐만 아니라, FE또한 제공하여 웹서비스 대시보드 환경을 구축한다.

      
    
