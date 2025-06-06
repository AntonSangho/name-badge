# 회로 연결하기

## 얼마나 걸릴까요?
- 준비하고 연결하는데 약 5분 정도 걸려요

## 필요한 것들
- 마이크로비트 v2
- AAA 배터리 2개
- AAA 배터리 케이스 (마이크로비트에 연결되는 것)

## 어떻게 연결하나요?

이 프로젝트는 매우 간단한 회로를 가지고 있어요. 마이크로비트와 배터리만 연결하면 됩니다.

### 기본 연결하기

1. AAA 배터리 2개를 배터리 케이스에 넣어요. (+)와 (-) 방향이 올바른지 확인하세요.
2. 배터리 케이스의 커넥터를 마이크로비트 하단의 배터리 커넥터에 연결해요.

![기본 연결 그림](/img/keyring-connection.jpg)

### 연결 확인하기

1. 배터리를 연결하면 마이크로비트의 LED가 켜지고 프로그램이 실행되는지 확인해요.
2. 화면에 "Amari" 또는 여러분이 설정한 메시지가 스크롤되어 표시되는지 확인해요.

## 배터리 케이스 위치 조정하기

키링 케이스를 만들 때 배터리 케이스의 위치를 고려해야 합니다:

1. **옆면 부착**: 배터리 케이스를 마이크로비트 옆에 놓으면 키링이 넓어지지만 얇아집니다.
2. **뒷면 부착**: 배터리 케이스를 마이크로비트 뒤에 놓으면 키링이 두꺼워지지만 컴팩트해집니다.

![배터리 위치 옵션](/img/battery-position-options.jpg)

## 배터리 절약 팁

키링은 항상 켜져 있기 때문에 배터리가 빨리 소모될 수 있습니다. 배터리 수명을 연장하는 방법들:

1. **LED 밝기 줄이기**: 코드에 `led.setBrightness(100)` 명령을 추가하여 밝기를 낮춰보세요 (기본값 255).
2. **사용하지 않을 때 배터리 분리하기**: 간단한 분리/연결 구조를 케이스에 추가하는 것을 고려해보세요.
3. **절전 모드 추가하기**: 일정 시간 후 LED가 꺼지고 버튼을 누르면 다시 켜지도록 코드를 수정해보세요.

## 문제가 생겼어요!

- **마이크로비트가 켜지지 않아요**: 
  - 배터리가 올바르게 삽입되었는지 확인하세요.
  - 배터리가 충분히 충전되었는지 확인하세요.
  - 배터리 커넥터가 마이크로비트에 제대로 연결되었는지 확인하세요.

- **배터리 케이스가 분리돼요**: 
  - 케이스 안에 배터리 케이스를 더 단단히 고정하세요.
  - 필요하다면 배터리 케이스에 작은 고리를 달아 케이스에 묶을 수 있어요.

- **케이블이 불편해요**: 
  - 배터리 케이스와 마이크로비트 사이의 케이블을 케이스 내부에 깔끔하게 정리하세요.
  - 케이블이 너무 길다면 접어서 케이스 안에 숨기세요.

## 알아두면 좋은 점

- 마이크로비트 v2는 표준 AAA 배터리 2개로 작동합니다 (총 3V).
- 배터리 수명은 LED 밝기, 메시지 길이, 사용 빈도에 따라 달라집니다.
- 일반적으로 AAA 배터리로 지속적인 사용 시 약 5-7일 정도 사용할 수 있어요.
- USB 케이블로 컴퓨터에 연결하면 배터리 없이도 작동합니다.