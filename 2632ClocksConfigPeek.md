From Pershoot's August 2.6.32 build using CM7 ROM and Config Peek Module on 11/23. Posted by plastikman
```
   clock                          state  ref div      rate
--------------------------------------------------------------
  *cdev2                          off    1            0         
  *cdev1                          off    1            0         
  *clk_m                          uninit 1            12000000  
     *pcie_xclk                   off    1   1        12000000  
     *afi                         off    1   1        12000000  
     *pex                         off    1   1        12000000  
     *csus                        on     1   1        12000000  
     *isp                         off    1   1        12000000  
     *usb3                        on     1   1        12000000  
     *usb2                        off    1   1        12000000  
     *usbd                        on     1   1        12000000  
     *disp2                       off    1   1        12000000  
     *tvdac                       off    1   1        12000000  
     *hdmi                        off    1   1        12000000  
     *tvo                         off    1   1        12000000  
     *cve                         off    1   1        12000000  
     *uarte                       off    1   1        12000000  
     *uartd                       off    1   1        12000000  
     *uartc                       off    1   1        12000000  
     *uartb                       off    1   1        12000000  
     *dvc                         off    1   4        3000000   
     *i2c3                        off    1   8        1500000   
     *i2c2                        off    1   30       400000    
     *i2c1                        off    1   15       800000    
     *mipi                        off    1   1        12000000  
     *nor                         off    1   1        12000000  
     *owr                         off    1   1        12000000  
     *la                          off    1   1        12000000  
     *bsev                        on     1   1        12000000  
     *bsea                        off    1   1        12000000  
     *vcp                         off    1   1        12000000  
     *sdmmc3                      on     1   30       400000    
     *sdmmc2                      off    1   1        12000000  
     *vfir                        off    1   1        12000000  
     *ide                         off    1   1        12000000  
     *sbc4                        off    1   1        12000000  
     *sbc3                        off    1   1        12000000  
     *sbc2                        off    1   1        12000000  
     *sbc1                        off    1   1        12000000  
     *twc                         off    1   1        12000000  
     *xio                         off    1   1        12000000  
     *spi                         off    1   1        12000000  
     *pwm                         on     1   128.5    93385     
     *i2s2                        off    1   1        12000000  
     *kfuse                       off    1   1        12000000  
     *timer                       on     1   1        12000000  
     *clk_d                       off    1   x2       24000000  
     *pll_e                       off    1   x100     1200000000
     *pll_x                       on     1   x83.3..  1000000000
        *cclk                     on     1            1000000000
           *cpu                   uninit 1            1000000000
     *pll_u                       on     1   x40      480000000 
     *pll_d                       off    1   12       1000000   
        *dsi                      off    1   1        1000000   
        *pll_d_out0               off    1   2        500000    
     *pll_p                       on     1   x18      216000000 
        *disp1                    on     1   1        216000000 
        *host1x                   on     1   2        108000000 
        *uarta                    on     1   1        216000000 
        *csite                    on     1   1.5      144000000 
        *sdmmc4                   on     1   4.5      48000000  
        *sdmmc1                   on     1   9        24000000  
        *ndflash                  off    1   2        108000000 
        *spdif_in                 off    1   6        36000000  
        *pll_p_out4               on     1   9        24000000  
        *pll_p_out3               on     1   3        72000000  
           *csi                   off    1   1        72000000  
           *dvc_i2c               on     1   1        72000000  
           *i2c3_i2c              on     1   1        72000000  
           *i2c2_i2c              on     1   1        72000000  
           *i2c1_i2c              on     1   1        72000000  
        *pll_p_out2               on     1   2        108000000 
        *pll_p_out1               on     1   7.5      28800000  
           *pll_a                 on     1   x1.9..   56448000  
              *pll_a_out0         on     1   5        11289600  
                 *audio           on     1            11289600  
                    *audio_2x     off    1   x2       22579200  
                 *spdif_out       off    1   2        5644800   
                 *i2s1            off    1   4        2822400   
     *pll_c                       on     1   x50      600000000 
        *epp                      on     1   2        300000000 
        *2d                       on     1   2        300000000 
        *vde                      on     1   2.5      240000000 
        *pll_c_out1               on     1   2.5      240000000 
           *sclk                  on     1            240000000 
               avp.sclk           off    1            240000000 
              *cop                uninit 1            240000000 
              *hclk               on     1   1        240000000 
                 *pclk            on     1   2        120000000 
                    *apbdma       on     1   1        120000000 
     *pll_m                       on     1   x55.5    666000000 
        *mpe                      off    1   6        111000000 
        *vi_sensor                on     1   33.5     19880597  
        *vi                       on     1   31.5     21142857  
        *3d                       off    1   2        333000000 
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
     *blink                       on     1   1        32768     
     *pll_s                       off    1   1        32768     
```