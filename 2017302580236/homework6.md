### P48

a)让W表示最大窗口大小。当最大发送速率达到链路容量时，当数据包丢弃时，WMSS/RTT=10 Gbps。因此，我们有W×1500×8/0.15=10乘10^9，然后W=125000段。

b)当拥塞窗口大小在W/2到W之间变化时，平均窗口大小为0.75W=93750。平均吞吐量为93750×1500×8/0.1=7.5Gbps。

c)当数据包丢失时，W变为W/2，即125/2=62。(125-62)×0.15=9.45秒，因为RTT的数量(此TCP连接将其窗口大小从62增加到125)为63。回想一下，每个RTT窗口的大小都会增加一个。

### P49

当TCP的平均吞吐量B由下式给出时

$B=\frac{1.22 \cdot MSS}{RTT \cdot \sqrt{L}}$

$L=(1.22\ast MSS/(B\ast RTT))^2$

由于在两个连续的分组丢失之间，由TCP发送的1/L分组因此，发送方T=(1/L)*MSS/B。因此，我们发现T=B*RTT22/(1.222*ms)，即T是AB.

### P52

W表示最大窗口大小。

首先，我们可以找到在TCP期间间隔期间发送的段总数将其窗口大小从W/2更改为并包括W。这通过以下方式给出：S=W/2（W/2）*（1个单位）（W/2）*（1个单位）2(w/2)*(1%)3(&C)..(w/2)*(1%)kK

我们发现K=log(1%)2，然后S=w*(2/1)/(2))。*

损耗率L由下式给出：

L=1/s=(2%)/(w×(2/1))。

TCP用于将其窗口大小从W/2增加到W的时间由下式给出：k×RTT＝(log(1％)2)×RTT，这显然与TCP的平均吞吐量无关。注意，TCP的平均吞吐量由下式给出：b=MSS*S/((k1)*RTT)=MSS/(L*(k1)*RTT)。

这与具有平均吞吐量的tcp不同：$B=\frac{1.22 \cdot MSS}{RTT \cdot \sqrt{L}}$，其中L的平方根出现在分母中。

​																				***by 2017302580236 刘一婧***