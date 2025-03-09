# Function: <code>_mmc_flush_cache</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int _mmc_flush_cache(struct mmc_host * host)
```

```json
{
  "name": "_mmc_flush_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_mmc_flush_cache",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2045",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_hw_reset",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589581424,
      "name": "_mmc_flush_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071592662754,
      "name": "_mmc_flush_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int _mmc_flush_cache(struct mmc_host * host)
```

```json
{
  "name": "_mmc_flush_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_mmc_flush_cache",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2080",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_hw_reset",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591076352,
      "name": "_mmc_flush_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071594547855,
      "name": "_mmc_flush_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int _mmc_flush_cache(struct mmc_host * host)
```

```json
{
  "name": "_mmc_flush_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592792400,
      "name": "_mmc_flush_cache",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2080",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_hw_reset",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592792400,
      "name": "_mmc_flush_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int _mmc_flush_cache(struct mmc_host * host)
```

```json
{
  "name": "_mmc_flush_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593228976,
      "name": "_mmc_flush_cache",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2080",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_hw_reset",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593228976,
      "name": "_mmc_flush_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int _mmc_flush_cache(struct mmc_host * host)
```

```json
{
  "name": "_mmc_flush_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_mmc_flush_cache",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2101",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_hw_reset",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593989152,
      "name": "_mmc_flush_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071597771180,
      "name": "_mmc_flush_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int _mmc_flush_cache(struct mmc_host * host)
```
</details>
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
