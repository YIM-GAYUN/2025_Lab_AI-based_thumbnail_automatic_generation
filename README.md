# 2025_Lab_AI-based_thumbnail_automatic_generation
[2025_lab] <br>
<h2>AI 기반 동영상 콘텐츠 썸네일 자동 생성 시스템</h2>
<hr>

:four_leaf_clover: <strong>프로젝트 소개</strong> <br>
본 프로젝트는 사용자의 입력을 바탕으로 영상을 분석하고, STT(음성 인식) 및 키워드 추출, CLIP 기반의 핵심 프레임 추출 과정을 거쳐, 사용자 선호도에 맞는 
레이아웃을 구성한 뒤, 키워드 기반의 제목 이미지까지 자동으로 생성하여 최종 썸네일 이미지를 완성하는 일련의 과정을 구현한다. 이러한 자동화된 워크플로우는 
크리에이터가 영상 제작 과정에서 겪는 반복적이고 시간 소모적인 썸네일 제작 부담을 획기적으로 줄여주며, 영상의 핵심 메시지와 시각적 특징을 과학적으로 
분석하여 썸네일 품질을 크게 향상시킬 수 있다. 특히, STT와 GPT, KeyBERT, CLIP 등 최근 다방면으로 많이 활용되는 AI 기술을 융합적으로 적용함으로써, 영상의 
주제와 맥락을 심층적으로 파악하고, 시청자의 시선을 끌 수 있는 핵심 장면과 키워드를 효과적으로 도출할 수 있다. 또한, 사용자의 채널 특성과 선호도를 반영한 
맞춤형 레이아웃 및 디자인을 자동으로 적용함으로써, 크리에이터의 개성을 살리면서도 클릭률(CTR)을 높일 수 있는 최적의 썸네일을 제공한다.
<hr>

:four_leaf_clover: <strong>활용 데이터 및 API</strong> <br>
- <em> GPT API</em>: 키워드를 효과적으로 추출하는 기능, 키워드 기반 채널의 제목 스타일을 반영한 제목 생성 기능을 구현<br>
- <em>구글 클라우드 youtube_data_v3 API</em>: 입력받은 본인 채널의 uploads playlist ID를 가져오고, 이 playlist에서 최근 영상 4개의 제목을 가져오도록 하는 코드를 구현<br>
<hr>

:four_leaf_clover: <strong>구현 과정 및 결과</strong> <br><br>
![Image](https://github.com/user-attachments/assets/4feeebf0-9739-4e10-9920-9cc924e6901c)



