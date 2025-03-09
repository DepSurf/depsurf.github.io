# Function: <code>pwm_lpss_prepare_enable</code>

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
int pwm_lpss_prepare_enable(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_prepare_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585415051,
      "name": "pwm_lpss_prepare_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:128",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585414976,
      "name": "pwm_lpss_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071591390715,
      "name": "pwm_lpss_prepare_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pwm_lpss_prepare_enable(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_prepare_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585295579,
      "name": "pwm_lpss_prepare_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:128",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585295504,
      "name": "pwm_lpss_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    },
    {
      "addr": 18446744071591332970,
      "name": "pwm_lpss_prepare_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pwm_lpss_prepare_enable(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_prepare_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pwm_lpss_prepare_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:128",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585752336,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071592357747,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585752832,
      "name": "pwm_lpss_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071592357860,
      "name": "pwm_lpss_prepare_enable.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pwm_lpss_prepare_enable(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_prepare_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pwm_lpss_prepare_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:128",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935728,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071594220127,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071586936240,
      "name": "pwm_lpss_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071594220239,
      "name": "pwm_lpss_prepare_enable.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pwm_lpss_prepare_enable(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_prepare_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588093072,
      "name": "pwm_lpss_prepare_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:165",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092560,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071596207700,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071588093072,
      "name": "pwm_lpss_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pwm_lpss_prepare_enable(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_prepare_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588367504,
      "name": "pwm_lpss_prepare_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:165",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366976,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071596732828,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071588367504,
      "name": "pwm_lpss_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pwm_lpss_prepare_enable(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_prepare_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588662272,
      "name": "pwm_lpss_prepare_enable",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:165",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588661744,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071597641284,
      "name": "pwm_lpss_prepare_enable.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071588662272,
      "name": "pwm_lpss_prepare_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int pwm_lpss_prepare_enable(struct pwm_lpss_chip * lpwm, struct pwm_device * pwm, const struct pwm_state * state)
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
