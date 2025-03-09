# Function: <code>sync_timeline_put</code>

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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585318748,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:123",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sync_timeline_put(struct sync_timeline * obj)
```

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585404896,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:123",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585404896,
      "name": "sync_timeline_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585835575,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:123",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586082788,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:123",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586226852,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:123",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586470645,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586619362,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587412705,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587482785,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587365057,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587932033,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589283976,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590845864,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591187704,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591534680,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:135",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void sync_timeline_put(struct sync_timeline * obj)
```

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499506656,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499506656,
      "name": "sync_timeline_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void sync_timeline_put(struct sync_timeline * obj)
```

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231976864,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231976864,
      "name": "sync_timeline_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void sync_timeline_put(struct sync_timeline * obj)
```

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292794672,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292794672,
      "name": "sync_timeline_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276720208,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586309842,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586151196,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586567330,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
  "name": "sync_timeline_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586679605,
      "name": "sync_timeline_put",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:114",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void sync_timeline_put(struct sync_timeline * obj)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void sync_timeline_put(struct sync_timeline * obj)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void sync_timeline_put(struct sync_timeline * obj)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void sync_timeline_put(struct sync_timeline * obj)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void sync_timeline_put(struct sync_timeline * obj)
```
</details>
</li>
</ul>
