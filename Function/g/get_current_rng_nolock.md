# Function: <code>get_current_rng_nolock</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_current_rng_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586684597,
      "name": "get_current_rng_nolock",
      "external": false,
      "loc": "drivers/char/hw_random/core.c:114",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_attr_current_show",
        "drivers/char/hw_random/core.c:hwrng_attr_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hwrng * get_current_rng_nolock()
```

```json
{
  "name": "get_current_rng_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586791536,
      "name": "get_current_rng_nolock",
      "external": false,
      "loc": "drivers/char/hw_random/core.c:114",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_attr_current_show",
        "drivers/char/hw_random/core.c:hwrng_attr_current_store",
        "drivers/char/hw_random/core.c:hwrng_attr_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790096,
      "name": "get_current_rng_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hwrng * get_current_rng_nolock()
```

```json
{
  "name": "get_current_rng_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586671936,
      "name": "get_current_rng_nolock",
      "external": false,
      "loc": "drivers/char/hw_random/core.c:114",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_attr_current_show",
        "drivers/char/hw_random/core.c:hwrng_attr_current_store",
        "drivers/char/hw_random/core.c:hwrng_attr_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670256,
      "name": "get_current_rng_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hwrng * get_current_rng_nolock()
```

```json
{
  "name": "get_current_rng_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587220176,
      "name": "get_current_rng_nolock",
      "external": false,
      "loc": "drivers/char/hw_random/core.c:114",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:rng_current_show",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587218496,
      "name": "get_current_rng_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hwrng * get_current_rng_nolock()
```

```json
{
  "name": "get_current_rng_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588526354,
      "name": "get_current_rng_nolock",
      "external": false,
      "loc": "drivers/char/hw_random/core.c:114",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:rng_quality_show",
        "drivers/char/hw_random/core.c:rng_current_show",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588524144,
      "name": "get_current_rng_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hwrng * get_current_rng_nolock()
```

```json
{
  "name": "get_current_rng_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589970104,
      "name": "get_current_rng_nolock",
      "external": false,
      "loc": "drivers/char/hw_random/core.c:125",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:rng_quality_show",
        "drivers/char/hw_random/core.c:rng_current_show",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967632,
      "name": "get_current_rng_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hwrng * get_current_rng_nolock()
```

```json
{
  "name": "get_current_rng_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590279704,
      "name": "get_current_rng_nolock",
      "external": false,
      "loc": "drivers/char/hw_random/core.c:125",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:rng_quality_show",
        "drivers/char/hw_random/core.c:rng_current_show",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590277232,
      "name": "get_current_rng_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hwrng * get_current_rng_nolock()
```

```json
{
  "name": "get_current_rng_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590620808,
      "name": "get_current_rng_nolock",
      "external": false,
      "loc": "drivers/char/hw_random/core.c:127",
      "file": "drivers/char/hw_random/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn"
      ],
      "caller_func": [
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:rng_quality_show",
        "drivers/char/hw_random/core.c:rng_current_show",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_current_store",
        "drivers/char/hw_random/core.c:rng_dev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590618176,
      "name": "get_current_rng_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
struct hwrng * get_current_rng_nolock()
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
