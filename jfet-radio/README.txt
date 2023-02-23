FETを使ったラジオを作りたくてJFETアンプ設計してみた
電源は5Vで入力はゼロクロスで最大でも200mVpp
FETは2sk303 3mA級あたりを想定
Id0mA付近ではyfsが低くなるのでVgsを0からあまり遠ざけたくない
そうするとソースにはあまり高抵抗を入れられないので
Negative Feedbackはそこそこに半分固定バイアスみたいにするとうまくいくっぽい

webシミレーター
https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjOB0CsDsAMBmaZbQBywJyK7ApgLSwjyQBMW0ALCmNOQluWPCdSdCNIt0WGABQAJxCNyY8tTGwJicvFLgFggFaTpC9DIlalhMtrLx4ANkEAlDWPjbUpm0fDgsWE4rIQPpGJZ0h0RXIpAO9FakUuMN9RcVD-MGYlVhNBAHkEpMREB0SJD0EAc395INkQZHzSQQB3TLkFF3zBAHsxZ3D4LCNIRDByKMh3LthTaFMBpV0K1u4OkFh0dAwKyFdEalxFkfR+h2MTCCPZiFNpTtc5g77JiVyK+YheL2dEQSA

JFETのモデルは以下から
 http://www.cyada.org/oto/audio/spice/jft.html
助言を頂いてランクに合わせて修正した
 https://rio2016.5ch.net/test/read.cgi/denki/1580718148/62-66
購入先
 https://akizukidenshi.com/catalog/g/gI-09507/
参考
 https://lab4sys.com/en/spice-simulation-of-jfet-field-effect-transistors/


