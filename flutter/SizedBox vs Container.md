# SizedBox vs Container

## SizedBox

- 고정된 사이즈의 위젯을 만들 때 사용
- 고정된 사이즈의 위젯으로 Row 또는 Column내에서 간격을 주고 싶을 때도 사용
- width, height 둘 중 하나라도 설정하지 않으면 child 크기에 맞게 설정됨

## Container

- SizedBox처럼 고정된 크기를 가진 위젯을 만들 수 있을 뿐만 아니라 padding, margin, color 등 부가적인 효과도 넣을 수 있음.
- 위 이유로 사이즈만 고정시키고 싶은 경우 SizedBox를 사용해야함. 크기만 고정하는데 Container를 사용할 경우 린트가 표시되면서 SizedBox를 사용하라고 권장됨.
- width, height를 넣지 않으면 child 위젯의 크기를 최대로 확장해줌

## 차이점

width & height가 설정되지 않은 경우

- SizedBox의 경우 child 위젯의 크기를 child위젯에 맞춤
- Container의 경우 child 위젯의 크기를 최대로 확장

## 결론

SizedBox와 Container는 각각의 장점이 있으며, 상황에 맞게 적절한 위젯을 선택하는 것이 중요하다. 간단히 공간을 만들거나 크기를 조정할 때는 SizedBox를, 스타일링이나 복잡한 레이아웃이 필요할 때는 Container를 사용하는 것이 좋다.
