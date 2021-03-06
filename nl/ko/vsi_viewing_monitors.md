---



copyright:
  years: 2017
lastupdated: "2017-10-23"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# 모니터 보기 및 관리

디바이스 모니터링은 사용자가 디바이스가 온라인 상태이며 응답하는지 확인하기 위해 서비스 및 느린 ping 실행을 시작할 수 있게 해 줍니다.
{:shortdesc}

할당된 시간 범위(서비스 ping의 경우 1초, 느린 ping의 경우 5초) 내에 에코가 수신되지 않으면 계정의 이메일 주소에
경보가 전송됩니다. **상태** 필드의 **작동 중** 상태는 에코가 수신되었음을 나타내며, **작동 중지** 상태는
에코가 수신되지 않았음을 나타냅니다. 기본 모니터를 이미 구성한 경우에는 아래 단계에 따라 디바이스에 대한 모니터링을 보고 관리할 수 있습니다.

   <table>
   <CAPTION>표 1. 디바이스 모니터링 보기 및 관리</CAPTION>
   <THEAD>
   <TR>
   <th>수행해야 하는 조치</th>
   <th>수행할 작업</th>
   </TR>
   </THEAD>
   <TBODY>
   <tr>
   <td>모니터 보기</td>
   <td>
   <ol>
   <li>디바이스 목록에서 <b>디바이스 이름</b>을 클릭하여 디바이스에 액세스하십시오.</li>
   <li><b>모니터링</b> 탭을 클릭하십시오. 모든 현재 ping을 랜딩 페이지에서 볼 수 있습니다. (<b>모니터링</b> 탭은 하나 이상의 모니터가 구성된 경우에만 표시됩니다.)</li>
   </ol>
   </td>
   </tr>
   <tr>
   <td>모니터 추가</td>
   <td>
   <ol>
   <li>디바이스 세부사항 페이지의 <b>모니터링</b> 탭에서 페이지 오른쪽에 있는 <b>모니터 관리</b>를 클릭하여 이 디바이스와 연관된 모니터를 관리하십시오.</li>
   <li>모니터 페이지에서 <b>모니터 추가</b> 탭을 클릭하십시오.</li>
   <li><b>IP 주소</b> 드롭 다운 목록에서 모니터할 IP 주소를 선택하십시오.</li>
   <li><b>모니터 유형</b> 드롭 다운 목록에서 모니터 유형을 선택하십시오.</li>
   <li>알림 옵션을 설정하십시오. <b>알림</b> 드롭 다운 목록에서 사용자에게 문제를 알리려면 <b>사용자에게 알림</b>을 선택하고, 사용자 알림을 사용하지 않으려면 <b>알리지 않음</b>을 선택하십시오.</li>
   <li><b>알림 대기</b> 드롭 다운 목록에서 사용자 알림의 시간 범위를 선택하십시오.</li>
   <li><b>모니터 추가</b> 단추를 클릭하여 디바이스의 모니터를 추가하십시오. 새 모니터가 화면의 <b>기존 모니터 편집</b> 섹션에 표시됩니다.</li>
   </ol>
   </td>
   </tr>
   <tr>
   <td>기존 모니터 편집</td>
   <td>
   <ol>
   <li><b>기존 모니터 편집</b> 표제 아래의 모니터 페이지에서 임의의 모니터 세부사항을 클릭하여 모니터를 편집할 수 있도록 여십시오.</li>
   <li>모니터 유형, 알림, 알림 대기 필드를 업데이트하십시오.</li>
   <li><b>업데이트</b> 단추를 클릭하여 세부사항을 업데이트하십시오. 편집을 취소하려면 <b>취소</b> 단추를 클릭하십시오.</li>
   </ol>
   </td>
   </tr>
   <tr>
   <td>모니터 제거</td>
   <td>
   <ol>
   <li><b>기존 모니터 편집</b> 표제 아래의 모니터 페이지에서 모니터 세부사항 옆에 있는 제거 아이콘을 클릭하십시오.</li>
   <li>모니터를 제거하려면 <b>예</b> 단추를 클릭하십시오. 조치를 취소하려면 <b>아니오</b> 단추를 클릭하십시오.</li>
   </ol>
   </td>
   </tr>
   </TBODY>
   </table>
   
## 다음 단계
   
- 새 모니터가 추가된 경우에는 해당 모니터가 **모니터링** 탭에 표시됩니다. 이 모니터는 해당 디바이스에 5분마다 ping을 실행하며 선택된 ping 유형에 따라 응답을 기대합니다. 기대된 응답이 수신되지 않으면 알림이 선택된 경우, 지정된 시간 범위 내에 계정의 알림 이메일 주소에 이메일이 발송됩니다.
- 모니터가 편집된 경우에는 해당 모니터가 모니터 세부사항에 지정된 대로 계속해서 작동합니다. 유형이 변경된 경우에는 기대된 ping을 수신하는 시간이 달라집니다. 알림 옵션이 변경된 경우에는 사용자가 실패한 시도에 대해 알림을 받는 방식이 새 선택사항에 따라 변경됩니다. 해당 모니터는 **모니터링** 탭에서 계속 액세스할 수 있습니다.
- 모니터가 제거된 경우에는 해당 모니터가 디바이스에 대해 더 이상 작동하지 않습니다. 제거된 모니터와 연관된 모든 모니터링이 중지되며 해당 모니터가 더 이상 **모니터링** 탭에 표시되지 않습니다.
