# Function: <code>rproc_coredump_add_custom_segment</code>

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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588231216,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1534",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231216,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589107792,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1563",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589107792,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589114304,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:78",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114304,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589004144,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:78",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589004144,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718496,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:78",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718496,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591226512,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:78",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591226512,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592975424,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:78",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592975424,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593426080,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:78",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593426080,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594172160,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:79",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594172160,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501687624,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1534",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501687624,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234213140,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1534",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234213140,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295122816,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1534",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295122816,
      "name": "rproc_coredump_add_custom_segment",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587842912,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1534",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587842912,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```

```json
{
  "name": "rproc_coredump_add_custom_segment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588303552,
      "name": "rproc_coredump_add_custom_segment",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1534",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303552,
      "name": "rproc_coredump_add_custom_segment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn</code> ➡️ <code>void (*)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t) dumpfn</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc * rproc, dma_addr_t da, size_t size, void (*)(struct rproc *, struct rproc_dump_segment *, void *) dumpfn, void * priv)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
