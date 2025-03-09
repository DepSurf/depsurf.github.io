# Function: <code>dma_buf_unpin</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment * attach)
```

```json
{
  "name": "dma_buf_unpin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587387004,
      "name": "dma_buf_unpin",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:833",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment",
        "drivers/dma-buf/dma-buf.c:dma_buf_map_attachment",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383200,
      "name": "dma_buf_unpin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment * attach)
```

```json
{
  "name": "dma_buf_unpin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587455068,
      "name": "dma_buf_unpin",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:846",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment",
        "drivers/dma-buf/dma-buf.c:dma_buf_map_attachment",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451168,
      "name": "dma_buf_unpin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void dma_buf_unpin(struct dma_buf_attachment * attach)
```

```json
{
  "name": "dma_buf_unpin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587332928,
      "name": "dma_buf_unpin",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:899",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587332928,
      "name": "dma_buf_unpin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void dma_buf_unpin(struct dma_buf_attachment * attach)
```

```json
{
  "name": "dma_buf_unpin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904620,
      "name": "dma_buf_unpin",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:903",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899840,
      "name": "dma_buf_unpin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void dma_buf_unpin(struct dma_buf_attachment * attach)
```

```json
{
  "name": "dma_buf_unpin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589255112,
      "name": "dma_buf_unpin",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:895",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589249552,
      "name": "dma_buf_unpin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void dma_buf_unpin(struct dma_buf_attachment * attach)
```

```json
{
  "name": "dma_buf_unpin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590809280,
      "name": "dma_buf_unpin",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:1069",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590809280,
      "name": "dma_buf_unpin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void dma_buf_unpin(struct dma_buf_attachment * attach)
```

```json
{
  "name": "dma_buf_unpin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591150304,
      "name": "dma_buf_unpin",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:1069",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591150304,
      "name": "dma_buf_unpin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void dma_buf_unpin(struct dma_buf_attachment * attach)
```

```json
{
  "name": "dma_buf_unpin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591496416,
      "name": "dma_buf_unpin",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:1064",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591496416,
      "name": "dma_buf_unpin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment * attach)
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
