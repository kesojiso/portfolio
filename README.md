scrape.ipynbは、PCの価格とスペックの一覧、GPUのベンチマークスコアをスクレイピングしcsvとして保存するところまでのプログラムとなっております。
pc_analyze.ipynbは、保存したcsvを読み込み、解析するノートブックとなっており、OS,CPUスコア,メモリ容量,ストレージ容量,GPUスコア,Officeの有無等の情報からPCの価格を予測するモデルを作成しました。
また現在色々Tryしている最中ではございますが、今の段階では、重回帰モデルでは5,6割程度、XGBを用いたモデルでは7,8割程度の精度となっております。
