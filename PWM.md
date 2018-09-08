# PWM
STM32F0 MCU의 timer를 사용하여 PWM신호를 출력하고 duty ratio, resolution, 그리고 frequency를 제어한다.

#### 1. PWM 출력을 원하는 핀을 클릭한 후 `TIM1_CH2`를 선택한다.
* `TIM1_CH2`는 "타이머 1, 채널 2"를 의미한다. 아직 timer1이 활성화 되지 않았기 때문에 핀이 노란색이다.

![](images/pwm-010.PNG)

#### 2. Timer 1 Channel 2를 활성화 시키고 PWM모드로 설정한다.

![](images/pwm-020.PNG)

#### 3. 타이머 상세 설정
Configuration 탭에 "TIM1" 버튼을 누르면 아래 타이머 상세 설정 창이 뜬다.

![](images/pwm-030.PNG)

