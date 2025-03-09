# Function: <code>__ww_mutex_check_waiters</code>

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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589499504,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:417",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589499504,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589959936,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:418",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959936,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590187600,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590187600,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591203856,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591203856,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591698992,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591698992,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591641504,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591641504,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076304,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:355",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076304,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211824,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:355",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211824,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580404496,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:355",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580404496,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580473584,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:355",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473584,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580533408,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/ww_mutex.h:355",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533408,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503929976,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503929976,
      "name": "__ww_mutex_check_waiters",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236542060,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236542060,
      "name": "__ww_mutex_check_waiters",
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297782448,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297782448,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279800128,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279800128,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589789888,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589789888,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589512368,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512368,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590233296,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590233296,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "__ww_mutex_check_waiters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590284080,
      "name": "__ww_mutex_check_waiters",
      "external": false,
      "loc": "kernel/locking/mutex.c:444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590284080,
      "name": "__ww_mutex_check_waiters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __ww_mutex_check_waiters(struct mutex * lock, struct ww_acquire_ctx * ww_ctx)
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
