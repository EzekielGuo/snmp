# snmp
将snmp信息转化为端口名与状态的对应关系


效果如下：
[{'id': 1, 'port': 'GigabitEthernet1/0/1', 'status': 'down'}, {'id': 2, 'port': 'GigabitEthernet1/0/2', 'status': 'down'}, {'id': 3, 'port': 'GigabitEthernet1/0/3', 'status': 'up'}, {'id': 4, 'port': 'GigabitEthernet1/0/4', 'status': 'down'}, {'id': 5, 'port': 'GigabitEthernet1/0/5', 'status': 'down'}, {'id': 6, 'port': 'GigabitEthernet1/0/6', 'status': 'down'}, {'id': 7, 'port': 'GigabitEthernet1/0/7', 'status': 'down'}, {'id': 8, 'port': 'GigabitEthernet1/0/8', 'status': 'down'}, {'id': 9, 'port': 'GigabitEthernet1/0/9', 'status': 'down'}, {'id': 10, 'port': 'GigabitEthernet1/0/10', 'status': 'down'}, {'id': 11, 'port': 'GigabitEthernet1/0/11', 'status': 'down'}, {'id': 12, 'port': 'GigabitEthernet1/0/12', 'status': 'down'}, {'id': 13, 'port': 'GigabitEthernet1/0/13', 'status': 'down'}, {'id': 14, 'port': 'GigabitEthernet1/0/14', 'status': 'down'}, {'id': 15, 'port': 'GigabitEthernet1/0/15', 'status': 'down'}, {'id': 16, 'port': 'GigabitEthernet1/0/16', 'status': 'down'}, {'id': 17, 'port': 'GigabitEthernet1/0/17', 'status': 'down'}, {'id': 18, 'port': 'GigabitEthernet1/0/18', 'status': 'down'}, {'id': 19, 'port': 'GigabitEthernet1/0/19', 'status': 'down'}, {'id': 20, 'port': 'GigabitEthernet1/0/20', 'status': 'down'}, {'id': 21, 'port': 'GigabitEthernet1/0/21', 'status': 'down'}, {'id': 22, 'port': 'GigabitEthernet1/0/22', 'status': 'down'}, {'id': 23, 'port': 'GigabitEthernet1/0/23', 'status': 'down'}, {'id': 24, 'port': 'GigabitEthernet1/0/24', 'status': 'down'}, {'id': 25, 'port': 'GigabitEthernet1/0/25', 'status': 'down'}, {'id': 26, 'port': 'GigabitEthernet1/0/26', 'status': 'down'}, {'id': 27, 'port': 'GigabitEthernet1/0/27', 'status': 'down'}, {'id': 28, 'port': 'GigabitEthernet1/0/28', 'status': 'down'}, {'id': 29, 'port': 'GigabitEthernet1/0/29', 'status': 'down'}, {'id': 30, 'port': 'GigabitEthernet1/0/30', 'status': 'down'}, {'id': 31, 'port': 'GigabitEthernet1/0/31', 'status': 'down'}, {'id': 32, 'port': 'GigabitEthernet1/0/32', 'status': 'down'}, {'id': 33, 'port': 'GigabitEthernet1/0/33', 'status': 'down'}, {'id': 34, 'port': 'GigabitEthernet1/0/34', 'status': 'down'}, {'id': 35, 'port': 'GigabitEthernet1/0/35', 'status': 'down'}, {'id': 36, 'port': 'GigabitEthernet1/0/36', 'status': 'down'}, {'id': 37, 'port': 'GigabitEthernet1/0/37', 'status': 'down'}, {'id': 38, 'port': 'GigabitEthernet1/0/38', 'status': 'down'}, {'id': 39, 'port': 'GigabitEthernet1/0/39', 'status': 'down'}, {'id': 40, 'port': 'GigabitEthernet1/0/40', 'status': 'down'}, {'id': 41, 'port': 'GigabitEthernet1/0/41', 'status': 'down'}, {'id': 42, 'port': 'GigabitEthernet1/0/42', 'status': 'up'}, {'id': 43, 'port': 'GigabitEthernet1/0/43', 'status': 'up'}, {'id': 44, 'port': 'GigabitEthernet1/0/44', 'status': 'up'}, {'id': 45, 'port': 'GigabitEthernet1/0/45', 'status': 'up'}, {'id': 46, 'port': 'GigabitEthernet1/0/46', 'status': 'up'}, {'id': 47, 'port': 'GigabitEthernet1/0/47', 'status': 'up'}, {'id': 48, 'port': 'GigabitEthernet1/0/48', 'status': 'down'}, {'id': 49, 'port': 'GigabitEthernet1/0/49', 'status': 'down'}, {'id': 50, 'port': 'GigabitEthernet1/0/50', 'status': 'down'}, {'id': 51, 'port': 'GigabitEthernet1/0/51', 'status': 'down'}, {'id': 52, 'port': 'GigabitEthernet1/0/52', 'status': 'down'}, {'id': 53, 'port': 'GigabitEthernet1/2/1', 'status': 'down'}, {'id': 54, 'port': 'GigabitEthernet1/2/2', 'status': 'up'}, {'id': 55, 'port': 'GigabitEthernet1/2/3', 'status': 'down'}, {'id': 56, 'port': 'GigabitEthernet1/2/4', 'status': 'down'}, {'id': 57, 'port': 'GigabitEthernet1/2/5', 'status': 'down'}, {'id': 58, 'port': 'GigabitEthernet1/2/6', 'status': 'down'}, {'id': 59, 'port': 'GigabitEthernet1/2/7', 'status': 'down'}, {'id': 60, 'port': 'GigabitEthernet1/2/8', 'status': 'down'}, {'id': 61, 'port': 'GigabitEthernet1/2/9', 'status': 'down'}, {'id': 62, 'port': 'GigabitEthernet1/2/10', 'status': 'down'}, {'id': 63, 'port': 'GigabitEthernet1/2/11', 'status': 'down'}, {'id': 64, 'port': 'GigabitEthernet1/2/12', 'status': 'down'}, {'id': 65, 'port': 'GigabitEthernet1/2/13', 'status': 'down'}, {'id': 66, 'port': 'GigabitEthernet1/2/14', 'status': 'down'}, {'id': 67, 'port': 'GigabitEthernet1/2/15', 'status': 'down'}, {'id': 68, 'port': 'GigabitEthernet1/2/16', 'status': 'down'}, {'id': 69, 'port': 'NULL0', 'status': 'up'}, {'id': 70, 'port': 'Ten-GigabitEthernet1/1/1', 'status': 'up'}, {'id': 71, 'port': 'Ten-GigabitEthernet1/1/2', 'status': 'up'}, {'id': 72, 'port': 'Ten-GigabitEthernet1/1/3', 'status': 'up'}, {'id': 73, 'port': 'Ten-GigabitEthernet1/1/4', 'status': 'up'}, {'id': 74, 'port': 'Vlan-interface1', 'status': 'down'}, {'id': 75, 'port': 'LoopBack0', 'status': 'up'}, {'id': 77, 'port': 'LoopBack127', 'status': 'up'}, {'id': 86, 'port': 'Vlan-interface101', 'status': 'up'}, {'id': 88, 'port': 'Bridge-Aggregation2', 'status': 'up'}, {'id': 89, 'port': 'Vlan-interface100', 'status': 'up'}, {'id': 90, 'port': 'LoopBack1', 'status': 'up'}, {'id': 91, 'port': 'Vlan-interface1402', 'status': 'up'}, {'id': 92, 'port': 'Vlan-interface1400', 'status': 'up'}]
