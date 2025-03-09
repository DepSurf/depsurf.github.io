# Function: <code>xfrm_replay_seqhi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586959824,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:24",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959824,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587404058,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:24",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406608,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587607274,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:24",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609824,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587755831,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:24",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587754432,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588284519,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:24",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283104,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588638192,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:24",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588638192,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588854288,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:24",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588854288,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589295479,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589293920,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589519815,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589518256,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590515389,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590512096,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590575181,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590571808,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590500334,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590497504,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591304926,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591303120,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592972046,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592969968,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594858846,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594856432,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595250046,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595247616,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596090574,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596088144,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503183888,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503183888,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235860388,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235858596,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296914956,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296912432,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279224360,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279224360,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589124183,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589122624,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588849223,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588847664,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589561047,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589559488,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u32 xfrm_replay_seqhi(struct xfrm_state * x, __be32 net_seq)
```

```json
{
  "name": "xfrm_replay_seqhi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589609415,
      "name": "xfrm_replay_seqhi",
      "external": true,
      "loc": "net/xfrm/xfrm_replay.c:12",
      "file": "net/xfrm/xfrm_replay.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589607040,
      "name": "xfrm_replay_seqhi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
