# Function: <code>bsg_job_put</code>

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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583268629,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:49",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_softirq_done"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268800,
      "name": "bsg_job_put",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323360,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:48",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323360,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583507689,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:48",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_softirq_done"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507216,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721637,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:136",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_softirq_done"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721504,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583828517,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:141",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828080,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584018533,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018944,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584122133,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122560,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584520453,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520576,
      "name": "bsg_job_put",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584629317,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629200,
      "name": "bsg_job_put",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584657365,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584657488,
      "name": "bsg_job_put",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585071173,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:162",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071056,
      "name": "bsg_job_put",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585796053,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:169",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796208,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586577349,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:169",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577520,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586835109,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:169",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835280,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587112325,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:169",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112496,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495967064,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495967064,
      "name": "bsg_job_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229309356,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229309356,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290187648,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290187648,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275070108,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275070018,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584090869,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584091296,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584026629,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": [
        "drivers/scsi/scsi_transport_fc.c:fc_bsg_job_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027056,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584074629,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075056,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bsg_job_put(struct bsg_job * job)
```

```json
{
  "name": "bsg_job_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584177205,
      "name": "bsg_job_put",
      "external": true,
      "loc": "block/bsg-lib.c:161",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177632,
      "name": "bsg_job_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bsg_job_put(struct bsg_job * job)
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
