# Beagle with ROS2 SLAM

Beagle with ROS2 SLAM (Simultaneous Localization and Mapping)은  ROS2(Robot Operating System 2)를 기반으로 하여 Beagle 로봇을 활용하여 SLAM을 학습할 수 있는 데모 프로그램입니다.<br>

ROS2에서 Beagle을 운영 할 수 있는 패키지를 제공합니다. 

![비글배경](https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/c43bef77-3f7d-4ea6-b028-5d082e06cfc6)

## 설치 전 준비 사항
[Ubuntu 22.04 LTS](https://ubuntu.com/) 기준으로 작성 되었습니다. <br>
[ROS2 Humble Hawksbill](https://docs.ros.org/en/foxy/Releases/Release-Humble-Hawksbill.html) 기준으로 작성 되었습니다.<br>
Ubuntu 22.04 LTS 가 설치되어 있는 PC가 필요합니다. <br>
**(ROS2 SLAM은 PC의 성능에 영향을 받습니다. 원할한 사용을 위하여 고사양 PC 사용을 권장합니다.)** <br>
[Ubunt](https://ubuntu.com/) (**Linux**)의 설치 및 사용 방법을 숙지 하고 사용 하십시요.<br>
[ROS2](https://wiki.ros.org/)의 설치 및 사용 방법을 숙지 하고 사용 하십시요.<br>


## 주요 제공 사항

>ROS2 Humble install package<br>
Gazebo simulation SLAM<br>
Beagle SLAM<br>
Gazbo SLAM 시연 동영상 <br>
Beagle SLAM 시연 동영상<br>
사용자 메뉴얼 <br>


아래 버튼을 눌러 ROS2 Package / 메뉴얼 / 시연 동영상을 다운받아 받아 SLAM을 직접 체험해보세요.


[Beagle ROS2 다운로드](https://www.dropbox.com/scl/fo/tginbjaoxmwcnhom2bx1i/AEbvqcCbhfh3AA-ftZ2CNxo?rlkey=tthz63ix16qcdu983hb2a8yk8&dl=0)


<details>

<summary>다운로드 방법</summary>

위 링크로 들어가, 다음과 같이 **로그인하지 않은 상태**로 다운로드를 진행할 수 있습니다.<br>
[ 다운로드 ] → [ 또는 다운로드만 하고 계속 진행하세요. ] 순으로 클릭합니다.

<img src='https://github.com/RobomationLAB/Beagle_with_ROS2_SLAM/assets/160319639/0b1e2a28-728a-4a75-a51e-a5b009172bee' width=500>

<br><br>

브라우저 우측 상단에 다운로드 버튼을 눌러 설치된 zip파일을 선택하고, 설치된 zip파일을 원하는 위치에 압축을 해제합니다.<br>
폴더로 제공하는 내용과 압축 파일의 내용은 동일합니다. 


<img src='https://github.com/RobomationLAB/Beagle_with_ROS2_SLAM/assets/160319639/8cd46237-9395-4b0b-a201-cc625332348a' width=600>


---


</details>

<br><br>

---

**Beagle ros2 manual.pdf 문서를 확인하여 설치 및 사용법을 숙지 하고 사용해 주시기 바랍니다.**


<img src="https://github.com/RobomationLAB/Beagle_with_ROS2_SLAM/assets/160319639/af323c65-33cf-40b1-8743-d83e9dfc82bd" alt="대체 텍스트" width=500>

---



*※해당 프로그램은 로보메이션의 제품을 활용해 대학생들이 개발하여 체험용으로 배포한 프로그램입니다.
<br>
따라서 <u>본 프로그램의 사용법이나 오류에 대한 문의는 받고 있지 않습니다.</u>*

---

<br><br><br><br>

 
# PC 연결

Beagle의 전원이 꺼져 있는 상태에서 **EXPRESS RECEIVER**를 PC의 USB단자에 꽂습니다.
<br>
**EXPRESS RECEIVER**의 연결 상태 표시등이 초록색으로 깜빡이면 연결 대기중인 상태로 정상입니다.



<img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/e6f30006-f092-4e51-af49-13063e7f1f77" alt="대체 텍스트" width=500>

<br><br>

Beagle로봇을 EXPRESS RECEIVER에 가까이 가져가 Beagle의 **전원 버튼**을 눌러 전원을 켭니다.
<br>
Beagle에서 **삑** 소리가 나고 **Beagle의 통신 상태 표시등**과 **EXPRESS RECEIVER의 연결상태 표시등**이 계속 켜져있거나 빠르게 깜빡이면 정상입니다.

<img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/d013081b-4ba2-492f-a9ba-0a2ff76b02b6" width=350>


---



<br><br>



# BEAGLE with ROS2 SLAM 시작하기

- 다운로드 파일의 **Beagle ros2 manual.pdf** 설명서를 참조하여 설치 및 사용을 진행하세요.
- SLAM 시연 동영상을 참조하세요.

    <img src="https://github.com/RobomationLAB/Beagle_with_ROS2_SLAM/assets/93518556/02b56522-cef7-40d1-8f56-e08434d812af" width = 800>

<br><br>
- ROS2 Humble의 설치는 https://github.com/RobomationLAB/Beagle_ROS2_Humble 을 참조하세요.<br>
 <img src="https://github.com/RobomationLAB/Beagle_with_ROS2_SLAM/assets/93518556/3e482bfc-7bb2-4f1f-9675-1ca67d6bdc1b" width = 300>

<br><br>
