#アプリケーション例を考えていく
Sensor Processor Actuatorのなかで2つを人が担当するようなのが増えそう？

## Sensor
###冷房調整アプリ
複数人に対し、温度調整に対する質問を投げる(Sensor)(Human)
複数人からの質問返答から、冷房が正しく設定されているか判断する(Processing)
温度を調整する(Actuate)

## Actuator
###クックパッドアプリ
クックパッドで選んだレシピのなかで、足りない食材の購入を命令できる
冷蔵庫をSensing→クックパッドのレシピに基づいてProcessing→足りない食材の購入に関して、HumanにActuateさせる。

## Processor
###鍵認証アプリ
来客者が誰かを自分で判断し、解錠するかどうかを選べる
来客者の存在をSensorで感知→来客者をHumanが見て、解錠するかどうかをProcessingする→ドアを開けるようActuate

##Sensor & Processor
###空気を読むアプリ
コンテキストを読むことは、センサーには難しい。
空気を人によってSensorし、Processingして状況を判断。何かしらのActuateを行う。

## Processor & Actuator

## Sensor & Actuator