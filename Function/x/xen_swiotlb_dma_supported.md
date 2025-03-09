# Function: <code>xen_swiotlb_dma_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583908848,
      "name": "xen_swiotlb_dma_supported",
      "external": true,
      "loc": "drivers/xen/swiotlb-xen.c:665",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908848,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584239699,
      "name": "xen_swiotlb_dma_supported",
      "external": true,
      "loc": "drivers/xen/swiotlb-xen.c:665",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239456,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584421139,
      "name": "xen_swiotlb_dma_supported",
      "external": true,
      "loc": "drivers/xen/swiotlb-xen.c:667",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420896,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584505040,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:659",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505040,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584915056,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:659",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915056,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585147536,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:645",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585147536,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257392,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:633",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257392,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585466848,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:545",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585466848,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607520,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:537",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607520,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586330288,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:543",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330288,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586448224,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:561",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448224,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586332208,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:548",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586332208,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586852032,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:546",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852032,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588138816,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:382",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588138816,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589528448,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:382",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589528448,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589829520,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:382",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589829520,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590166528,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:382",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590166528,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498274328,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:537",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498274328,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585369168,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:537",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369168,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557920,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:537",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557920,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```

```json
{
  "name": "xen_swiotlb_dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585665872,
      "name": "xen_swiotlb_dma_supported",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:537",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665872,
      "name": "xen_swiotlb_dma_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
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
int xen_swiotlb_dma_supported(struct device * hwdev, u64 mask)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
