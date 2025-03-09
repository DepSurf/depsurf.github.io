# Function: <code>bpf_selem_unlink_map</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bpf_selem_unlink_map(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137824,
      "name": "bpf_selem_unlink_map",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:166",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137824,
      "name": "bpf_selem_unlink_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void bpf_selem_unlink_map(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094224,
      "name": "bpf_selem_unlink_map",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:167",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094224,
      "name": "bpf_selem_unlink_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void bpf_selem_unlink_map(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_selem_unlink_map",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:167",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186581,
      "name": "bpf_selem_unlink_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071581323472,
      "name": "bpf_selem_unlink_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void bpf_selem_unlink_map(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_selem_unlink_map",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:196",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960905,
      "name": "bpf_selem_unlink_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071581626896,
      "name": "bpf_selem_unlink_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void bpf_selem_unlink_map(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_selem_unlink_map",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:205",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_unlink_nolock",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596021532,
      "name": "bpf_selem_unlink_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071582013664,
      "name": "bpf_selem_unlink_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void bpf_selem_unlink_map(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_selem_unlink_map",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:377",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203472,
      "name": "bpf_selem_unlink_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071596543166,
      "name": "bpf_selem_unlink_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void bpf_selem_unlink_map(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_selem_unlink_map",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:377",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352704,
      "name": "bpf_selem_unlink_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071597446259,
      "name": "bpf_selem_unlink_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void bpf_selem_unlink_map(struct bpf_local_storage_elem * selem)
```
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
