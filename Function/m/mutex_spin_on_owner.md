# Function: <code>mutex_spin_on_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671168,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:225",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671168,
      "name": "mutex_spin_on_owner.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689968,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:225",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689968,
      "name": "mutex_spin_on_owner.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717712,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:353",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717712,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713936,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:424",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713936,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746528,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:424",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746528,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780896,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:425",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780896,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827472,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:523",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827472,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858800,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:524",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858800,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907376,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907376,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951184,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951184,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939600,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939600,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947424,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947424,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076512,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:346",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076512,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211584,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:352",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211584,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580404816,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:352",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580404816,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580473328,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:352",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473328,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580533152,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:352",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533152,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491107880,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491107880,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225111832,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225111832,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283999840,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283999840,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879488,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879488,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814480,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814480,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867648,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867648,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
```

```json
{
  "name": "mutex_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579913056,
      "name": "mutex_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/mutex.c:550",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913056,
      "name": "mutex_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ww_acquire_ctx * ww_ctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct mutex_waiter * waiter</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool mutex_spin_on_owner(struct mutex * lock, struct task_struct * owner, struct ww_acquire_ctx * ww_ctx, struct mutex_waiter * waiter)
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
