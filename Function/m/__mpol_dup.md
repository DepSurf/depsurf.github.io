# Function: <code>__mpol_dup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820176,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2088",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:mpol_set_shared_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820176,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945600,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2105",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:do_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945600,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581017824,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2099",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:SYSC_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017824,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063696,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2004",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:SYSC_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063696,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174880,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2066",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:SYSC_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174880,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319552,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2123",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319552,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403728,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2162",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403728,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515856,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2183",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515856,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580320,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2222",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580320,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792288,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2322",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:vma_replace_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792288,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840112,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2297",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:vma_replace_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840112,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581870944,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2302",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:mbind_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581870944,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162656,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2220",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:mbind_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162656,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619056,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2394",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:mbind_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619056,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583142928,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2409",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:mbind_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583142928,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353072,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2420",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:vma_replace_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353072,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583588976,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2322",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:sp_alloc",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:mbind_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588976,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493018048,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2222",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493018048,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286445584,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2222",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:do_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286445584,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549056,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2222",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549056,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490704,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2222",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490704,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581540368,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2222",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581540368,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```

```json
{
  "name": "__mpol_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605408,
      "name": "__mpol_dup",
      "external": true,
      "loc": "mm/mempolicy.c:2222",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:vma_dup_policy",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605408,
      "name": "__mpol_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct mempolicy * __mpol_dup(struct mempolicy * old)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct mempolicy * __mpol_dup(struct mempolicy * old)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
