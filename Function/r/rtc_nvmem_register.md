# Function: <code>rtc_nvmem_register</code>

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
void rtc_nvmem_register(struct rtc_device * rtc)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586296960,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:87",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:__rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586296960,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void rtc_nvmem_register(struct rtc_device * rtc)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586760480,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:87",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/class.c:__rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760480,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587032432,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:85",
      "file": "drivers/rtc/nvmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032432,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192480,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:83",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192480,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587457856,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457856,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587660976,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587660976,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588528288,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588528288,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500814416,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500814416,
      "name": "rtc_nvmem_register",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233320988,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-omap.c:omap_rtc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233320988,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294272864,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294272864,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277632850,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277632850,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587344736,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344736,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113040,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113040,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587612224,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587612224,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
```

```json
{
  "name": "rtc_nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587723456,
      "name": "rtc_nvmem_register",
      "external": true,
      "loc": "drivers/rtc/nvmem.c:80",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723456,
      "name": "rtc_nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void rtc_nvmem_register(struct rtc_device * rtc)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nvmem_config * nvmem_config</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
int rtc_nvmem_register(struct rtc_device * rtc, struct nvmem_config * nvmem_config)
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
