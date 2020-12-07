### vpc 만들기: IP 결정 시 고려 사항

Private IP 표준 권장

-10.0.0.0/8

-172.16.0.0/12

-192.168.0.0/16

예약된 IP 주소 총 5개

-10.0.0.0: 네트워크 주소

-10.0.0.2: AWS에서 예약한 DNS 주소

-10.0.0.3: AWS 에서 향후 사용을 위하여 예약

-10.0.0.255: 브로드캐스트 주소=> VPC 에서는 브로드캐스트 지원 X, AWS 예약

![image-20201207165244909](C:\Users\eun-hye.kim\AppData\Roaming\Typora\typora-user-images\image-20201207165244909.png)




