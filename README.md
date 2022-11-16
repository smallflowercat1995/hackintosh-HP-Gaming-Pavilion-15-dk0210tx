# hackintosh-HP-Gaming-Pavilion-15-dk0210tx
黑苹果 ventura 光影精灵 HP Gaming Pavilion - 15-dk0210tx  

## 描述
`EFI` 是调好的 opencore 0.8.7 引导，三码已清，自行更换，清理nvram  
`opencore debug 流程` 是针对个人机器 光影精灵-HP-Gaming-Pavilion-15-dk0210tx 做的记录和调试，方便自己以后做参考，其它主板型号和CPU请酌情参考  

## 官方机型参数
https://support.hp.com/cn-zh/document/c06498444  

## 注意
本人的 傲腾SSD 支持安装 Ventura 可以按照流程制作 nvme.aml 补丁，其实就在 EFI -> OC -> ACPI 里。  
本人已经将intel网卡替换成了 博通网卡 Broadcom BCM43224AG 802.11a/b/g/draft-n Wireless Network Adapter PCI 然而买错了不能免驱  
所以网卡配置如下：  
<img width="964" alt="image" src="https://user-images.githubusercontent.com/94947393/201841163-97df13ad-4a79-4dab-af6b-25089f28a4b2.png">


## 声明
对于 `opencore debug 流程` 请斟酌参考，若参考某流程导致机毁人亡，本人不敢也没能力承担责任，实在抱歉
