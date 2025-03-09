# Function: <code>dma_resv_iter_next_unlocked</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_fence * dma_resv_iter_next_unlocked(struct dma_resv_iter * cursor)
```

```json
{
  "name": "dma_resv_iter_next_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589267776,
      "name": "dma_resv_iter_next_unlocked",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:429",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589267776,
      "name": "dma_resv_iter_next_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct dma_fence * dma_resv_iter_next_unlocked(struct dma_resv_iter * cursor)
```

```json
{
  "name": "dma_resv_iter_next_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590832288,
      "name": "dma_resv_iter_next_unlocked",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:435",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590832288,
      "name": "dma_resv_iter_next_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct dma_fence * dma_resv_iter_next_unlocked(struct dma_resv_iter * cursor)
```

```json
{
  "name": "dma_resv_iter_next_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591174320,
      "name": "dma_resv_iter_next_unlocked",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:435",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_set_deadline",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591174320,
      "name": "dma_resv_iter_next_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct dma_fence * dma_resv_iter_next_unlocked(struct dma_resv_iter * cursor)
```

```json
{
  "name": "dma_resv_iter_next_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591520320,
      "name": "dma_resv_iter_next_unlocked",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:435",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_set_deadline",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591520320,
      "name": "dma_resv_iter_next_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct dma_fence * dma_resv_iter_next_unlocked(struct dma_resv_iter * cursor)
```
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
