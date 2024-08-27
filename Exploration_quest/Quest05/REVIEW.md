## AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김기홍, 김소영, 김동규, 정권영
- 리뷰어 : 김원영, 김주현, 유제민


## PRT(Peer Review Template)
[X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
- LMS 환경에서 정상적으로 동작하는 코드를 로컬이나 코랩 환경에서도 동작할 수 있도록 여러 측면에서 노력하였으나 차원 불일치 이슈가 해결이 쉽지 않아 끝내 완성하지는 못했습니다. 
- 하지만, 계속해서 발생하는 여러 오류를 마지막까지 해결하기 위해 많은 노력을 기울였음을 피어 리뷰 과정에서 잘 이해할 수 있었습니다. 
    
[O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
- 네. 필요한 부분마다 주석이 잘 기록되어 있습니다. 

[O]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
- 실제 인코딩 결과와 예측 결과를 비교하기 위해 직접 인코딩 결과 배열을 직접 출력해보면서 테스트함. 
```python
sample_input = questions[0:1]
sample_output = answers[0:1]
predictions = model.predict([sample_input, sample_output[:, :-1]])
print("Predictions:", predictions)
print("Actual Output:", sample_output[:, 1:])
```
        
[O]  **4. 회고를 잘 작성했나요?**
- 네. 프로젝트를 진행하면서 어려웠던 부분, 해결하기 위한 다양한 시도와 그로 인해 배운 점까지 잘 작성되어 있습니다. 
        
[O]  **5. 코드가 간결하고 효율적인가요?**
- 네. 전체 코드가 중복 없이 간결하게 작성되어 있습니다. 

## 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```