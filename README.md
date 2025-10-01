파이썬 실행환경 설치 커맨드

pip 설치의 준비
`Invoke-WebRequest -Uri https://bootstrap.pypa.io/get-pip.py -OutFile get-pip.py`

pip를 설치
`./python.exe get-pip.py`

pip 업그레이드 및 필수요소 설치
`./python.exe -m pip install --upgrade pip setuptools wheel`

기본 요청 라이브러리 설치 (requirements.txt 참조)
`./python.exe -m pip install -r requirements.txt --no-warn-script-location`

torch 설치
`./python.exe -m pip install torch_cluster torch_scatter torch_sparse torch_spline_conv -f https://data.pyg.org/whl/torch-2.2.0+cpu.html`

torch-geometric 설치
`./python.exe -m pip install torch-geometric==2.6.1`

spacy 요소 다운로드
`./python.exe -m spacy download en_core_web_sm`
`./python.exe -m spacy download en_core_web_md`
