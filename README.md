# mymybot
세종대왕봇

신조어와 순화대상어(외래어)를 인식하여 관련된 정보를 제공하고, 친구와 대화하듯 일상대화와 자체학습이 가능한 인공지능 챗봇\n

# 개발환경
-window 10 (x64)\n
-IBM Watson Bluemix
-Python 3.6
-Bothub Studio(Chatbot hosting service)
-Telegram

# 개발목적 
-Chatbot을 통한 오락효과
-신조어 소개를 통한 세대차이 극복
-순화어 제공을 통한 교육적 효과

# 개발과정

1. IBM 블루믹스에 일상대화를 위한 데이터를 학습 (SejongChatbot.json 파일을 블루믹스에 업로드하여 실행 가능)
2. bothub를 이용한 코드 작성
(사용자로부터 입력받은 input 값으로 왓슨 api를 호출하여 얻은 confidence(인식률) 값 또는 intent의 존재 유무에 따라 학습 또는 일상대화로 이어짐)
3. 텔레그램과 연동하여 챗봇 실행
