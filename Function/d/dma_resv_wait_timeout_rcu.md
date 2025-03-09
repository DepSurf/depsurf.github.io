# Function: <code>dma_resv_wait_timeout_rcu</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611856,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611856,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587402144,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:532",
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
      "addr": 18446744071587402144,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587470384,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:532",
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
      "addr": 18446744071587470384,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 891
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587352192,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:532",
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
      "addr": 18446744071587352192,
      "name": "dma_resv_wait_timeout_rcu",
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499500440,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499500440,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231971008,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231971008,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292787040,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292787040,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276713852,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276713852,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586302336,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586302336,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586143712,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586143712,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586559824,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586559824,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```

```json
{
  "name": "dma_resv_wait_timeout_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671120,
      "name": "dma_resv_wait_timeout_rcu",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:499",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671120,
      "name": "dma_resv_wait_timeout_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv * obj, bool wait_all, bool intr, long unsigned int timeout)
```
</details>
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
