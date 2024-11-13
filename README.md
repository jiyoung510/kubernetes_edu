# kubernetes_edu
20241111~20241115

takytaky@empas.com

--version kubernetes 1.27 

- NatNetwork 구성
  . 192.168.137.0/24
  . 192.168.137.100/24
- Windows
  . NIC 59.29.224.*
  . 192.168.56.1:port

- docker install
    https://docs.docker.com/engine/install/rhel/

- https://labs.play-with-k8s.com/

- https://killercoda.com/
- .https://www.udemy.com/?utm_source=adwords-brand&utm_medium=udemyads&utm_campaign=Brand-Udemy_la.KR_cc.KR&campaigntype=Search&portfolio=BrandDirect&language=KR&product=Course&test=&audience=Keyword&topic=&priority=&utm_content=deal4584&utm_term=_._ag_130894067178_._ad_561967300013_._kw_%EC%9C%A0%EB%8D%B0%EB%AF%B8_._de_c_._dm__._pl__._ti_kwd-319889856191_._li_9195692_._pd__._&matchtype=b&gad_source=1&gclid=Cj0KCQiA88a5BhDPARIsAFj595gci7emW9kUtMdLM7Dm-AIuAYGJNJiafsb4skVrWRUlHG2wEnZsVrYaAkqXEALw_wcB

- pod의 container ip는 시작할 때가 아니라 실행될 때 받고, 종료되면 ip를 반환한다

** test

- kubectl set image
- kubectl edit (객체의 속성 실시간 변경)
- 템플릿(yaml) 수정 -> kubectl apply
