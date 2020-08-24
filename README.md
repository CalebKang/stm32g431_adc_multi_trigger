# stm32g431_adc_multi_trigger

1. CubeMX에서 TIM1 Channel5를 PWM Generation No Output으로 하나 더 설정.

2. TIMx_CR2의 MMS2의 값을 원하시는 대로 변경합니다.
   Multiple Trigger는 1010 ~ 1111까지 변경이 가능하며 해당 설정에 따라 엣지 방향이 설정됨. 
   즉, 세개(4,5,6)의 채널을 설정하되 실제로 Trigger사용되는 채널은 설정에 따라 바뀌게 됩니다.
   
   
