# Function: <code>__kthread_cancel_work</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536912,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:965",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536912,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524096,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:970",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524096,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550160,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:975",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550160,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577120,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:993",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577120,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614624,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:995",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614624,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639536,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639536,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665488,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665488,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697120,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1041",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697120,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675088,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1095",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675088,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579686486,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1153",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
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
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579764806,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1153",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
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
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579870741,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1213",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
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
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580013573,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1213",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
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
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580067109,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1214",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
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
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580109749,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1231",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490846552,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490846552,
      "name": "__kthread_cancel_work",
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224870932,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224870932,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283678128,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283678128,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271510954,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271510954,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641808,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641808,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570208,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570208,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639072,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639072,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```

```json
{
  "name": "__kthread_cancel_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673344,
      "name": "__kthread_cancel_work",
      "external": false,
      "loc": "kernel/kthread.c:1005",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673344,
      "name": "__kthread_cancel_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool __kthread_cancel_work(struct kthread_work * work, bool is_dwork, long unsigned int * flags)
```
</details>
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
