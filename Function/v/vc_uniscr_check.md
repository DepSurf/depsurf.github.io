# Function: <code>vc_uniscr_check</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585425264,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585425264,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585657411,
      "name": "vc_uniscr_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585639808,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585781104,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781104,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513776,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:512",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513776,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626976,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:505",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626976,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586511168,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:505",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586511168,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587046064,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:501",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587046064,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588347680,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:501",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588347680,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589768544,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:501",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589768544,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590073440,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:483",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590073440,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590412576,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:482",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590412576,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498498856,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498498856,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231152952,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231152952,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291691616,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291691616,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276129278,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276129278,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585542096,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585542096,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585411920,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585411920,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585731504,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731504,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int vc_uniscr_check(struct vc_data * vc)
```

```json
{
  "name": "vc_uniscr_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585839520,
      "name": "vc_uniscr_check",
      "external": true,
      "loc": "drivers/tty/vt/vt.c:506",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585839520,
      "name": "vc_uniscr_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int vc_uniscr_check(struct vc_data * vc)
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
