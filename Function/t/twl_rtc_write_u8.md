# Function: <code>twl_rtc_write_u8</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int twl_rtc_write_u8(struct twl_rtc * twl_rtc, u8 data, u8 reg)
```

```json
{
  "name": "twl_rtc_write_u8",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233346092,
      "name": "twl_rtc_write_u8",
      "external": false,
      "loc": "drivers/rtc/rtc-twl.c:171",
      "file": "drivers/rtc/rtc-twl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-twl.c:twl_rtc_probe",
        "drivers/rtc/rtc-twl.c:twl_rtc_probe",
        "drivers/rtc/rtc-twl.c:twl_rtc_probe",
        "drivers/rtc/rtc-twl.c:twl_rtc_interrupt",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_read_time",
        "drivers/rtc/rtc-twl.c:mask_rtc_irq_bit",
        "drivers/rtc/rtc-twl.c:set_rtc_irq_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233346092,
      "name": "twl_rtc_write_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int twl_rtc_write_u8(struct twl_rtc * twl_rtc, u8 data, u8 reg)
```
</details>
</li>
</ul>
