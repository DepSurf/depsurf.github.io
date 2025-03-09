# Function: <code>__rtc_register_device</code>

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
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586288176,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:426",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586288176,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586751632,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:429",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586751632,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587018400,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:499",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018400,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587179520,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:349",
      "file": "drivers/rtc/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587179520,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587446811,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/class.c:devm_rtc_device_register"
      ],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444944,
      "name": "__rtc_register_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071587446853,
      "name": "__rtc_register_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587445360,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587648127,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649961,
      "name": "__rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587648016,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588516411,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:388",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/class.c:devm_rtc_device_register"
      ],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588514640,
      "name": "__rtc_register_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071588516507,
      "name": "__rtc_register_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071588514848,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500800760,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
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
      "addr": 18446603336500800760,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233306588,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
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
      "addr": 3233306588,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294252912,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294252912,
      "name": "__rtc_register_device",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277622138,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277622138,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587331887,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333721,
      "name": "__rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587331776,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587100191,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587102025,
      "name": "__rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587100080,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587599375,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587601209,
      "name": "__rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587599264,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587710191,
      "name": "__rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:344",
      "file": "drivers/rtc/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587712025,
      "name": "__rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587710080,
      "name": "__rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int __rtc_register_device(struct module * owner, struct rtc_device * rtc)
```
</details>
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
