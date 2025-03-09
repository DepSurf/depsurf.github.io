# Function: <code>cs_watchdog_read</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool cs_watchdog_read(struct clocksource * cs, u64 * csnow, u64 * wdnow)
```

```json
{
  "name": "cs_watchdog_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cs_watchdog_read",
      "external": false,
      "loc": "kernel/time/clocksource.c:197",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191504,
      "name": "cs_watchdog_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071591253868,
      "name": "cs_watchdog_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource * cs, u64 * csnow, u64 * wdnow)
```

```json
{
  "name": "cs_watchdog_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cs_watchdog_read",
      "external": false,
      "loc": "kernel/time/clocksource.c:214",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580337904,
      "name": "cs_watchdog_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071592154333,
      "name": "cs_watchdog_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource * cs, u64 * csnow, u64 * wdnow)
```

```json
{
  "name": "cs_watchdog_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cs_watchdog_read",
      "external": false,
      "loc": "kernel/time/clocksource.c:220",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550864,
      "name": "cs_watchdog_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071593929332,
      "name": "cs_watchdog_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource * cs, u64 * csnow, u64 * wdnow)
```

```json
{
  "name": "cs_watchdog_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cs_watchdog_read",
      "external": false,
      "loc": "kernel/time/clocksource.c:220",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808496,
      "name": "cs_watchdog_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    },
    {
      "addr": 18446744071595997279,
      "name": "cs_watchdog_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource * cs, u64 * csnow, u64 * wdnow)
```

```json
{
  "name": "cs_watchdog_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cs_watchdog_read",
      "external": false,
      "loc": "kernel/time/clocksource.c:223",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891664,
      "name": "cs_watchdog_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071596515562,
      "name": "cs_watchdog_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource * cs, u64 * csnow, u64 * wdnow)
```

```json
{
  "name": "cs_watchdog_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cs_watchdog_read",
      "external": false,
      "loc": "kernel/time/clocksource.c:225",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982096,
      "name": "cs_watchdog_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071597414889,
      "name": "cs_watchdog_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool cs_watchdog_read(struct clocksource * cs, u64 * csnow, u64 * wdnow)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>enum wd_read_status</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
