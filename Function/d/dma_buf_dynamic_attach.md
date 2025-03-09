# Function: <code>dma_buf_dynamic_attach</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
```

```json
{
  "name": "dma_buf_dynamic_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587387984,
      "name": "dma_buf_dynamic_attach",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:676",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587387984,
      "name": "dma_buf_dynamic_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
```

```json
{
  "name": "dma_buf_dynamic_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587456048,
      "name": "dma_buf_dynamic_attach",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:689",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587456048,
      "name": "dma_buf_dynamic_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
```

```json
{
  "name": "dma_buf_dynamic_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587335760,
      "name": "dma_buf_dynamic_attach",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:720",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587335760,
      "name": "dma_buf_dynamic_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
```

```json
{
  "name": "dma_buf_dynamic_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_buf_dynamic_attach",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:724",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592524442,
      "name": "dma_buf_dynamic_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587902272,
      "name": "dma_buf_dynamic_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
```

```json
{
  "name": "dma_buf_dynamic_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_buf_dynamic_attach",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:716",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594395845,
      "name": "dma_buf_dynamic_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589253344,
      "name": "dma_buf_dynamic_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
```

```json
{
  "name": "dma_buf_dynamic_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_buf_dynamic_attach",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:894",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596259009,
      "name": "dma_buf_dynamic_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590813600,
      "name": "dma_buf_dynamic_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
```

```json
{
  "name": "dma_buf_dynamic_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_buf_dynamic_attach",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:894",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596787118,
      "name": "dma_buf_dynamic_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591154672,
      "name": "dma_buf_dynamic_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
```

```json
{
  "name": "dma_buf_dynamic_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_buf_dynamic_attach",
      "external": true,
      "loc": "drivers/dma-buf/dma-buf.c:889",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597696074,
      "name": "dma_buf_dynamic_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591500512,
      "name": "dma_buf_dynamic_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
struct dma_buf_attachment * dma_buf_dynamic_attach(struct dma_buf * dmabuf, struct device * dev, const struct dma_buf_attach_ops * importer_ops, void * importer_priv)
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
