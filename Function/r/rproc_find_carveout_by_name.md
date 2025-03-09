# Function: <code>rproc_find_carveout_by_name</code>

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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588234080,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:244",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588234080,
      "name": "rproc_find_carveout_by_name",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589111072,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:248",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589111072,
      "name": "rproc_find_carveout_by_name",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589108128,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:248",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589108128,
      "name": "rproc_find_carveout_by_name",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588997552,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:251",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588997552,
      "name": "rproc_find_carveout_by_name",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589711744,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:253",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589711744,
      "name": "rproc_find_carveout_by_name",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591219232,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:253",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591219232,
      "name": "rproc_find_carveout_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592970480,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592970480,
      "name": "rproc_find_carveout_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593420864,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593420864,
      "name": "rproc_find_carveout_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594166816,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:252",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594166816,
      "name": "rproc_find_carveout_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501691440,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:244",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501691440,
      "name": "rproc_find_carveout_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234216528,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:244",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234216528,
      "name": "rproc_find_carveout_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295125952,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:244",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295125952,
      "name": "rproc_find_carveout_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845776,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:244",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845776,
      "name": "rproc_find_carveout_by_name",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```

```json
{
  "name": "rproc_find_carveout_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588306416,
      "name": "rproc_find_carveout_by_name",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:244",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588306416,
      "name": "rproc_find_carveout_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
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
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct rproc_mem_entry * rproc_find_carveout_by_name(struct rproc * rproc, const char * name, void (anon))
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
