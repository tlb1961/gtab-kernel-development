From GTab HC Development Build and 2.6.36 kernel on 11/23 with Config Peek Module. Posted by fosser2
```
  *cdev2                          off    1            0          
  *cdev1                          off    1            0          
  *clk_m                          uninit 1            12000000    
     *pcie_xclk                   off    1   1        12000000    
     *afi                         off    1   1        12000000    
     *pex                         off    1   1        12000000    
     *csus                        on     1   1        12000000    
     *isp                         on     1   1        12000000    
     *usb3                        on     1   1        12000000    
     *usb2                        off    1   1        12000000    
     *usbd                        on     1   1        12000000    
     *tvdac                       off    1   1        12000000    
     *hdmi                        off    1   1        12000000    
     *tvo                         off    1   1        12000000    
     *cve                         off    1   1        12000000    
     *dvc                         off    1   15       800000      
     *i2c3                        off    1   15       800000      
     *i2c2                        off    1   4        3000000    
     *i2c1                        on     1   15       800000      
     *mipi                        off    1   1        12000000    
     *nor                         off    1   1        12000000    
     *owr                         off    1   1        12000000    
     *la                          off    1   1        12000000    
     *bsev                        off    1   1        12000000    
     *bsea                        off    1   1        12000000    
     *vcp                         off    1   1        12000000    
     *vfir                        off    1   1        12000000    
     *ide                         off    1   1        12000000    
     *sbc4                        off    1   1        12000000    
     *sbc3                        off    1   1        12000000    
     *sbc2                        off    1   1        12000000    
     *sbc1                        off    1   1        12000000    
     *twc                         off    1   1        12000000    
     *xio                         off    1   1        12000000    
     *spi                         off    1   1        12000000    
     *pwm                         on     1   1        12000000    
     *kfuse                       on     1   1        12000000    
     *timer                       on     1   1        12000000    
     *clk_d                       on     1   x2       24000000    
     *pll_e                       off    1   x100     1200000000  
     *pll_x                       on     1   x26      312000000  
        *cclk                     on     1            312000000  
           *cpu                   uninit 1            312000000  
     *pll_u                       on     1   x40      480000000  
     *pll_d                       on     1   2.5      5000000    
        *dsi                      off    1   1        5000000    
        *pll_d_out0               off    1   2        2500000    
     *pll_p                       on     1   x18      216000000  
        *disp2                    off    1   1        216000000  
        *disp1                    on     1   1        216000000  
        *host1x                   on     1   1.5      144000000  
        *uarte                    off    1   1        216000000  
        *uartd                    off    1   1        216000000  
        *uartc                    off    1   1        216000000  
        *uartb                    off    1   1        216000000  
        *uarta                    off    1   1        216000000  
        *csite                    on     1   1.5      144000000  
        *vde                      off    1   1        216000000  
        *sdmmc4                   on     1   7.5      28800000    
        *sdmmc3                   on     1   4.5      48000000    
        *sdmmc2                   off    1   4.5      48000000    
        *sdmmc1                   on     1   4.5      48000000    
        *ndflash                  on     1   2        108000000  
        *spdif_in                 on     1   35.5     6084507    
           *audio                 on     1            6084507    
              *audio_2x           on     1   x2       12169014    
        *pll_p_out4               on     1   8.5      25411764    
        *pll_p_out3               on     1   3        72000000    
           *csi                   on     1   1        72000000    
           *dvc_i2c               on     1   1        72000000    
           *i2c3_i2c              on     1   1        72000000    
           *i2c2_i2c              on     1   1        72000000    
           *i2c1_i2c              on     1   1        72000000    
        *pll_p_out2               on     1   2        108000000  
           *sclk                  on     1            108000000  
               avp.sclk           off    1            108000000  
              *cop                uninit 1            108000000  
              *hclk               on     1   1        108000000  
                 *pclk            on     1   2        54000000    
                    *apbdma       on     1   1        54000000    
        *pll_p_out1               on     1   7.5      28800000    
           *pll_a                 on     1   x1.9..   56448000    
              *pll_a_out0         on     1   5        11289600    
                 *spdif_out       on     1   2        5644800    
                 *i2s2            on     1   6        1881600    
                 *i2s1            on     1   1        11289600    
     *pll_c                       on     1   x50      600000000  
        *mpe                      off    1   2.5      240000000  
        *epp                      off    1   2        300000000  
        *vi_sensor                on     1   5.5      109090909  
        *vi                       on     1   5.5      109090909  
        *2d                       off    1   2        300000000  
        *3d                       off    1   2        300000000  
        *pll_c_out1               on     1   4        150000000  
     *pll_m                       on     1   x55.5    666000000  
        *emc                      on     1   1        666000000  
            usb3.emc              off    1            666000000  
            usb2.emc              off    1            666000000  
            usb1.emc              off    1            666000000  
            usbd.emc              off    1            666000000  
            host.emc              off    1            666000000  
            hdmi.emc              off    1            666000000  
            disp2.emc             off    1            666000000  
            disp1.emc             off    1            666000000  
            cpu.emc               off    1            666000000  
            avp.emc               off    1            666000000  
        *pll_m_out1               on     1   3        222000000  
   clk_32k                        on     1            32768      
     *rtc                         on     1   1        32768      
     *kbc                         off    1   1        32768      
     *blink                       off    1   1        32768      
     *pll_s                       on     1   x366     11993088    
```