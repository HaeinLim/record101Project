# 금반 말고 음반
회원은 음반 조회 및 구매가 가능하고 관리자는 음반의 재고관리 및 회원관리가 가능한 프로그램입니다.

## 목차
  - [개요](#개요)
  - [프로그램 설명](#프로그램-설명)
  - [프로그램 화면](#프로그램-화면)
## 개요
  - 프로젝트명 : 금반말고 음반
  - 프로젝트 진행기간 : 2023.04.19-2023.04.27
  - 사용 기술 : JAVA, JFrame, Oracle, SQL
  - 팀 구성원 : 임해인 외 4명

## 프로그램 설명
<div align="center">
  <table>
    <tr>
      <td>
        <img src="https://github.com/HaeinLim/Record101Project/assets/140698817/0e759991-8627-4b8c-88ef-3b84d7977e39" width="500" height="300">
      </td>
    </tr>
    <tr>
      <td align="center">시작 화면</td>
    </tr>
  </table>
</div>
K-POP 열풍에 따라 음악 시장이 활성화됨에 따라 음반 판매 프로그램을 개발하게 되었습니다.

  - 회원가입을 통해 회원되기 🧑‍🤝‍🧑 <br>
    음반을 조회 및 구매하기 위해서는 회원가입이 필수입니다. 시작 화면에서 회원가입 버튼을 클릭한 후 이름, 아이디, 비밀번호, 비밀번호 확인, 전화번호를 모두 기입해야
    가입이 진행됩니다. 아이디의 경우 중복 체크가 필수이며, 모든 값을 제대로 입력했다면 가입 완료 버튼을 클릭해 회원가입을 완료합니다. 이후 프로그램을 이용하고 싶을 때
    아이디와 비밀번호를 입력하여 로그인을 진행할 수 있습니다.

  - 음반 검색하고 구매하기 💿💵 <br>
    회원은 음반의 제목이나 가수명을 두 글자 입력 후 검색하면 원하는 음반을 조회할 수 있습니다. 음반을 구매하기 위해 검색한 음반 내역을 클릭하면 자동으로 하단의
    가수명이 채워지며, 수량을 1 이상 입력한 후 구매 버튼을 클릭하면 구매가 진행됩니다. 다시 해당 음반을 조회해보면 구매한만큼 재고 수량이 줄어든 것을
    확인할 수 있습니다.

  - 관리자 🧑‍💼 <br>
    관리자 계정으로 로그인하면 '관리자로 로그인합니다' 알림창과 함께 재고관리와 회원관리 중 선택할 수 있는 화면으로 이동합니다. 아이디에 'admin'을 포함하면
    관리자로 인식할 수 있도록 구현했습니다.

  - 음반의 재고관리 📚 <br>
    관리자는 검색창에 음반의 제목이나 가수명을 두 글자 이상 입력 후 검색하면 해당 음반의 정보를 확인할 수 있습니다. 출력 버튼을 클릭하면 모든 음반의 정보를
    조회할 수 있으며, 여기서 음반의 재고 수량을 추가, 수정, 삭제할 수 있습니다.

  - 회원관리 🧑‍🤝‍🧑 <br>
    관리자는 검색창에 회원의 이름을 두 글자 이상 입력 후 검색하면 해당 회원의 정보를 확인할 수 있습니다. 출력 버튼을 클릭하면 모든 회원의 정보를 조회할 수 있고,
    회원의 정보를 수정할 수 있습니다.

## 프로그램 화면

  - 시작 및 회원가입 화면

<div align="center">
  <table align="center">
      <tr>
        <th>시작화면</th><th>회원가입</th>
      </tr>
      <tr>
        <td>
          <img src="https://github.com/HaeinLim/Record101Project/assets/140698817/0e759991-8627-4b8c-88ef-3b84d7977e39" width="400" height="300">
        </td>
        <td>
          <img src="https://github.com/HaeinLim/Record101Project/assets/140698817/dccddb87-acf7-4100-af91-721eab0cc213" width="400" height="300">
        </td>
      </tr>
      <tr>
        <td>
          - 로그인 진행 가능<br>
          - 회원가입 미 진행시 사용 불가
        </td>
        <td>
          - 모든 정보 기입 필수<br>
          - 아이디 중복 체크 필수 <br>
        </td>
      </tr>
  </table>
</div>

  - 회원의 음반 조회 및 구매

<div align="center">
  <table align="center">
      <tr>
        <th>음반 조회 및 구매 화면</th>
      </tr>
      <tr>
        <td>
          <img src="https://github.com/HaeinLim/Record101Project/assets/140698817/dde29ed1-2562-4100-bf21-4d85b2922a32" width="400" height="300">
        </td>
      </tr>
      <tr>
        <td>
          - 검색창에 음반의 제목이나 가수명을 두 글자 이상 입력 후 <br>
            검색 시 해당 음반의 정보 조회 가능<br>
          - 구매를 원하는 음반 내역을 클릭한 후 자동으로 가수명이 채워지면<br>
            수량을 입력한 후 구매 버튼을 클릭해 구매 진행
        </td>
      </tr>
  </table>
</div>

  - 관리자

<div align="center">
  <table align="center">
    <tr>
      <th>관리자페이지</th><th>재고관리</th><th>회원관리</th>
    </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/HaeinLim/Record101Project/assets/140698817/fb0ccdb4-311c-486c-8356-1939e666462d" width="400" height="200">
      </td>
      <td align="center">
        <img src="https://github.com/HaeinLim/Record101Project/assets/140698817/642ad6b9-4b91-4fc7-9d72-c55a15159901" width="400" height="200">
      </td>
      <td align="center">
        <img src="https://github.com/HaeinLim/Record101Project/assets/140698817/d3dc0030-740f-4e70-a7b4-a8c0d863ab9e" width="400" height="200">
      </td>
    </tr>
    <tr>
      <td>
        - 관리자로 로그인 시 두 관리 중 하나 선택 가능
      </td>
      <td>
        - 검색창에 음반의 제목이나 가수명을 두 글자 이상 입력 후<br>
          검색하면 음반의 정보 조회 가능<br>
        - 출력 버튼을 클릭해 모든 음반의 정보 조회 가능<br>
        - 추가, 수정, 삭제를 통해 음반의 재고관리 가능
      </td>
      <td>
        - 검색창에 회원의 이름을 두 글자 이상 입력 후<br>
          검색하면 해당 회원의 정보 조회 가능<br>
        - 출력 버튼을 클릭해 모든 회원의 정보 조회 가능<br>
        - 회원의 정보 수정 가능
      </td>
    </tr>
  </table>
</div>
    
