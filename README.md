n = int(input())  # 讀取隊伍數量

count = 0  # 初始化為0，用來記錄隊伍的數量

for _ in range(n):  # 迴圈每個隊伍

    team_size = int(input())  # 隊伍人數
    
    if team_size % 3 == 0 and team_size != 0:  # 隊伍人數是否是3的倍數且不為0
    
        count += 1  # 如果是可以的隊伍，計數器加一

print(count)  # 印出符合標準的隊伍總數
