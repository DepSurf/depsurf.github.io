# Function: <code>mc146818_avoid_UIP</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool mc146818_avoid_UIP(void (*)(unsigned char, void *) callback, void * param)
```

```json
{
  "name": "mc146818_avoid_UIP",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590556160,
      "name": "mc146818_avoid_UIP",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:17",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_does_rtc_work",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590556160,
      "name": "mc146818_avoid_UIP",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool mc146818_avoid_UIP(void (*)(unsigned char, void *) callback, void * param)
```

```json
{
  "name": "mc146818_avoid_UIP",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592210368,
      "name": "mc146818_avoid_UIP",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:17",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_does_rtc_work",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592210368,
      "name": "mc146818_avoid_UIP",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool mc146818_avoid_UIP(void (*)(unsigned char, void *) callback, void * param)
```

```json
{
  "name": "mc146818_avoid_UIP",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592634656,
      "name": "mc146818_avoid_UIP",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:17",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_does_rtc_work",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592634656,
      "name": "mc146818_avoid_UIP",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool mc146818_avoid_UIP(void (*)(unsigned char, void *) callback, int timeout, void * param)
```

```json
{
  "name": "mc146818_avoid_UIP",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593379472,
      "name": "mc146818_avoid_UIP",
      "external": true,
      "loc": "drivers/rtc/rtc-mc146818-lib.c:21",
      "file": "drivers/rtc/rtc-mc146818-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_does_rtc_work",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_read_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593379472,
      "name": "mc146818_avoid_UIP",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool mc146818_avoid_UIP(void (*)(unsigned char, void *) callback, void * param)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int timeout</code>
</li>
<li>
<b>Param reordered. </b>
<code>callback, param</code> ➡️ <code>callback, timeout, param</code>
</li>
</ul>
</details>
</li>
</ul>
