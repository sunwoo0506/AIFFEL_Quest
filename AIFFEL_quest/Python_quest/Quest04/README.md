## AIFFEL Campus Online Code Peer Review Templete
- 코더 : 오선우
- 리뷰어 : 서승호


## PRT(Peer Review Template)
[x] **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
- 입력값을 받는 부분이 없습니다. comprehension, generator는 잘 작동합니다.

```
 
  # 물고기 리스트 생성
fish_list = [
    {"이름": "Nemo", "speed": 3},
    {"이름": "Dory", "speed": 5},
]

# 컴프리헨션 함수: 물고기의 움직임을 출력
def show_fish_movement_comprehension(fish_list):
    # 각 물고기의 정보를 가져와 출력
    [print(f"{fish['이름']} is swimming at {fish['speed']} m/s") for fish in fish_list]

# 제너레이터 함수: 물고기의 움직임을 생성하고 출력
def show_fish_movement_generator(fish_list):
    # 각 물고기의 정보를 가져와 값 생성
    for fish in fish_list:
        # 값 생성 및 반환
        yield f"{fish['이름']} is swimming at {fish['speed']} m/s"


print("Using Comprehension:")
show_fish_movement_comprehension(fish_list)

print("Using Generator:")
generator = show_fish_movement_generator(fish_list)
# 제너레이터를 통해 물고기의 움직임을 가져와 출력
for move in generator:
    print(move)

```
[o] **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
- 주석 작성이 잘 되어있습니다.
        
[o]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
        
[o]  **4. 회고를 잘 작성했나요?**
- 회고를 잘 작성하였습니다.
        
[o]  **5. 코드가 간결하고 효율적인가요?**
- 간결하고 효율적으로 작성되었습니다.

## 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
