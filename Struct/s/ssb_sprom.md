# Struct: <code>ssb_sprom</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ssb_sprom {
    u8 revision;
    u8[6] il0mac;
    u8[6] et0mac;
    u8[6] et1mac;
    u8[6] et2mac;
    u8 et0phyaddr;
    u8 et1phyaddr;
    u8 et2phyaddr;
    u8 et0mdcport;
    u8 et1mdcport;
    u8 et2mdcport;
    u16 dev_id;
    u16 board_rev;
    u16 board_num;
    u16 board_type;
    u8 country_code;
    char[2] alpha2;
    u8 leddc_on_time;
    u8 leddc_off_time;
    u8 ant_available_a;
    u8 ant_available_bg;
    u16 pa0b0;
    u16 pa0b1;
    u16 pa0b2;
    u16 pa1b0;
    u16 pa1b1;
    u16 pa1b2;
    u16 pa1lob0;
    u16 pa1lob1;
    u16 pa1lob2;
    u16 pa1hib0;
    u16 pa1hib1;
    u16 pa1hib2;
    u8 gpio0;
    u8 gpio1;
    u8 gpio2;
    u8 gpio3;
    u8 maxpwr_bg;
    u8 maxpwr_al;
    u8 maxpwr_a;
    u8 maxpwr_ah;
    u8 itssi_a;
    u8 itssi_bg;
    u8 tri2g;
    u8 tri5gl;
    u8 tri5g;
    u8 tri5gh;
    u8[4] txpid2g;
    u8[4] txpid5gl;
    u8[4] txpid5g;
    u8[4] txpid5gh;
    s8 rxpo2g;
    s8 rxpo5g;
    u8 rssisav2g;
    u8 rssismc2g;
    u8 rssismf2g;
    u8 bxa2g;
    u8 rssisav5g;
    u8 rssismc5g;
    u8 rssismf5g;
    u8 bxa5g;
    u16 cck2gpo;
    u32 ofdm2gpo;
    u32 ofdm5glpo;
    u32 ofdm5gpo;
    u32 ofdm5ghpo;
    u32 boardflags;
    u32 boardflags2;
    u32 boardflags3;
    u16 boardflags_lo;
    u16 boardflags_hi;
    u16 boardflags2_lo;
    u16 boardflags2_hi;
    struct ssb_sprom_core_pwr_info[4] core_pwr_info;
    struct (anon) antenna_gain;
    struct (anon) fem;
    u16[8] mcs2gpo;
    u16[8] mcs5gpo;
    u16[8] mcs5glpo;
    u16[8] mcs5ghpo;
    u8 opo;
    u8[3] rxgainerr2ga;
    u8[3] rxgainerr5gla;
    u8[3] rxgainerr5gma;
    u8[3] rxgainerr5gha;
    u8[3] rxgainerr5gua;
    u8[3] noiselvl2ga;
    u8[3] noiselvl5gla;
    u8[3] noiselvl5gma;
    u8[3] noiselvl5gha;
    u8[3] noiselvl5gua;
    u8 regrev;
    u8 txchain;
    u8 rxchain;
    u8 antswitch;
    u16 cddpo;
    u16 stbcpo;
    u16 bw40po;
    u16 bwduppo;
    u8 tempthresh;
    u8 tempoffset;
    u16 rawtempsense;
    u8 measpower;
    u8 tempsense_slope;
    u8 tempcorrx;
    u8 tempsense_option;
    u8 freqoffset_corr;
    u8 iqcal_swp_dis;
    u8 hw_iqcal_en;
    u8 elna2g;
    u8 elna5g;
    u8 phycal_tempdelta;
    u8 temps_period;
    u8 temps_hysteresis;
    u8 measpower1;
    u8 measpower2;
    u8 pcieingress_war;
    u16 cckbw202gpo;
    u16 cckbw20ul2gpo;
    u32 legofdmbw202gpo;
    u32 legofdmbw20ul2gpo;
    u32 legofdmbw205glpo;
    u32 legofdmbw20ul5glpo;
    u32 legofdmbw205gmpo;
    u32 legofdmbw20ul5gmpo;
    u32 legofdmbw205ghpo;
    u32 legofdmbw20ul5ghpo;
    u32 mcsbw202gpo;
    u32 mcsbw20ul2gpo;
    u32 mcsbw402gpo;
    u32 mcsbw205glpo;
    u32 mcsbw20ul5glpo;
    u32 mcsbw405glpo;
    u32 mcsbw205gmpo;
    u32 mcsbw20ul5gmpo;
    u32 mcsbw405gmpo;
    u32 mcsbw205ghpo;
    u32 mcsbw20ul5ghpo;
    u32 mcsbw405ghpo;
    u16 mcs32po;
    u16 legofdm40duppo;
    u8 sar2g;
    u8 sar5g;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct ssb_sprom {
    u8 revision;
    u8[6] il0mac;
    u8[6] et0mac;
    u8[6] et1mac;
    u8[6] et2mac;
    u8 et0phyaddr;
    u8 et1phyaddr;
    u8 et2phyaddr;
    u8 et0mdcport;
    u8 et1mdcport;
    u8 et2mdcport;
    u16 dev_id;
    u16 board_rev;
    u16 board_num;
    u16 board_type;
    u8 country_code;
    char[2] alpha2;
    u8 leddc_on_time;
    u8 leddc_off_time;
    u8 ant_available_a;
    u8 ant_available_bg;
    u16 pa0b0;
    u16 pa0b1;
    u16 pa0b2;
    u16 pa1b0;
    u16 pa1b1;
    u16 pa1b2;
    u16 pa1lob0;
    u16 pa1lob1;
    u16 pa1lob2;
    u16 pa1hib0;
    u16 pa1hib1;
    u16 pa1hib2;
    u8 gpio0;
    u8 gpio1;
    u8 gpio2;
    u8 gpio3;
    u8 maxpwr_bg;
    u8 maxpwr_al;
    u8 maxpwr_a;
    u8 maxpwr_ah;
    u8 itssi_a;
    u8 itssi_bg;
    u8 tri2g;
    u8 tri5gl;
    u8 tri5g;
    u8 tri5gh;
    u8[4] txpid2g;
    u8[4] txpid5gl;
    u8[4] txpid5g;
    u8[4] txpid5gh;
    s8 rxpo2g;
    s8 rxpo5g;
    u8 rssisav2g;
    u8 rssismc2g;
    u8 rssismf2g;
    u8 bxa2g;
    u8 rssisav5g;
    u8 rssismc5g;
    u8 rssismf5g;
    u8 bxa5g;
    u16 cck2gpo;
    u32 ofdm2gpo;
    u32 ofdm5glpo;
    u32 ofdm5gpo;
    u32 ofdm5ghpo;
    u32 boardflags;
    u32 boardflags2;
    u32 boardflags3;
    u16 boardflags_lo;
    u16 boardflags_hi;
    u16 boardflags2_lo;
    u16 boardflags2_hi;
    struct ssb_sprom_core_pwr_info[4] core_pwr_info;
    struct (anon) antenna_gain;
    struct (anon) fem;
    u16[8] mcs2gpo;
    u16[8] mcs5gpo;
    u16[8] mcs5glpo;
    u16[8] mcs5ghpo;
    u8 opo;
    u8[3] rxgainerr2ga;
    u8[3] rxgainerr5gla;
    u8[3] rxgainerr5gma;
    u8[3] rxgainerr5gha;
    u8[3] rxgainerr5gua;
    u8[3] noiselvl2ga;
    u8[3] noiselvl5gla;
    u8[3] noiselvl5gma;
    u8[3] noiselvl5gha;
    u8[3] noiselvl5gua;
    u8 regrev;
    u8 txchain;
    u8 rxchain;
    u8 antswitch;
    u16 cddpo;
    u16 stbcpo;
    u16 bw40po;
    u16 bwduppo;
    u8 tempthresh;
    u8 tempoffset;
    u16 rawtempsense;
    u8 measpower;
    u8 tempsense_slope;
    u8 tempcorrx;
    u8 tempsense_option;
    u8 freqoffset_corr;
    u8 iqcal_swp_dis;
    u8 hw_iqcal_en;
    u8 elna2g;
    u8 elna5g;
    u8 phycal_tempdelta;
    u8 temps_period;
    u8 temps_hysteresis;
    u8 measpower1;
    u8 measpower2;
    u8 pcieingress_war;
    u16 cckbw202gpo;
    u16 cckbw20ul2gpo;
    u32 legofdmbw202gpo;
    u32 legofdmbw20ul2gpo;
    u32 legofdmbw205glpo;
    u32 legofdmbw20ul5glpo;
    u32 legofdmbw205gmpo;
    u32 legofdmbw20ul5gmpo;
    u32 legofdmbw205ghpo;
    u32 legofdmbw20ul5ghpo;
    u32 mcsbw202gpo;
    u32 mcsbw20ul2gpo;
    u32 mcsbw402gpo;
    u32 mcsbw205glpo;
    u32 mcsbw20ul5glpo;
    u32 mcsbw405glpo;
    u32 mcsbw205gmpo;
    u32 mcsbw20ul5gmpo;
    u32 mcsbw405gmpo;
    u32 mcsbw205ghpo;
    u32 mcsbw20ul5ghpo;
    u32 mcsbw405ghpo;
    u16 mcs32po;
    u16 legofdm40duppo;
    u8 sar2g;
    u8 sar5g;
}
```
</details>
</li>
</ul>
