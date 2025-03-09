# Function: <code>__devm_rtc_register_device</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __devm_rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__devm_rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588541435,
      "name": "__devm_rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:379",
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
      "addr": 18446744071588539696,
      "name": "__devm_rtc_register_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071591576774,
      "name": "__devm_rtc_register_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071588539904,
      "name": "__devm_rtc_register_device",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __devm_rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__devm_rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devm_rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:376",
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
      "addr": 18446744071591519642,
      "name": "__devm_rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071588422704,
      "name": "__devm_rtc_register_device",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __devm_rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__devm_rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devm_rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:376",
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
      "addr": 18446744071592628188,
      "name": "__devm_rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071589090272,
      "name": "__devm_rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
int __devm_rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__devm_rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devm_rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:389",
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
      "addr": 18446744071594511805,
      "name": "__devm_rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071590534832,
      "name": "__devm_rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
int __devm_rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__devm_rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devm_rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:389",
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
      "addr": 18446744071596307286,
      "name": "__devm_rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592187088,
      "name": "__devm_rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 914
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
int __devm_rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__devm_rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devm_rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:389",
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
      "addr": 18446744071596836697,
      "name": "__devm_rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592610816,
      "name": "__devm_rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
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
int __devm_rtc_register_device(struct module * owner, struct rtc_device * rtc)
```

```json
{
  "name": "__devm_rtc_register_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devm_rtc_register_device",
      "external": true,
      "loc": "drivers/rtc/class.c:389",
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
      "addr": 18446744071597760747,
      "name": "__devm_rtc_register_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593355568,
      "name": "__devm_rtc_register_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __devm_rtc_register_device(struct module * owner, struct rtc_device * rtc)
```
</details>
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
