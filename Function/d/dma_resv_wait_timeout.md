# Function: <code>dma_resv_wait_timeout</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int dma_resv_wait_timeout(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918544,
      "name": "dma_resv_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:512",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918544,
      "name": "dma_resv_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
long int dma_resv_wait_timeout(struct dma_resv * obj, enum dma_resv_usage usage, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589268880,
      "name": "dma_resv_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:659",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access",
        "drivers/dma-buf/dma-buf.c:__map_dma_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589268880,
      "name": "dma_resv_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int dma_resv_wait_timeout(struct dma_resv * obj, enum dma_resv_usage usage, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590832480,
      "name": "dma_resv_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:665",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access",
        "drivers/dma-buf/dma-buf.c:__map_dma_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590832480,
      "name": "dma_resv_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int dma_resv_wait_timeout(struct dma_resv * obj, enum dma_resv_usage usage, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591174736,
      "name": "dma_resv_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:670",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access",
        "drivers/dma-buf/dma-buf.c:__map_dma_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591174736,
      "name": "dma_resv_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int dma_resv_wait_timeout(struct dma_resv * obj, enum dma_resv_usage usage, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591520736,
      "name": "dma_resv_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:670",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access",
        "drivers/dma-buf/dma-buf.c:__map_dma_buf",
        "drivers/gpu/drm/drm_gem.c:drm_gem_dma_resv_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591520736,
      "name": "dma_resv_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int dma_resv_wait_timeout(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum dma_resv_usage usage</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wait_all</code>
</li>
</ul>
</details>
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
