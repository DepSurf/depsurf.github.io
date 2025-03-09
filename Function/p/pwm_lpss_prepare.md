# Function: <code>pwm_lpss_prepare</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584163184,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:94",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163184,
      "name": "pwm_lpss_prepare.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584251152,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:85",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584252320,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss-platform.c:79",
      "file": "drivers/pwm/pwm-lpss-platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584251152,
      "name": "pwm_lpss_prepare.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071584252320,
      "name": "pwm_lpss_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584444272,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:82",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584445488,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss-platform.c:76",
      "file": "drivers/pwm/pwm-lpss-platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584444272,
      "name": "pwm_lpss_prepare.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071584445488,
      "name": "pwm_lpss_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581040,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:82",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584582240,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss-platform.c:76",
      "file": "drivers/pwm/pwm-lpss-platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581040,
      "name": "pwm_lpss_prepare.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071584582240,
      "name": "pwm_lpss_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585257200,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:82",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply"
      ]
    },
    {
      "addr": 18446744071585258096,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss-platform.c:76",
      "file": "drivers/pwm/pwm-lpss-platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257200,
      "name": "pwm_lpss_prepare.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071585258096,
      "name": "pwm_lpss_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585415051,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:87",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585295579,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:87",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585752384,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:87",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586935776,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:87",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588092608,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:124",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588367024,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:124",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588661792,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:124",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584531200,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:82",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584532400,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss-platform.c:76",
      "file": "drivers/pwm/pwm-lpss-platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531200,
      "name": "pwm_lpss_prepare.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071584532400,
      "name": "pwm_lpss_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```

```json
{
  "name": "pwm_lpss_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584638976,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:82",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584640176,
      "name": "pwm_lpss_prepare",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss-platform.c:76",
      "file": "drivers/pwm/pwm-lpss-platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638976,
      "name": "pwm_lpss_prepare.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071584640176,
      "name": "pwm_lpss_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```
</details>
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
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, int duty_ns, int period_ns)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
