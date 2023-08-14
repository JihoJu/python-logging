# python-logging

로그포맷

- 로그 포맷: [$time_local][$log_level][[$json_msg]]
    
    - 멀티라인 허용 x
    - json_msg는 "{"로 시작하여 "}"로 종료
    - json schema
        
        1. step: 처리 단계
        2. cnt: 처리/에러 건수
        3. msg: 처리/에러 메시지 