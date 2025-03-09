# Function: <code>dma_fence_free</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585304864,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:187",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304864,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585393824,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:184",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585393824,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585823131,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:183",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822960,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586069113,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:184",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068944,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213161,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:275",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212992,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586456434,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:285",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455168,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586603390,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603136,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587393100,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391504,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587461672,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:480",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587459888,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587342808,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:561",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587341536,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587909237,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:561",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907984,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589259738,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589258144,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590822106,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:572",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590819824,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591163642,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:573",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591161104,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591509626,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:573",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591507040,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499489480,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499487928,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231961512,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231961356,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292772000,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292771664,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276705344,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276705204,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586293870,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293616,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586135246,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134992,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586551358,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586551104,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_free(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586663230,
      "name": "dma_fence_free",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:270",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/seqno-fence.c:seqno_release",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662976,
      "name": "dma_fence_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dma_fence_free(struct dma_fence * fence)
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
