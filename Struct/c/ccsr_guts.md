# Struct: <code>ccsr_guts</code>

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
struct ccsr_guts {
    u32 porpllsr;
    u32 porbmsr;
    u32 porimpscr;
    u32 pordevsr;
    u32 pordbgmsr;
    u32 pordevsr2;
    u8[8] res018;
    u32 porcir;
    u8[12] res024;
    u32 gpiocr;
    u8[12] res034;
    u32 gpoutdr;
    u8[12] res044;
    u32 gpindr;
    u8[12] res054;
    u32 pmuxcr;
    u32 pmuxcr2;
    u32 dmuxcr;
    u8[4] res06c;
    u32 devdisr;
    u32 devdisr2;
    u8[4] res078;
    u32 pmjcr;
    u32 powmgtcsr;
    u32 pmrccr;
    u32 pmpdccr;
    u32 pmcdr;
    u32 mcpsumr;
    u32 rstrscr;
    u32 ectrstcr;
    u32 autorstsr;
    u32 pvr;
    u32 svr;
    u8[8] res0a8;
    u32 rstcr;
    u8[12] res0b4;
    u32 iovselsr;
    u8[60] res0c4;
    u32[16] rcwsr;
    u8[228] res140;
    u32 iodelay1;
    u32 iodelay2;
    u8[984] res22c;
    u32 pamubypenr;
    u8[504] res608;
    u32 clkdvdr;
    u8[252] res804;
    u32 ircr;
    u8[4] res904;
    u32 dmacr;
    u8[8] res90c;
    u32 elbccr;
    u8[520] res918;
    u32 ddr1clkdr;
    u32 ddr2clkdr;
    u32 ddrclkdr;
    u8[724] resb2c;
    u32 clkocr;
    u8[12] rese04;
    u32 ddrdllcr;
    u8[12] rese14;
    u32 lbcdllcr;
    u32 cpfor;
    u8[220] rese28;
    u32 srds1cr0;
    u32 srds1cr1;
    u8[32] resf0c;
    u32 itcr;
    u8[16] resf30;
    u32 srds2cr0;
    u32 srds2cr1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ccsr_guts {
    u32 porpllsr;
    u32 porbmsr;
    u32 porimpscr;
    u32 pordevsr;
    u32 pordbgmsr;
    u32 pordevsr2;
    u8[8] res018;
    u32 porcir;
    u8[12] res024;
    u32 gpiocr;
    u8[12] res034;
    u32 gpoutdr;
    u8[12] res044;
    u32 gpindr;
    u8[12] res054;
    u32 pmuxcr;
    u32 pmuxcr2;
    u32 dmuxcr;
    u8[4] res06c;
    u32 devdisr;
    u32 devdisr2;
    u8[4] res078;
    u32 pmjcr;
    u32 powmgtcsr;
    u32 pmrccr;
    u32 pmpdccr;
    u32 pmcdr;
    u32 mcpsumr;
    u32 rstrscr;
    u32 ectrstcr;
    u32 autorstsr;
    u32 pvr;
    u32 svr;
    u8[8] res0a8;
    u32 rstcr;
    u8[12] res0b4;
    u32 iovselsr;
    u8[60] res0c4;
    u32[16] rcwsr;
    u8[228] res140;
    u32 iodelay1;
    u32 iodelay2;
    u8[984] res22c;
    u32 pamubypenr;
    u8[504] res608;
    u32 clkdvdr;
    u8[252] res804;
    u32 ircr;
    u8[4] res904;
    u32 dmacr;
    u8[8] res90c;
    u32 elbccr;
    u8[520] res918;
    u32 ddr1clkdr;
    u32 ddr2clkdr;
    u32 ddrclkdr;
    u8[724] resb2c;
    u32 clkocr;
    u8[12] rese04;
    u32 ddrdllcr;
    u8[12] rese14;
    u32 lbcdllcr;
    u32 cpfor;
    u8[220] rese28;
    u32 srds1cr0;
    u32 srds1cr1;
    u8[32] resf0c;
    u32 itcr;
    u8[16] resf30;
    u32 srds2cr0;
    u32 srds2cr1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ccsr_guts {
    u32 porpllsr;
    u32 porbmsr;
    u32 porimpscr;
    u32 pordevsr;
    u32 pordbgmsr;
    u32 pordevsr2;
    u8[8] res018;
    u32 porcir;
    u8[12] res024;
    u32 gpiocr;
    u8[12] res034;
    u32 gpoutdr;
    u8[12] res044;
    u32 gpindr;
    u8[12] res054;
    u32 pmuxcr;
    u32 pmuxcr2;
    u32 dmuxcr;
    u8[4] res06c;
    u32 devdisr;
    u32 devdisr2;
    u8[4] res078;
    u32 pmjcr;
    u32 powmgtcsr;
    u32 pmrccr;
    u32 pmpdccr;
    u32 pmcdr;
    u32 mcpsumr;
    u32 rstrscr;
    u32 ectrstcr;
    u32 autorstsr;
    u32 pvr;
    u32 svr;
    u8[8] res0a8;
    u32 rstcr;
    u8[12] res0b4;
    u32 iovselsr;
    u8[60] res0c4;
    u32[16] rcwsr;
    u8[228] res140;
    u32 iodelay1;
    u32 iodelay2;
    u8[984] res22c;
    u32 pamubypenr;
    u8[504] res608;
    u32 clkdvdr;
    u8[252] res804;
    u32 ircr;
    u8[4] res904;
    u32 dmacr;
    u8[8] res90c;
    u32 elbccr;
    u8[520] res918;
    u32 ddr1clkdr;
    u32 ddr2clkdr;
    u32 ddrclkdr;
    u8[724] resb2c;
    u32 clkocr;
    u8[12] rese04;
    u32 ddrdllcr;
    u8[12] rese14;
    u32 lbcdllcr;
    u32 cpfor;
    u8[220] rese28;
    u32 srds1cr0;
    u32 srds1cr1;
    u8[32] resf0c;
    u32 itcr;
    u8[16] resf30;
    u32 srds2cr0;
    u32 srds2cr1;
}
```
</details>
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
struct ccsr_guts {
    u32 porpllsr;
    u32 porbmsr;
    u32 porimpscr;
    u32 pordevsr;
    u32 pordbgmsr;
    u32 pordevsr2;
    u8[8] res018;
    u32 porcir;
    u8[12] res024;
    u32 gpiocr;
    u8[12] res034;
    u32 gpoutdr;
    u8[12] res044;
    u32 gpindr;
    u8[12] res054;
    u32 pmuxcr;
    u32 pmuxcr2;
    u32 dmuxcr;
    u8[4] res06c;
    u32 devdisr;
    u32 devdisr2;
    u8[4] res078;
    u32 pmjcr;
    u32 powmgtcsr;
    u32 pmrccr;
    u32 pmpdccr;
    u32 pmcdr;
    u32 mcpsumr;
    u32 rstrscr;
    u32 ectrstcr;
    u32 autorstsr;
    u32 pvr;
    u32 svr;
    u8[8] res0a8;
    u32 rstcr;
    u8[12] res0b4;
    u32 iovselsr;
    u8[60] res0c4;
    u32[16] rcwsr;
    u8[228] res140;
    u32 iodelay1;
    u32 iodelay2;
    u8[984] res22c;
    u32 pamubypenr;
    u8[504] res608;
    u32 clkdvdr;
    u8[252] res804;
    u32 ircr;
    u8[4] res904;
    u32 dmacr;
    u8[8] res90c;
    u32 elbccr;
    u8[520] res918;
    u32 ddr1clkdr;
    u32 ddr2clkdr;
    u32 ddrclkdr;
    u8[724] resb2c;
    u32 clkocr;
    u8[12] rese04;
    u32 ddrdllcr;
    u8[12] rese14;
    u32 lbcdllcr;
    u32 cpfor;
    u8[220] rese28;
    u32 srds1cr0;
    u32 srds1cr1;
    u8[32] resf0c;
    u32 itcr;
    u8[16] resf30;
    u32 srds2cr0;
    u32 srds2cr1;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct ccsr_guts {
    u32 porpllsr;
    u32 porbmsr;
    u32 porimpscr;
    u32 pordevsr;
    u32 pordbgmsr;
    u32 pordevsr2;
    u8[8] res018;
    u32 porcir;
    u8[12] res024;
    u32 gpiocr;
    u8[12] res034;
    u32 gpoutdr;
    u8[12] res044;
    u32 gpindr;
    u8[12] res054;
    u32 pmuxcr;
    u32 pmuxcr2;
    u32 dmuxcr;
    u8[4] res06c;
    u32 devdisr;
    u32 devdisr2;
    u8[4] res078;
    u32 pmjcr;
    u32 powmgtcsr;
    u32 pmrccr;
    u32 pmpdccr;
    u32 pmcdr;
    u32 mcpsumr;
    u32 rstrscr;
    u32 ectrstcr;
    u32 autorstsr;
    u32 pvr;
    u32 svr;
    u8[8] res0a8;
    u32 rstcr;
    u8[12] res0b4;
    u32 iovselsr;
    u8[60] res0c4;
    u32[16] rcwsr;
    u8[228] res140;
    u32 iodelay1;
    u32 iodelay2;
    u8[984] res22c;
    u32 pamubypenr;
    u8[504] res608;
    u32 clkdvdr;
    u8[252] res804;
    u32 ircr;
    u8[4] res904;
    u32 dmacr;
    u8[8] res90c;
    u32 elbccr;
    u8[520] res918;
    u32 ddr1clkdr;
    u32 ddr2clkdr;
    u32 ddrclkdr;
    u8[724] resb2c;
    u32 clkocr;
    u8[12] rese04;
    u32 ddrdllcr;
    u8[12] rese14;
    u32 lbcdllcr;
    u32 cpfor;
    u8[220] rese28;
    u32 srds1cr0;
    u32 srds1cr1;
    u8[32] resf0c;
    u32 itcr;
    u8[16] resf30;
    u32 srds2cr0;
    u32 srds2cr1;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct ccsr_guts {
    u32 porpllsr;
    u32 porbmsr;
    u32 porimpscr;
    u32 pordevsr;
    u32 pordbgmsr;
    u32 pordevsr2;
    u8[8] res018;
    u32 porcir;
    u8[12] res024;
    u32 gpiocr;
    u8[12] res034;
    u32 gpoutdr;
    u8[12] res044;
    u32 gpindr;
    u8[12] res054;
    u32 pmuxcr;
    u32 pmuxcr2;
    u32 dmuxcr;
    u8[4] res06c;
    u32 devdisr;
    u32 devdisr2;
    u8[4] res078;
    u32 pmjcr;
    u32 powmgtcsr;
    u32 pmrccr;
    u32 pmpdccr;
    u32 pmcdr;
    u32 mcpsumr;
    u32 rstrscr;
    u32 ectrstcr;
    u32 autorstsr;
    u32 pvr;
    u32 svr;
    u8[8] res0a8;
    u32 rstcr;
    u8[12] res0b4;
    u32 iovselsr;
    u8[60] res0c4;
    u32[16] rcwsr;
    u8[228] res140;
    u32 iodelay1;
    u32 iodelay2;
    u8[984] res22c;
    u32 pamubypenr;
    u8[504] res608;
    u32 clkdvdr;
    u8[252] res804;
    u32 ircr;
    u8[4] res904;
    u32 dmacr;
    u8[8] res90c;
    u32 elbccr;
    u8[520] res918;
    u32 ddr1clkdr;
    u32 ddr2clkdr;
    u32 ddrclkdr;
    u8[724] resb2c;
    u32 clkocr;
    u8[12] rese04;
    u32 ddrdllcr;
    u8[12] rese14;
    u32 lbcdllcr;
    u32 cpfor;
    u8[220] rese28;
    u32 srds1cr0;
    u32 srds1cr1;
    u8[32] resf0c;
    u32 itcr;
    u8[16] resf30;
    u32 srds2cr0;
    u32 srds2cr1;
}
```
</details>
</li>
</ul>
