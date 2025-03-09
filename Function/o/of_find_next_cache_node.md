# Function: <code>of_find_next_cache_node</code>

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
struct device_node * of_find_next_cache_node(const struct device_node * np)
```

```json
{
  "name": "of_find_next_cache_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501609016,
      "name": "of_find_next_cache_node",
      "external": true,
      "loc": "drivers/of/base.c:2194",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/base.c:of_find_last_cache_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501609016,
      "name": "of_find_next_cache_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct device_node * of_find_next_cache_node(const struct device_node * np)
```

```json
{
  "name": "of_find_next_cache_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234133124,
      "name": "of_find_next_cache_node",
      "external": true,
      "loc": "drivers/of/base.c:2194",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_init",
        "drivers/of/base.c:of_find_last_cache_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234133124,
      "name": "of_find_next_cache_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct device_node * of_find_next_cache_node(const struct device_node * np)
```

```json
{
  "name": "of_find_next_cache_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295035472,
      "name": "of_find_next_cache_node",
      "external": true,
      "loc": "drivers/of/base.c:2194",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online",
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online",
        "arch/powerpc/kernel/setup_64.c:initialize_cache_info",
        "arch/powerpc/kernel/setup_64.c:initialize_cache_info",
        "arch/powerpc/kernel/smp.c:cpu_to_l2cache",
        "drivers/of/base.c:of_find_last_cache_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295035472,
      "name": "of_find_next_cache_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct device_node * of_find_next_cache_node(const struct device_node * np)
```

```json
{
  "name": "of_find_next_cache_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278074490,
      "name": "of_find_next_cache_node",
      "external": true,
      "loc": "drivers/of/base.c:2194",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves",
        "arch/riscv/kernel/cacheinfo.c:_init_cache_level",
        "drivers/of/base.c:of_find_last_cache_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278074490,
      "name": "of_find_next_cache_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct device_node * of_find_next_cache_node(const struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_find_next_cache_node(const struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * of_find_next_cache_node(const struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * of_find_next_cache_node(const struct device_node * np)
```
</details>
</li>
</ul>
