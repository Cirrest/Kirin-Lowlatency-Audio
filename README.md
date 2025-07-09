# Kirin Lowlatency Audio
Huawei Kirin Processor Low latency Audio Maigsk Module<br>
This is a module that improves the audio quality and reduces audio latency of Huawei Kirin processors.<br>
The project is also posted in [CoolApk](https://www.coolapk.com/feed/52302433?shareKey=Zjg1MjExYTc5MzdiNjZiNzZiMDg~&shareUid=2679393&shareFrom=com.coolapk.market_14.4.0-beta2
)
<br><br>

The module supports operation on the following models:
----
Sound card (Mandatory) : hi3660_hi6430_Card<br>
System:EMUI/HarmonyOS<br>
This can be seen in hardware-audio with Root permissions in Devcheck<br>
Support processor: Kirin 960, Kirin 970, Kirin 980(?)<br>
You may use it on other processors to turn off those sound effects<br><br>

How it Works:
----
Enable Huawei's hidden Kirin Low Latency audio channel<br>
Huawei Audio offload and HiRes modes are enabled<br>
Disable SWS(histen), DTS, and Dolby sound effects at the system level<br>
The system declares Low Latency support so that software that supports this feature can use this channel<br>
The driver interface enables features such as Low Latency Mixer and CLK and DRV<br>
Enable the low-power Audio DSP function<br><br>

Bring results:
----
Global audio delay reduction<br>
Declaring Support for Low Latency applications can use the Low Latency channel to further reduce latency<br>
The OpenSL ES HD and Direct audio apis can output high quality audio directly without the impact of repeated degradation and resampling of system sound effects and SRC<br>
Audio playback power consumption is reduced<br><br>

Negative effects:
----
Sound effects will be turned off (disable the module and restart the system to recover)<br>
Some devices cannot output normal audio (the problem is not supported by the device)<br>
The results may vary depending on the hardware and software of the device.<br><br>
![iamge](https://github.com/Cirrest/Kirin-Lowlatency-Audio/blob/main/1.jpeg)
![iamge](https://github.com/Cirrest/Kirin-Lowlatency-Audio/blob/main/2.jpeg)
![iamge](https://github.com/Cirrest/Kirin-Lowlatency-Audio/blob/main/3.jpeg)
