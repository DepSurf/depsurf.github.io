# Function: <code>sync_pt_create</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585317857,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:167",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585405405,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:167",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585835978,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:246",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586083017,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:246",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586227289,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:245",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586471047,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:236",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586618839,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
```

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587413424,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413424,
      "name": "sync_pt_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
```

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587483152,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587483152,
      "name": "sync_pt_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
```

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587364336,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364336,
      "name": "sync_pt_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
```

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587931312,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587931312,
      "name": "sync_pt_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
```

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589285024,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589285024,
      "name": "sync_pt_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
```

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590846800,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590846800,
      "name": "sync_pt_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
```

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591189344,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591189344,
      "name": "sync_pt_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
```

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591535936,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:271",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591535936,
      "name": "sync_pt_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499509232,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231978276,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292796968,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276719706,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586309319,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586150679,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586566807,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_pt_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586679095,
      "name": "sync_pt_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:233",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sync_pt * sync_pt_create(struct sync_timeline * obj, unsigned int value)
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
