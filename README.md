# pytorch_base

딥러닝에 대해서 관심이 생겨서 탐구해보려고 합니다

아주 기초부터 공부한다기보다는 직접 파이토치를 써보면서 얕고 넓게 공부한 뒤에
빈칸 채우기 식으로 공부할 예정입니다.

## base1 역전파 (손실함수,연쇄법칙)

기본적인 딥러닝의 flow를 보여주는 미분.

1) requires_grad

기본적으로 false이므로 바꾸려면 True값으로 써줘야한다.

@ 최적화란 손실함수 기준으로 각 변수마다 미분을 하는 것

#d(res)/dx_i = x_i + 1
# res = (z_1 + .. +z_4)/4
# z_i = 2 y_i **2
# z_i = 2(x_i+1)**2

2) backward 
연쇄법칙 (후에 더 채워 넣을 예정)

3) .grad

미분값을 확인하고 싶을 때 사용

