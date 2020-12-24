# AML Assignment 1
## Explainable AI
#### 1. LRP
##### -- LRP는 각 layer별로 output score(relevance score)에 얼마나 영향을 끼쳤는지 분석하는 explainable 기법이다.
##### -- 방법으론 최종단에 나온 relevance score (대표적으로 probability ) 를 모델의 input 방향으로 backword시키면서 각 layer에 relevance score를 재분배 한다.
##### -- 따라서 전제조건이 relevance score를 분배한 후 모든 layer들의 relevance score의 합은 기존 output의 relevance score와 같아야 한다.

#### 2. Grad-CAM
##### -- 
#### 3. LIME
