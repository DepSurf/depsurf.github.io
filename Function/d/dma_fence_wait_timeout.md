# Function: <code>dma_fence_wait_timeout</code>

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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304624,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:157",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304624,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585393376,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:154",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585393376,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585822720,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:153",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822720,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068480,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:153",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068480,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214944,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:227",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214944,
      "name": "dma_fence_wait_timeout",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:220",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459545,
      "name": "dma_fence_wait_timeout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586457248,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586604704,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586604704,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587393264,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587393264,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587461312,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:410",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461312,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587343888,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:491",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587343888,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587910304,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:491",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910304,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589260944,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:492",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260944,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590822800,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:500",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590822800,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591165456,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:501",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591165456,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591511440,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:501",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_fences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591511440,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499492888,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499492888,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231963000,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231963000,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292774576,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292774576,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276706458,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276706458,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586295184,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295184,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586136560,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136560,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552672,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552672,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
```

```json
{
  "name": "dma_fence_wait_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586664608,
      "name": "dma_fence_wait_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:204",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664608,
      "name": "dma_fence_wait_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
long int dma_fence_wait_timeout(struct dma_fence * fence, bool intr, long int timeout)
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
