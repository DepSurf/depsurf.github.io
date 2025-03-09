# Function: <code>_mmc_cache_enabled</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool _mmc_cache_enabled(struct mmc_host * host)
```

```json
{
  "name": "_mmc_cache_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588878032,
      "name": "_mmc_cache_enabled",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2032",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878032,
      "name": "_mmc_cache_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
bool _mmc_cache_enabled(struct mmc_host * host)
```

```json
{
  "name": "_mmc_cache_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589581429,
      "name": "_mmc_cache_enabled",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2036",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580464,
      "name": "_mmc_cache_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
bool _mmc_cache_enabled(struct mmc_host * host)
```

```json
{
  "name": "_mmc_cache_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591076357,
      "name": "_mmc_cache_enabled",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2071",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591075744,
      "name": "_mmc_cache_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
bool _mmc_cache_enabled(struct mmc_host * host)
```

```json
{
  "name": "_mmc_cache_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592792405,
      "name": "_mmc_cache_enabled",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2071",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592791696,
      "name": "_mmc_cache_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
bool _mmc_cache_enabled(struct mmc_host * host)
```

```json
{
  "name": "_mmc_cache_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593228981,
      "name": "_mmc_cache_enabled",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2071",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593228272,
      "name": "_mmc_cache_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
bool _mmc_cache_enabled(struct mmc_host * host)
```

```json
{
  "name": "_mmc_cache_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593989214,
      "name": "_mmc_cache_enabled",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:2092",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593983168,
      "name": "_mmc_cache_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool _mmc_cache_enabled(struct mmc_host * host)
```
</details>
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
