# Function: <code>dma_fence_add_callback</code>

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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585307440,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:242",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307440,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585395920,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:241",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395920,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585824848,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:240",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824848,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586071344,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:241",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586071344,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586215792,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:334",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215792,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:344",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459571,
      "name": "dma_fence_add_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586458048,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586605440,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586605440,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587392176,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:346",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587392176,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587460528,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:556",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587460528,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587343216,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:637",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587343216,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587909632,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:637",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_excl",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587909632,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589260176,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:635",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260176,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590822576,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:642",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590822576,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591164560,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:643",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591164560,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591510544,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:643",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591510544,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499490856,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499490856,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231963628,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231963628,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292775344,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292775344,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276707670,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276707670,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586295920,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295920,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586137296,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586137296,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553408,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553408,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
```

```json
{
  "name": "dma_fence_add_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586665440,
      "name": "dma_fence_add_callback",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:329",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665440,
      "name": "dma_fence_add_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int dma_fence_add_callback(struct dma_fence * fence, struct dma_fence_cb * cb, dma_fence_func_t func)
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
