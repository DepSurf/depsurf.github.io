# Function: <code>devm_rtc_allocate_device</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586290400,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:388",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586290400,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586753872,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:391",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586753872,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587020624,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:461",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587020624,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587180880,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:311",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587180880,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587446224,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446224,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587649344,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649344,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588516160,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:350",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588516160,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588541216,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:352",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588541216,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588424096,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:349",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588424096,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589091664,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:349",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589091664,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590535856,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:360",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590535856,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592188432,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:360",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188432,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592612160,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:360",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592612160,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593356960,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:360",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593356960,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500800128,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500800128,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233306020,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-pl031.c:pl031_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233306020,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294255344,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294255344,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277622574,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277622574,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587333104,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333104,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587101408,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101408,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587600592,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587600592,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```

```json
{
  "name": "devm_rtc_allocate_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587711408,
      "name": "devm_rtc_allocate_device",
      "external": true,
      "loc": "drivers/rtc/class.c:306",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587711408,
      "name": "devm_rtc_allocate_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct rtc_device * devm_rtc_allocate_device(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
