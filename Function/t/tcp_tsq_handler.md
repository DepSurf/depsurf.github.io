# Function: <code>tcp_tsq_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586674160,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:735",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674160,
      "name": "tcp_tsq_handler.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587120783,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:733",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120656,
      "name": "tcp_tsq_handler.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587325423,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:733",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325248,
      "name": "tcp_tsq_handler.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587457247,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:734",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457072,
      "name": "tcp_tsq_handler.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587979103,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:775",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978864,
      "name": "tcp_tsq_handler.part.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588329488,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:806",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329488,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588518624,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:804",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518624,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588928944,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:804",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588928944,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589152880,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589152880,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590121968,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:871",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590121968,
      "name": "tcp_tsq_handler",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590169696,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1027",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590169696,
      "name": "tcp_tsq_handler",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590084128,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1027",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590084128,
      "name": "tcp_tsq_handler",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590858736,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1027",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590858736,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592495040,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1026",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592495040,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594350448,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1026",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594350448,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594738368,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1028",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594738368,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595543472,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1080",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595543472,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502768512,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502768512,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235473344,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235473344,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296400960,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296400960,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278890534,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278890534,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759264,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759264,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588471216,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471216,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195440,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195440,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void tcp_tsq_handler(struct sock * sk)
```

```json
{
  "name": "tcp_tsq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589235536,
      "name": "tcp_tsq_handler",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:808",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_pace_kick",
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589235536,
      "name": "tcp_tsq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void tcp_tsq_handler(struct sock * sk)
```
</details>
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
