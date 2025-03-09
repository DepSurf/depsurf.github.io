# Function: <code>dma_resv_get_fences</code>

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
int dma_resv_get_fences(struct dma_resv * obj, struct dma_fence * * pfence_excl, unsigned int * pshared_count, struct dma_fence * * * pshared)
```

```json
{
  "name": "dma_resv_get_fences",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587917504,
      "name": "dma_resv_get_fences",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:411",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917504,
      "name": "dma_resv_get_fences",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
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
int dma_resv_get_fences(struct dma_resv * obj, enum dma_resv_usage usage, unsigned int * num_fences, struct dma_fence * * * fences)
```

```json
{
  "name": "dma_resv_get_fences",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_resv_get_fences",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:555",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594396116,
      "name": "dma_resv_get_fences.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589270496,
      "name": "dma_resv_get_fences",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int dma_resv_get_fences(struct dma_resv * obj, enum dma_resv_usage usage, unsigned int * num_fences, struct dma_fence * * * fences)
```

```json
{
  "name": "dma_resv_get_fences",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_resv_get_fences",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:561",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596259392,
      "name": "dma_resv_get_fences.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071590834240,
      "name": "dma_resv_get_fences",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int dma_resv_get_fences(struct dma_resv * obj, enum dma_resv_usage usage, unsigned int * num_fences, struct dma_fence * * * fences)
```

```json
{
  "name": "dma_resv_get_fences",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_resv_get_fences",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:561",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596787501,
      "name": "dma_resv_get_fences.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071591176464,
      "name": "dma_resv_get_fences",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int dma_resv_get_fences(struct dma_resv * obj, enum dma_resv_usage usage, unsigned int * num_fences, struct dma_fence * * * fences)
```

```json
{
  "name": "dma_resv_get_fences",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_resv_get_fences",
      "external": true,
      "loc": "drivers/dma-buf/dma-resv.c:561",
      "file": "drivers/dma-buf/dma-resv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597696457,
      "name": "dma_resv_get_fences.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071591522464,
      "name": "dma_resv_get_fences",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int dma_resv_get_fences(struct dma_resv * obj, struct dma_fence * * pfence_excl, unsigned int * pshared_count, struct dma_fence * * * pshared)
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
<b>Param added. </b>
<code>unsigned int * num_fences</code>
</li>
<li>
<b>Param added. </b>
<code>struct dma_fence * * * fences</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dma_fence * * pfence_excl</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * pshared_count</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dma_fence * * * pshared</code>
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
