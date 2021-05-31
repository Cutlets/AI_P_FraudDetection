# Hongik Univ. AI 2021-1 Project 01
  Credit Card Fraud Detection with DNN Algorithm.


1_1 : 제출본
1_1(2) : 테스트 데이터셋 오류를 수정했습니다.....

# Undersamping the test data
df_xt_s, df_yt_s = RandomUnderSampler(random_state=0).fit_resample(df_x, df_y)

=>

# Undersamping the test data
df_xt_s, df_yt_s = RandomUnderSampler(random_state=0).fit_resample(df_xt, df_yt)


새로운 결과입니다.
Epoch 1/3
3184/3184 [==============================] - 9s 2ms/step - loss: 0.1790 - accuracy: 0.9283 - Precision: 0.8198 - Recall: 0.9606
Epoch 2/3
3184/3184 [==============================] - 7s 2ms/step - loss: 0.0243 - accuracy: 0.9946 - Precision: 0.9652 - Recall: 0.9902
Epoch 3/3
3184/3184 [==============================] - 7s 2ms/step - loss: 0.0186 - accuracy: 0.9963 - Precision: 0.9776 - Recall: 0.9940
Model Evaluation
202/202 [==============================] - 1s 1ms/step - loss: 1.4678 - accuracy: 0.9158 - Precision: 0.9818 - Recall: 0.9953
== <Results> ==
 Accuracy  91.58415794372559 %

Precision 	 0.9818211793899536 

Recall 		 0.9953023791313171 

f1-score 	 0.9885158178573424 

===============
