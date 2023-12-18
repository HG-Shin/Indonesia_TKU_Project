# 2023 HBNU TKU Global Engineering Project 9기

| | NAME | MAJOR |
| - | - | - |
| HBNU | Heegwan Shin | Computer Engineering |
| HBNU | Jieun Min | Chemical Engineering |
| HNU | Hogyun Lim | Chemical Engineering |
<br/>

## 📜 서비스 내용
인도네시아 텔콤 대학교에 방문하여 현지 학생들과 함께 진행한 프로젝트로, 차(Tea)의 품질을 신속하고 객관적으로 확인하기 위한 주제입니다.  
아두이노와 다양한 센서들을 활용하여 수집한 데이터와 전문가의 평가 데이터를 결합하였습니다.  
프로젝트 주제를 보다 잘 이해하기 위해 반둥 지역의 차 생산 공장을 방문하여 전 과정을 확인하였습니다.  
수집한 데이터는 다양한 머신러닝 기법을 활용하여 분석되어 99%의 정확도를 달성하였습니다.
<br/><br/>

## 💻 Tech Stack
<div align="left">
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
<img src="https://img.shields.io/badge/machinelearning-3776AB?style=for-the-badge&logo=machinelearning&logoColor=white">
</div><br/>

## 💡 성장 경험
### 글로벌 역량 함양
앞서 진행한 치앙마이 대학교 및 텔콤 대학교 학생들과 협업을 진행하며 그들의 문화를 이해하고 영어를 사용해 의사소통하는 경험을 얻었습니다. 서로 부족한 부분은 알려주고 때로는 배우기도 하며 지식을 공유할 수 있었던 점이 많은 도움이 되었습니다.

### 머신러닝의 실무 프로젝트 적용
머신러닝 관련 과목을 들으며 A+ 라는 좋은 성적을 얻긴 했지만 제 실력이 아직 부족하다고 느꼈었습니다. 하지만 해당 실무 프로젝트를 진행하며 개념을 다시 한번 정리할 수 있었고 배웠던 기술을 사용하고 응용하며 문제를 해결할 수 있었습니다. 
<br/><br/>

## Project Background
<img width="541" alt="image" src="https://github.com/HG-Shin/Indonesia_TKU_Project/assets/124351914/433a95d7-5edc-4afd-8508-bbc086fd7dfc">
  <div>
    In response to the subjective and inconsistent methods of tea quality assessment, we introduce the concept of an "Artificial Nose."  
    This innovative approach combines machine learning and specialized hardware to evaluate tea quality based solely on its aroma.
  </div>

## Solution
- Through the integration of machine learning, we combine various machine learning methods in our approach.
- The machine learning approach enables the hardware to process sensor data with the goal of identifying and isolating the authentic aroma originating from tea.
- for imbalance data this is out of our control, depending on tea plantation manufacturer

## Gas Sensor
| Sensor | Sensitivity |
| - | - |
| MQ3 | Alcohol vapors |
| TGS882 | such as Hydrogen(H2), Methane(CH4), Carbone monoxide(CO) |
| TGS2602 | Ammonia(NH3) and Organic compounds |
| MQ5 | LPG, Methane(CH4), Alcohol |
| MQ138 | Ammonia(NH3) |
| TGS2620 | Hydrogen(H2), Methane(CH4), Propane(C3H8) |

## Algorithm Comparison Table
| Name Algorithm | accuracy |
| - | - |
| KNeighbors | 0.99 (99%) |
| RandomForest | 0.99 (99%) |
| XGboost	| 0.91 (91%) |
| Neural Network | 0.89 (89%) |
| Decision Tree	| 0.75 (75%) |
| Logistic Regression	| 0.73 (73%) |
| Support Vector Machine	| 0.73 (73%) |

## Completion
<img width="396" alt="image" src="https://github.com/HG-Shin/Indonesia_TKU_Project/assets/124351914/e791690a-6ac4-4c0b-9f93-959519a4d530">
<div>
In the end, the goal of this solution is to address consumer complaints and enhance overall <br/>
satisfaction by maintaining consistent and objectively measured product quality.
</div>
