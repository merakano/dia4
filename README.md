코끼리 폴더를 폴더채 다운받아서 아무곳에나 넣고 사용하면 됩니다.
실행파일은 코끼리.exe 입니다.

스킬을 메인스킬, 핵심스킬, 기본스킬, 그외 쿨올때마다 쓰면 좋은 스킬1 스킬2, 이렇게 구분하였습니다.
메인스킬은 말 그대로 메인스킬입니다 (예를들면, 구상번개).  핵심스킬과 기본스킬은 다 아시는바와 같구요.
당연히 핵심스킬을 메인으로 쓸 수 있습니다. (예를들면 연쇄번개를 메인으로 쓰는 경우).  이런 경우, 설정에서 메인스킬에 연쇄번개가 들어가면 되고, 핵심스킬은 그냥 비워두면 됩니다.

알고리즘)
디아블로는 매크로를 방지하기 위한 몇가지 트릭을 가지고 있는 듯 합니다.  화면 전반에 걸쳐서 눈에 잘 보이지 않는 노이즈를 밀리밀리초 단위로 깔고 있어 보입니다.  그리고, 물리적인 키보드나 마우스클릭이 아니면 방어하는 메카니즘도 가지고 있습니다.  
그래서, 스킬 사용을 위해는 이미지를 따와서, 노이즈를 없애고 게임과 비교하여 상태를 파악하는 알고리즘을 택했습니다.
자동물약은 체력통에서 빨간색만 따와서, 체력이 없을때와 있을때의 빨간색 정도를 비교하는 방식을 창조해 봤습니다.  잘 되는데, 문제는 '보강' 상태때의 값을 아직 가져오지 못했습니다.  
스킬자동시전은
메인스킬 키를 누르면 -> 메인스킬을 쓸 수 있으면 메인스킬 먼저, 마나가 떨어져서 못쓰면 -> 기본스킬 -> 쿨 스킬들에 쿨 들어왔으면 쿨스킬 
쉽게 말해서, 마나가 허용하는 한, 메인스킬 우선입니다.

글쓰는거가...어려워...

