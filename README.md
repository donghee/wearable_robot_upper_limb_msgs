# wearable_robot_upper_limb_msgs

상지 로봇 명령 서비스 메시지 확인
```
ros2 interface show wearable_robot_upper_limb_msgs/srv/UpperLimbCommander
```

상지 로봇 명령 서비스 실행
```
ros2 service call /upper_limb_command wearable_robot_upper_limb_msgs/srv/UpperLimbCommander
```


상지 로봇 상태 출력
```
ros2 topic echo /upper_limb_state
```
