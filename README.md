# iBeacon-Notification-Server

iPhone & Android 모바일 운영체제에서 iBeacon에 진입하였을 때 major, minor 값에 따라 Remote Notification 서비스를 사용할 수 있도록 개발하고 있는 프로젝트.

기본적으로 iPhone & Android 모바일 운영체제에서 통합적인 Remote Notification이 iBeacon의 기능과 관계없이 작동하되, iBeacon의 Event에 따라 Database의 누적된 변화를 빅데이터화하여 지능적인 Notification 서비스가 Node.js를 통해 안정적으로 실행 가능하도록 목표를 두고 있다.


### Environment
 - Nodelipse

 
### Todos

 - major, minor 값에 따른 기본 Notification 기능
 - Notification과 Database 제어 및 관리 기능
 - 공간서비스를 제공하는 업주들의 개별적인 Notification 송신 기능