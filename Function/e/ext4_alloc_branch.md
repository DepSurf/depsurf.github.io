# Function: <code>ext4_alloc_branch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581831480,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:322",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582027512,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:322",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582117640,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:322",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581956993,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:322",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582106049,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:323",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582294409,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:323",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582393167,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:323",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557856,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557856,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582658800,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582658800,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970560,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970560,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583046160,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583046160,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072080,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072080,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583410272,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410272,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1131
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925696,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925696,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1151
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584551840,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:328",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584551840,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1163
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780560,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:328",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780560,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1177
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585013008,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:328",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585013008,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1192
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494311856,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494311856,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227747516,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227747516,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288036428,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273754848,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582627536,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627536,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582564704,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564704,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582617392,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582617392,
      "name": "ext4_alloc_branch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_branch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582703871,
      "name": "ext4_alloc_branch",
      "external": false,
      "loc": "fs/ext4/indirect.c:321",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
int ext4_alloc_branch(handle_t * handle, struct ext4_allocation_request * ar, int indirect_blks, ext4_lblk_t * offsets, Indirect * branch)
```
</details>
</li>
</ul>
