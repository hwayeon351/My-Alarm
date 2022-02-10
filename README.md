# My-Alarm
### 알람 안드로이드 앱

#### 시간을 지정해 알람을 설정하고, 지정된 시간이 되면 알람이 울리는 기본 알람 앱 입니다.
### Blog
* <https://hwayomingdlog.tistory.com/240>
* <https://hwayomingdlog.tistory.com/243>
</br>


## 주기능
### 시간 재설정
* 시간 재설정 버튼을 클릭해서 알람을 설정할 시간을 정할 수 있습니다.
* TimePicker는 기본적으로 현재 시각으로 맞춰져 있으며, 시, 분, 오전/오후를 지정할 수 있습니다.
* 현재 시각을 기준으로 이미 지나간 시각을 설정하면 다음 날에 지정된 시간에 알람이 울립니다.

### 알람 켜기/끄기
* 알람 켜기 버튼을 클릭하면 시간 재설정을 통해 지정한 시간에 알람이 울립니다.
* 알람 끄기 버튼을 클릭하면 이전에 설정된 알람이 취소 됩니다.
</br>

## 활용 기술
* SharedPreferences - 알람을 설정하고 앱을 재실행하여도 이전에 설정한 알람 값을 받아오기 위해 SharedPreferences를 활용해 데이터를 저장하였습니다.
* AlarmManager - 지정한 시각에 작업을 실행하거나, 반복 알람을 설정하기 위해 AlarmManager을 사용했습니다.
* BroadcastReceiver - 지정한 시각이 되어 AlarmManager가 호출하면 BroadcastReceiver가 Notification을 기기에 띄우도록 구현하였습니다.
</br>

***
<img src="/img/img0.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img1.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img2.png" width="300px" height="600px" title="" alt=""></img>
