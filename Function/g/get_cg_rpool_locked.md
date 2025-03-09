# Function: <code>get_cg_rpool_locked</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073360,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:132",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073360,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126112,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:132",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126112,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185824,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:132",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185824,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580233120,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:132",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233120,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580283888,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283888,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332112,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332112,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580404912,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580404912,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580392208,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580392208,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580395168,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395168,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557296,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557296,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756528,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756528,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034832,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034832,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123136,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123136,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581221488,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221488,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491594336,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491594336,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225553844,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225553844,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284578240,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284578240,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271999898,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271999898,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580300912,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300912,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580248256,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248256,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580292160,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292160,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```

```json
{
  "name": "get_cg_rpool_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580346512,
      "name": "get_cg_rpool_locked",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346512,
      "name": "get_cg_rpool_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct rdmacg_resource_pool * get_cg_rpool_locked(struct rdma_cgroup * cg, struct rdmacg_device * device)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
