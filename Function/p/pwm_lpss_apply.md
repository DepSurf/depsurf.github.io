# Function: <code>pwm_lpss_apply</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584163488,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:132",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163488,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584251680,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:127",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584251680,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584444768,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:124",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584444768,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581536,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:124",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581536,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257392,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:124",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257392,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585415456,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:148",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415456,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296000,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:148",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296000,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:148",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585752896,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071592357889,
      "name": "pwm_lpss_apply.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:148",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586936304,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071594220268,
      "name": "pwm_lpss_apply.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:185",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093184,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071596207784,
      "name": "pwm_lpss_apply.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:185",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588367616,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071596732912,
      "name": "pwm_lpss_apply.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:185",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588662384,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071597641368,
      "name": "pwm_lpss_apply.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584531696,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:124",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531696,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```

```json
{
  "name": "pwm_lpss_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584639472,
      "name": "pwm_lpss_apply",
      "external": false,
      "loc": "drivers/pwm/pwm-lpss.c:124",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639472,
      "name": "pwm_lpss_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, struct pwm_state * state)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct pwm_state * state</code> ➡️ <code>const struct pwm_state * state</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
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
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int pwm_lpss_apply(struct pwm_chip * chip, struct pwm_device * pwm, const struct pwm_state * state)
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
