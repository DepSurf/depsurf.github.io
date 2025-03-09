# Function: <code>edac_ce_error</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586563040,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:963",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587030560,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:968",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587328471,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:970",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587506807,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:963",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587780732,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:959",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587985436,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_ce_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:900",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588840944,
      "name": "edac_ce_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071588844603,
      "name": "edac_ce_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_ce_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:904",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588856784,
      "name": "edac_ce_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071591594096,
      "name": "edac_ce_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void edac_ce_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:904",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588743536,
      "name": "edac_ce_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071591537020,
      "name": "edac_ce_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void edac_ce_error(struct edac_raw_error_desc * e)
```

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:907",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589434000,
      "name": "edac_ce_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071592650872,
      "name": "edac_ce_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590912544,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:832",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592610448,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:831",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593041056,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:831",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593792496,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:832",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501230752,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233733780,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294759048,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277925242,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587616412,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587384428,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587941580,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_ce_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588056860,
      "name": "edac_ce_error",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:952",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void edac_ce_error(struct edac_raw_error_desc * e)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void edac_ce_error(struct edac_raw_error_desc * e)
```
</details>
</li>
</ul>
