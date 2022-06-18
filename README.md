 RL Homework5
Freeway遊戲共有3個版本：v0、v4及 v5，v0、v4的Action Space比較少 v5的Action Space有18種(必須在初始化環境時設定參數full_action_space=True)，預設情況下此環境返回顯示給玩家的是RGB圖像作為observation。

遊戲目標
此款遊戲的目標是讓在最下方的雞群穿過繁忙的高峰時段交通的車道，在穿過所有車道到達最上方後即可獲得1分。

Reward
讓雞穿過所有車道到達最上方後即可獲得1分。

Action Space
有18種(必須在初始化環境時設定參數full_action_space=True)

程式概分為9大部份：
1.	Setup Environment環境設定
    1.1	Setup virtual display設定虛擬環境顯示
    1.2	Import the necessary code libraries
    1.3	使用video recording
2.	Create the Deep Q-Network class
3.	Create the policy
4.	Create the replay buffer設定記憶回放buffer
5.	Create the environment建立及初始化遊戲環境後再隨機選擇一個action與環境交互
6.	Create the test/sampling function測試環境建立結果
7.	reate the Deep Q-Learning algorithm建立Deep Q-Learning algorithm
8.	Train the policy進行policy訓練
9.	Check the resulting policy結果顯示
