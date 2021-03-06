# Quant-Analysis

## TOM/ROM Effect 분석

### **월말 월초효과(Turn of the Month Effect, TOM)** 

월말과 월초 기간에 유의적인 초과수익이 발생하는 현상이며, 월초와 월말에 발생하는 금융계의 이상 현상중 하나임
> 이러한 월말 / 월초 효과의 원인과 관련 factor를 통계적 검정과 머신러닝으로 분석

![image](https://user-images.githubusercontent.com/62705839/114147038-3f674580-9953-11eb-9321-b1072957ae5d.png)

- TOM기간을 1, ROM 기간을 0으로 라벨링 후 간단한 트리 분류 모델 설계
> 그 결과 기간 자금 해지액, 단기 자금 해지액이 월말 월초에 유의한 factor로 나옴

- 하지만 KOSPI와 KPI200 수익률에는 TOM 효과가 두드러지지 않았음.
- 또한 backtesting 결과도 유의하지 않았으므로, 최근에는 TOM 전략이 무의미하다는 결론을 얻음. 
