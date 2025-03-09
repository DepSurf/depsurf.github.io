# Function: <code>ns_get_path_cb</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818368,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818368,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905360,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905360,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582030912,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030912,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582108848,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108848,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582345733,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:109",
      "file": "fs/nsfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_get_path"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345648,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582397374,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:109",
      "file": "fs/nsfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_get_path"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397280,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582424654,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:109",
      "file": "fs/nsfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_get_path"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582424560,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582747454,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:109",
      "file": "fs/nsfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_get_path"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747360,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583294622,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:109",
      "file": "fs/nsfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_get_path"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294528,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583878942,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:109",
      "file": "fs/nsfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_get_path"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878832,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584100702,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:110",
      "file": "fs/nsfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_get_path"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100592,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584316798,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:107",
      "file": "fs/nsfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_get_path"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316688,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493648512,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493648512,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227183456,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227183456,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287240624,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287240624,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273280404,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273280404,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077584,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077584,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015104,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015104,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582068864,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068864,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```

```json
{
  "name": "ns_get_path_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140624,
      "name": "ns_get_path_cb",
      "external": true,
      "loc": "fs/nsfs.c:106",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_info_fill",
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill",
        "fs/nsfs.c:ns_get_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140624,
      "name": "ns_get_path_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void * ns_get_path_cb(struct path * path, ns_get_path_helper_t * ns_get_cb, void * private_data)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>int</code>
</li>
</ul>
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
