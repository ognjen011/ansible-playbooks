# switch - Neighbors and EIGRP learned routes

| Neighbor | Local Interface | Neighbor IP Address | Remote Interface | Summary Routes |
| -------- | --------------- | ------------------- | ---------------- | -------------- |
| switch2 | GigabitEthernet9/42 | 10.254.135.1 | GigabitEthernet1/1 | [u'10.135.0.0/16'] |
| switch3 | TenGigabitEthernet1/4 | 10.254.56.6 | TenGigabitEthernet5/1 | [u'10.56.0.0/19'] |
| switch4 | TenGigabitEthernet1/6 | 10.254.55.6 | TenGigabitEthernet7/1 | [u'10.55.0.0/19'] |

# switch - Summarization Report for access switches
| Numbers of routes pre-summarized | Number of routes post-summarized | Summarized Route |
| -------- | --------------- | ------------------- |
| 93 | 35 | ['10.55.0.0/19', '10.56.0.0/19', '10.135.0.0/16'] |