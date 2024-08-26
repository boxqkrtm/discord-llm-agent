# discord llm agent

# How To Use
.env.example을 참고하여 .env파일을 만들고 discord, google api key를 넣어주세요<br>
`pip install -r requirements.txt`<br>
`python index.py`
<br>
# 참고
초기 실행의 경우 slash 명령어 등록을 위하여
```python
async def on_ready():
    #await tree.sync()
```
해당 부분의 주석 해제 후 한번 실행하여 명령어 등록 후 사용
<br>다음 번 부터는 주석 처리하여 사용하면 됩니다.<br>
(계속 실행 시 too many requests 에러 발생)
# 기본 기능
- ssh 접속하여 명령어 실행 및 응답