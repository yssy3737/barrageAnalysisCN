# barrageAnalysisCN
中文弹幕情感分析

## CMD Record
```sh
python logProcess.py server.log | grep -v '[empty] line' > barrage.temp
python segment.py > seg.temp
```
######
