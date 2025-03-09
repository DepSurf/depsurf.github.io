# Function: <code>dma_fence_unwrap_next</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_fence_unwrap_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589281323,
      "name": "dma_fence_unwrap_next",
      "external": false,
      "loc": "include/linux/dma-fence-unwrap.h:68",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dma_fence * dma_fence_unwrap_next(struct dma_fence_unwrap * cursor)
```

```json
{
  "name": "dma_fence_unwrap_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590829008,
      "name": "dma_fence_unwrap_next",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-unwrap.c:48",
      "file": "drivers/dma-buf/dma-fence-unwrap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590829008,
      "name": "dma_fence_unwrap_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dma_fence * dma_fence_unwrap_next(struct dma_fence_unwrap * cursor)
```

```json
{
  "name": "dma_fence_unwrap_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591170960,
      "name": "dma_fence_unwrap_next",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-unwrap.c:48",
      "file": "drivers/dma-buf/dma-fence-unwrap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591170960,
      "name": "dma_fence_unwrap_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dma_fence * dma_fence_unwrap_next(struct dma_fence_unwrap * cursor)
```

```json
{
  "name": "dma_fence_unwrap_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591516944,
      "name": "dma_fence_unwrap_next",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-unwrap.c:48",
      "file": "drivers/dma-buf/dma-fence-unwrap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591516944,
      "name": "dma_fence_unwrap_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct dma_fence * dma_fence_unwrap_next(struct dma_fence_unwrap * cursor)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
