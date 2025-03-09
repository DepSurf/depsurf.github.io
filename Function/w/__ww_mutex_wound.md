# Function: <code>__ww_mutex_wound</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827360,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827360,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858688,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:363",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858688,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907264,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907264,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591203939,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
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
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591699075,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
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
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591641587,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
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
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580076420,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:300",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
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
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580211990,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:300",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
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
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580404662,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:300",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
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
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580473750,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:300",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
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
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580533574,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:300",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491108056,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491108056,
      "name": "__ww_mutex_wound",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225112052,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225112052,
      "name": "__ww_mutex_wound",
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283999648,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283999648,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271688778,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271688778,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879376,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879376,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814368,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814368,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867536,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867536,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```

```json
{
  "name": "__ww_mutex_wound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912944,
      "name": "__ww_mutex_wound",
      "external": false,
      "loc": "kernel/locking/mutex.c:389",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_check_waiters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912944,
      "name": "__ww_mutex_wound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool __ww_mutex_wound(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, struct ww_acquire_ctx * hold_ctx)
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
