# Function: <code>tcf_block_put_ext</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587755904,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:339",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755904,
      "name": "tcf_block_put_ext",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588097745,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:664",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097216,
      "name": "tcf_block_put_ext.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071588097648,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588280497,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1119",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588280320,
      "name": "tcf_block_put_ext.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071588280400,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588675873,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1497",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588675696,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071588675776,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588901377,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588901200,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071588901280,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589786912,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1374",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589794400,
      "name": "tcf_block_put_ext",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589829856,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1375",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589829696,
      "name": "tcf_block_put_ext",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589736156,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1375",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589736000,
      "name": "tcf_block_put_ext",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590494796,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1376",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590494640,
      "name": "tcf_block_put_ext",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592090363,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1393",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592090176,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593908011,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1395",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593907808,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594295403,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1500",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594295200,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595094320,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1520",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595094320,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502494052,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502493824,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446603336502493928,
      "name": "tcf_block_put_ext",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235204828,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235204640,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 3235204720,
      "name": "tcf_block_put_ext",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296055308,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296055088,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 13835058055296055216,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278669134,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278668942,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446743936278669034,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588507761,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588507584,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071588507664,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588219761,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219584,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071588219664,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588839937,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588839760,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071588839840,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_block_put_ext",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588979825,
      "name": "tcf_block_put_ext",
      "external": true,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_block_put"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979648,
      "name": "tcf_block_put_ext.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071588979728,
      "name": "tcf_block_put_ext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void tcf_block_put_ext(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```
</details>
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
