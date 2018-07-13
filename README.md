# hardware-gen8-sas-convert
用于转换 HP MicroServer Gen8 的 MiniSAS 端口顺序  
以使得 SATA SSD 能在最优状态下引导

介绍: [https://blog.mhycy.me/archives/16.html](https://blog.mhycy.me/archives/16.html)

**最终端口顺序**  
> SAS-1 -> SATA-5  
> SAS-2-> SAS-1  
> SAS-3-> SAS-2  
> SAS-4-> SAS-3  
> SATA-5 -> SAS-4  
