# **"빅데이터를 활용한 중소형 외감기업 부실 예측 및 부실 지수 제언"**
<br>


# **프로젝트 개요**
- 외감기업을 상장기업, 비상장기업으로 나누어 부실예측 모형을 만든다.
  - 전통적 통계기법, 머신러닝, 딥러닝을 다양하게 활용하여 모델링을 수행한다.
  - 사용한 분석 기법
    : Naive Bayes, Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost, SVM, DNN, TabNet, Stacking
- 도출된 Feature 들을 바탕으로 사전적인 부실 지수를 산출한다.



# **목적**
- 상장기업의 부실 예측 및 등급화를 통해 주주들에게 기업에 대한 정보를 제공하고자 한다.
  - 기존에 제공되는 기업 등급들은 기업들의 채권 상환능력을 평가한 등급이기 때문에 주식 투자자들이 얻을 수 있는 기업 정보를 제공한다.
- 비상장 외감기업의 부실 예측 및 등급화를 통해 기업에게 투자를 진행하려고 하는 투자자들과 은행에게 기업 부실에 대한 위험도를 알린다.
  - 많은 은행들의 주 고객이지만, 상대적으로 분석이 많이 이루어지지 않고 있는 비상장 기업에 대한 분석을 통해 새로운 분석 시각을 제공한다.
- 기존의 기업 신용평가 등급은 신용 사건이 발생했을 때 주로 갱신되는 사후적 확률이므로, 본 분석을 통해 투자자에게 사전적인 정보를 제공하고자 한다.
  - 부실 발생 직전 년도를 Target 으로 설정하여 최초 시점의 부실을 예측하는 모델로, 사전적인 부실 탐지 모형이다.



---
# **PPT**
![image](https://github.com/shoni0325/Project_2/assets/129731878/cd537d0c-9567-45f1-a441-64cca06ce719)
![image](https://github.com/shoni0325/Project_2/assets/129731878/e04c2d91-8924-43ba-b218-c11e16ed138c)
![image](https://github.com/shoni0325/Project_2/assets/129731878/c6bc6a54-bbf2-4aa5-8aa4-c87f7e0fcfda)
![image](https://github.com/shoni0325/Project_2/assets/129731878/dc557cc1-26f1-4a79-bd96-11a3231de805)
![image](https://github.com/shoni0325/Project_2/assets/129731878/e61f87f8-b2fc-480b-ab6a-4f68f0071c5f)
![image](https://github.com/shoni0325/Project_2/assets/129731878/6a23b80f-7208-4266-9481-74e146977f03)
![image](https://github.com/shoni0325/Project_2/assets/129731878/949fb141-6e44-41d5-ad37-f55e94f07924)
![image](https://github.com/shoni0325/Project_2/assets/129731878/e1376851-af73-46e9-a83a-216710147f0e)
![image](https://github.com/shoni0325/Project_2/assets/129731878/97c1bba2-8532-4038-aea5-9554fabc333e)
![image](https://github.com/shoni0325/Project_2/assets/129731878/b715ac6b-2979-436b-b8c4-5556b58c7187)
![image](https://github.com/shoni0325/Project_2/assets/129731878/986f9eeb-dfa9-4fa1-9397-ad40100e905e)
![image](https://github.com/shoni0325/Project_2/assets/129731878/851cd689-4ff1-4a4b-9997-51644f8512d4)
![image](https://github.com/shoni0325/Project_2/assets/129731878/82398d7b-2fe1-48ef-9181-50bdeecf7ac6)
![image](https://github.com/shoni0325/Project_2/assets/129731878/1f279cf9-a512-4af5-826c-0a6879854a21)
![image](https://github.com/shoni0325/Project_2/assets/129731878/f90a6c8f-e58f-409e-8831-1735e0440c6e)
![image](https://github.com/shoni0325/Project_2/assets/129731878/0c143ec2-2e8f-44bc-be3f-cfdb6cf9b775)
![image](https://github.com/shoni0325/Project_2/assets/129731878/bb4e379e-f6c5-4a01-ac48-1eb3f12c894b)
![image](https://github.com/shoni0325/Project_2/assets/129731878/e0cbdd5c-ca66-4513-8bad-187533bfd253)
![image](https://github.com/shoni0325/Project_2/assets/129731878/a154b224-21b6-43cf-a28a-32f2a2703797)
![image](https://github.com/shoni0325/Project_2/assets/129731878/cf89c1a6-8bb1-4f0b-9516-07f6c6a9d529)
![image](https://github.com/shoni0325/Project_2/assets/129731878/64dd44b8-cbc2-4aac-9b5d-db22a231f19b)
![image](https://github.com/shoni0325/Project_2/assets/129731878/8294c730-cc2a-48a6-96cd-b144767e4492)
![image](https://github.com/shoni0325/Project_2/assets/129731878/48e416c9-5f5d-4c83-8e8d-973a5b4c192c)
![image](https://github.com/shoni0325/Project_2/assets/129731878/d4094d92-52a9-4c95-b9c5-f97d9de55676)
![image](https://github.com/shoni0325/Project_2/assets/129731878/97f16d04-ecdb-4340-94d7-d60278bd819a)
![image](https://github.com/shoni0325/Project_2/assets/129731878/4c0cb898-96f1-46be-973a-36236490c301)
![image](https://github.com/shoni0325/Project_2/assets/129731878/a9d081c2-b907-42ed-99be-046d49447731)
![image](https://github.com/shoni0325/Project_2/assets/129731878/65a113ca-05a5-48f0-b194-49338a8e7d8b)
![image](https://github.com/shoni0325/Project_2/assets/129731878/7cde1faf-6e30-4dc4-81e8-a09de928af58)
![image](https://github.com/shoni0325/Project_2/assets/129731878/6b6146fd-bdc6-4de0-b055-3a7ce4672605)
![image](https://github.com/shoni0325/Project_2/assets/129731878/866af5fa-f889-4090-963e-fa907edc1470)
![image](https://github.com/shoni0325/Project_2/assets/129731878/0416e770-6a46-4c6d-9028-0174dad7779e)
![image](https://github.com/shoni0325/Project_2/assets/129731878/299a2cee-ee2d-452f-a0cd-ee5626251623)
![image](https://github.com/shoni0325/Project_2/assets/129731878/1e847a6c-5ebf-4ef0-9223-6998aab001ec)
![image](https://github.com/shoni0325/Project_2/assets/129731878/9d629447-750a-403d-ab12-bf07418c0caf)
![image](https://github.com/shoni0325/Project_2/assets/129731878/9ff268f6-5657-45d9-a005-f07d6236688c)
![image](https://github.com/shoni0325/Project_2/assets/129731878/b4b07997-dbb7-477d-a1a8-8caa8cf0ceac)
![image](https://github.com/shoni0325/Project_2/assets/129731878/b5ad2998-a697-4fd0-8061-6a4c567658bb)
![image](https://github.com/shoni0325/Project_2/assets/129731878/207b89fc-37f0-402a-9126-317421f0e6e8)
![image](https://github.com/shoni0325/Project_2/assets/129731878/1999c66d-14c5-4d2d-b85b-98da1730aa56)
![image](https://github.com/shoni0325/Project_2/assets/129731878/642db376-2358-44cd-b3c0-f93e812e1f72)
![image](https://github.com/shoni0325/Project_2/assets/129731878/f2672410-9c71-4425-9302-529b7c619a91)
![image](https://github.com/shoni0325/Project_2/assets/129731878/ca504dcf-fc09-4ad9-a7e3-84e1fd67c3ce)
![image](https://github.com/shoni0325/Project_2/assets/129731878/b162ad0d-b470-492c-9596-df85a1775146)
![image](https://github.com/shoni0325/Project_2/assets/129731878/ca4ffbb2-ee42-489e-8866-0d0c0ac76c4a)
![image](https://github.com/shoni0325/Project_2/assets/129731878/6324b5d7-5243-490b-b8f1-2cc2d3f4c452)
![image](https://github.com/shoni0325/Project_2/assets/129731878/0c70eef7-a499-4b15-b0ef-fed92e987585)
![image](https://github.com/shoni0325/Project_2/assets/129731878/3b0d9e95-d044-4bb1-9e87-621974ff7b17)
![image](https://github.com/shoni0325/Project_2/assets/129731878/cc599c80-ac2b-4bd8-a24d-c5aeb6267e49)
![image](https://github.com/shoni0325/Project_2/assets/129731878/bf2999fa-e06f-40d0-ae86-505bbbdee39f)
![image](https://github.com/shoni0325/Project_2/assets/129731878/79f9cfec-6efe-4460-b3a0-6691cf5b8611)
![image](https://github.com/shoni0325/Project_2/assets/129731878/6be37a4b-616e-4512-a337-c72311511eb0)
![image](https://github.com/shoni0325/Project_2/assets/129731878/1b5074c3-c32c-4369-9897-e2f3745e9d71)
![image](https://github.com/shoni0325/Project_2/assets/129731878/40ce8175-3a38-4b46-9a82-23d010c87e23)
![image](https://github.com/shoni0325/Project_2/assets/129731878/5b1b6c79-24f1-4acc-8b12-031b551f9daa)
![image](https://github.com/shoni0325/Project_2/assets/129731878/8d1c899d-3bf6-464c-bd4b-d7ee8fa1908c)
![image](https://github.com/shoni0325/Project_2/assets/129731878/75e81efa-30ca-454b-b3b3-00fd595fc963)
![image](https://github.com/shoni0325/Project_2/assets/129731878/799e8b1c-6d98-4262-96a0-0cebb6e512e6)
