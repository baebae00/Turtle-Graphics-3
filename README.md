# Turtle-Graphics-3
### turtle makes some of the triangles that shape like conch

```python
import turtle
t=turtle.Turtle()
t.shape('turtle')

length=30

for i in range(8) : #for 구문은 반복문이다 for문 안의 내용을 8번 반복하겠다는 의미
  t.forward(length)
  t.left(90)
  t.forward(length)
  t.left(135)
  t.forward(length*(2**(1/2))) #위에서 선언한 length=30을 이용한다, *는 곱셈, 2**(1/2)는 2의 2분의1을 제곱하겠다는 의미
  t.left(135)
  length*=2**(1/2) #length=length*(2**(1/2))와 동일하다 단지 =을 기준으로 length가 반복되니 이를 생략하는 방법일 뿐
  t.left(45)
```
