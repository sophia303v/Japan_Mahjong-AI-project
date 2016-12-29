Agent
--------------------------------------
* SimpleDefense Agent:  
    把前8張被丟出但沒被吃,碰,槓的牌當作安全牌  
    計算所有牌被吃,碰,槓的機率  
    安全牌會隨回合而變,但是機率不變,因此若存在機率很小的牌應該優先保存,  
    先打安全牌中機率較大的牌  
    另外,這個agent並不宣告吃,碰,槓  

* Random Agent:  
   隨機丟出手中的任何一張牌  

Update History :
--------------------------------------
v.1.3 (2016.12.24)
--------------------------------------

1. 新增SimpleDefense agent 

v.1.2 (2016.12.17)
--------------------------------------

1. 新增計算胡牌牌型分數的方法

2. 新增門風概念

3. 有簡單的UI可以給AI使用

v.1.1 (2016.12.11)
--------------------------------------

1. agent胡牌或自摸時會回傳牌型

2. 可計算向聽數

3. 利用向聽數實作OneStepAgent

[向聽數計算程式](https://github.com/chrinide/mahjong)

v.1.0 (2016.12.7 )
--------------------------------------

1. 麻將桌初步實作完成

2. 只有random action的agent

3. 吃碰槓為程式決定  不能選擇是否要吃碰槓

4. 不能宣告聽牌
