# koopman
采用Koopman算子去检测变化点
先采用前十二个点去找到Koopman算子，然后将该算子用于预测，当预测值与实际值相差过大时，则检测为异常点。
压缩包里是对应的python代码，相关数据可能需要重新去下载。