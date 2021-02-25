# The_end_of_python_ml
~~~python3
"마지막_머신러닝_정리"
~~~
[머신러닝 적용]<img src="https://scikit-learn.org/stable/_static/ml_map.png" width="80%" height="50%"></img>

1. Pandas/ Numpy
> ** Data Handling **
>> [Numpy](https://github.com/DominKim/The_end_of_python_ml/blob/main/1.numpy_pandas/numpy_for_machine_learning.ipynb)
>> [Pandas](https://github.com/DominKim/The_end_of_python_ml/blob/main/1.numpy_pandas/pandas_for_machine_learning.ipynb)
>
2. Classification
> ** Classification **
> - Logit Transform : odd를 구하고, log를 취한 것
> - LogisticRegression B1(가중치) 해석 : x가 한단위 증가 했을 때 log(odds)의 증가량
>> [Evaluatino(평가)](https://github.com/DominKim/The_end_of_python_ml/blob/main/2.Evaluation/Evaluation.ipynb)
>> [Classification](https://github.com/DominKim/The_end_of_python_ml/blob/main/3.Classification/Classification.ipynb)
>> [Ensemble](https://github.com/DominKim/The_end_of_python_ml/blob/main/3.Classification/Ensemble.ipynb)
>> [stacking_mode](https://github.com/DominKim/The_end_of_python_ml/blob/main/3.Classification/stacking_model.ipynb)
>
3. Regression
> ** Regression **
> - 회귀에서 선형 회귀 / 비선형 회귀를 나누는 기준은 회귀 계수가 선형 / 비선형인지에 따른 것이지 독립변수의 선형 / 비선형 여부와는 무관
>  - 편향 - 분산 트레이드오프(Bias-Variance Trade off)
  >  - 고편향성 : 지나치게 한 방향성으로 치우진 것
  >  - 고분산 : 지나치게 높은 변동성을 가진 것
>> [Regression](https://github.com/DominKim/The_end_of_python_ml/blob/main/4.Regression/Linear_Regression.ipynb)
>
4. Dimension_Reduction
> ** Dimension_Reduction **
>> [PCA](https://github.com/DominKim/The_end_of_python_ml/blob/main/5_Dimension_Reduction/PCA.ipynb)
>
> - PCA : 입력 데이터의 변동성이 가장 큰 축을 구하고, 다시 이 축에 직각인 축을 반복적을 축소하려는 차원 개수만큼 구한 뒤 입력 데이터를 이 축들에 투영해 차원을 축소하는 방식
> - LDA : 입력 데이터의 결정 값 클래스를 최대한을 분리할 수 있는 축을 찾음
