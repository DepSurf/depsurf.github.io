# Function: <code>of_gen_pool_get</code>

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
struct gen_pool * of_gen_pool_get(struct device_node * np, const char * propname, int index)
```

```json
{
  "name": "of_gen_pool_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496201696,
      "name": "of_gen_pool_get",
      "external": true,
      "loc": "lib/genalloc.c:871",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/altera_edac.c:ocram_alloc_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496201696,
      "name": "of_gen_pool_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct gen_pool * of_gen_pool_get(struct device_node * np, const char * propname, int index)
```

```json
{
  "name": "of_gen_pool_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229525904,
      "name": "of_gen_pool_get",
      "external": true,
      "loc": "lib/genalloc.c:871",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init",
        "sound/core/memalloc.c:snd_dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229525904,
      "name": "of_gen_pool_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct gen_pool * of_gen_pool_get(struct device_node * np, const char * propname, int index)
```

```json
{
  "name": "of_gen_pool_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290488256,
      "name": "of_gen_pool_get",
      "external": true,
      "loc": "lib/genalloc.c:871",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290488256,
      "name": "of_gen_pool_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
struct gen_pool * of_gen_pool_get(struct device_node * np, const char * propname, int index)
```

```json
{
  "name": "of_gen_pool_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275254990,
      "name": "of_gen_pool_get",
      "external": true,
      "loc": "lib/genalloc.c:871",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275254990,
      "name": "of_gen_pool_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct gen_pool * of_gen_pool_get(struct device_node * np, const char * propname, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct gen_pool * of_gen_pool_get(struct device_node * np, const char * propname, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct gen_pool * of_gen_pool_get(struct device_node * np, const char * propname, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct gen_pool * of_gen_pool_get(struct device_node * np, const char * propname, int index)
```
</details>
</li>
</ul>
