# 서울대학교 수리과학부 박사과정을 위한 학위논문 템플릿

[서울대학교 컴퓨터공학부 박사 학위논문 작성을 위한 LATEX 템플릿을](https://github.com/skywalker023/thesis-template-snu-cse) 수정해 수리과학부 용으로 만든 템플릿입니다.

이 템플릿은 `zeta709`님께서 전체 학부에서 조금씩만 수정하면 사용할 수 있게끔 만들어 두신 [버전](https://github.com/zeta709/snuthesis)에 기초해서 컴퓨터공학부만을 위해 `sjp38`님께서 수정한 [버전](https://github.com/sjp38/snucse_phd_thesis_template)을 기반으로 둔
`skywalker023`의 [버전](https://github.com/skywalker023/thesis-template-snu-cse)을 2025년 도서관 제출 기준으로 업데이트하고 수리과학부 용으로 조금 수정한 템플릿입니다.

### 수리과학부에서 많이 사용된 텍 템플릿이 아닙니다.

대표적인 차이점은:
1. `book` 클래스 기반이 아니고 `report` 클래스를 기반으로 만든 커스텀 클래스이며 B5 4x6배판 기준입니다.
2. 영문 인준서가 포함이 되어 있지 않습니다 (전통인가 모르겠는데 일단 도서관에서는 영문 인준서를 요구 하지 않습니다)
3. 국문 인준서 포맷이 수정이 되어 있습니다
4. Copyright 페이지 포함이 되어 있지 않습니다.
5. `book` 클래스가 아니라서 헤더에 챕터명이 표시되지 않습니다.
6. `Table of content`가 살짝 다릅니다.
7. 수학용 매크로 커맨드가 포함되어 있지 않습니다.
8. 기타 장점이거나 단점인 차이점이 존재 할 수 있습니다.


해당 사항들을 유의하시고 사용하시기 바랍니다.

이하는 기반 리포지토리의 README 입니다.


# 서울대학교 컴퓨터공학부 박사과정을 위한 학위논문 템플릿

서울대학교 컴퓨터공학부 박사 학위논문 작성을 위한 LATEX 템플릿입니다.
이 템플릿은 `zeta709`님께서 전체 학부에서 조금씩만 수정하면 사용할 수 있게끔 만들어 두신 [버전](https://github.com/zeta709/snuthesis)에 기초해서 컴퓨터공학부만을 위해 `sjp38`님께서 수정한 [버전](https://github.com/sjp38/snucse_phd_thesis_template)에 기반합니다.
Template 내용을 좀더 추가하고, Overleaf에서도 사용 가능하도록 했습니다.

## 사용법
`thesis.tex` 파일을 열어 학부명, 논문 제목, 저자명, 학번, 지도교수님, 학위 수여일, 논문 인준일, 심사위원 다섯 분 성함만 수정하고 그 아래 부분부터 평소 논문 쓰듯 논문을 쓰시면 됩니다. 레퍼런스는 `thesis.bib` 파일을 사용하시면 됩니다.

### 컴파일
- **make를 사용하는 경우**: 위 파일들과 같은 디렉토리에서 `make` 명령을 입력하면, 자동으로 `target` 디렉토리가 생성되면서 그 안에  `thesis.pdf` 파일이 생성됩니다.
- **Overleaf 사용하는 경우**: 화면 좌측 상단의 Menu에서 latex compiler는 pdflatex로 하고, texlive는 2021로 설정해줍니다.

## 작성자
- 최초 작성자: [박성재](https://sjp38.github.io/ko/) (2019.08 졸업)
- 추후 편집자:
    - [김병창](https://bckim92.github.io) (2022.02 졸업)
    - [김현우](https://hyunw.kim) (2023.08 졸업 예정)

Pull request 언제나 환영입니다 🙌🏻
