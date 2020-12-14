gradle 6.0 이상일 때 node download 가 true 면 에러가 발생한다. 

이 때 false 로 변경 후 node 설정 값을 잡아주면 정상 진행되지만 번거로운 점이 있어 gradle을 5.xx로 다운그레이드 한다.

이 후에는 기존 연동 방법과 동일하다.

frontend package.json proxy 값을 서버 주소로 변경해주어야 백엔드와 연동 가능하다.
