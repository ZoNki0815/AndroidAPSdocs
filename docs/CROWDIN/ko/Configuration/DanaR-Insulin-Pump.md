# 다나R 펌프

*다음 지침은 다나R에서 앱과 펌프를 구성하기 위한 것입니다. 2017년에 출시된 다나RS를 갖고있는 경우 [다나RS 인슐린펌프](./DanaRS-Insulin-Pump)를 방문하세요.*

* 펌프에서 Main Menu > Setting > User Option 으로 이동하세요.
* “8. Extended Bolus”을 On으로 변경하세요. 

![다나R 펌프](../images/danar1.png)

* Menu > Setting > Discovery 으로 이동하세요.
* 스마트폰 환경설정에서 블루투스로 이동하고, 주변 디바이스를 검색한 다음, DanaR 시리얼 번호를 선택하고 암호를 입력합니다(암호는 0000). 만약 검색을 해도 DanaR이 표시되지 않으면 스마트폰을 재시작한다음, DanaR펌프 배터리를 꺼내고 교체한 후 이 두 단계를 다시 시작합니다.

* AndroidAPS에서 구성관리자로 들어가 갖고있는 DanaR의 종류를 선택합니다(다나R,다나 한글, 다나R v2)

* 오른쪽 상단에 있는 점 3개를 눌러 메뉴를 선택하세요. 설정을 선택하세요.
* 다나R 블루투스 장치를 선택하고, DanaR 시리얼 번호를 클릭하세요.
* 펌프 비밀번호를 선택하고 비밀번호를 입력하세요. (기본 비밀번호는 1234)
* AndroidAPS가 Basal양을 200프로 이상 늘어나게 하려면, ">200% 주입위한 확장Bolus 사용"을 활성화하세요. 이것은 식사를 위해 확장Bolus를 주입한 동안은, 기본설정보다 높은 임시Basal로 Loop할 수 없음을 의미합니다.
* 다나R 펌프 세팅의 설정에서 기본 Bolus주입 속도를 변경할 수 있습니다(1u당 12초, 1u당 30초 및 1u당 60초).
* 펌프의 Basal 단위를 0.01U/h로 하세요.
* 펌프에서 확장Bolus를 활성화하세요.

## 다나R 펌프 사용시 다른 시간대 국가로의 여행

For information on traveling across time zones see section [Timezone traveling with pumps](../Usage/Timezone-traveling#danarv2-danars).