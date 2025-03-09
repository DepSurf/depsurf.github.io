# Function: <code>ww_mutex_lock_interruptible</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588317440,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1205",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313424,
      "name": "ww_mutex_lock_interruptible.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588317440,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588882848,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1205",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878912,
      "name": "ww_mutex_lock_interruptible.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588882848,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589259712,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1229",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257840,
      "name": "ww_mutex_lock_interruptible.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071589259712,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589502240,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1407",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589500128,
      "name": "ww_mutex_lock_interruptible.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071589502240,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589962800,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1417",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962800,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590190464,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590190464,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591206480,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591206480,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591701664,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1446",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591701664,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591645952,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1444",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591645952,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592819456,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1056",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592819456,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594721696,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1112",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594721696,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596471952,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1112",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596471952,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597016064,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1112",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597016064,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597945408,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1117",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations",
        "drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations",
        "drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_lock_single_interruptible",
        "drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_object_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597945408,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503935472,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503935472,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236544488,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236544488,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297788736,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297788736,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279803354,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279803354,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589792752,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589792752,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589515232,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515232,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590236160,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590236160,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock_interruptible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590288176,
      "name": "ww_mutex_lock_interruptible",
      "external": true,
      "loc": "kernel/locking/mutex.c:1443",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590288176,
      "name": "ww_mutex_lock_interruptible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int ww_mutex_lock_interruptible(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
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
