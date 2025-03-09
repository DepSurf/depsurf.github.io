# Function: <code>tcp_connect_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586675046,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3057",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587121542,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3109",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587319254,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3233",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587450848,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3255",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587972201,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3309",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588321919,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3290",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588511023,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3322",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588910160,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3356",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588910160,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589133872,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589133872,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1319
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590104720,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3461",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104720,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1213
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590151664,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3641",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590151664,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590064928,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3638",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590064928,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3639",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590838608,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1485
    },
    {
      "addr": 18446744071592718074,
      "name": "tcp_connect_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3646",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592474352,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1451
    },
    {
      "addr": 18446744071594604497,
      "name": "tcp_connect_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3648",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594330000,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1451
    },
    {
      "addr": 18446744071596339811,
      "name": "tcp_connect_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3730",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594717440,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1435
    },
    {
      "addr": 18446744071596869198,
      "name": "tcp_connect_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3832",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595521424,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
    },
    {
      "addr": 18446744071597793404,
      "name": "tcp_connect_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502748432,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502748432,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235453816,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235453816,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296376912,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296376912,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278874210,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278874210,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588740256,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588740256,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1319
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588452208,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452208,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1319
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589176432,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176432,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1319
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
void tcp_connect_init(struct sock * sk)
```

```json
{
  "name": "tcp_connect_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589216496,
      "name": "tcp_connect_init",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216496,
      "name": "tcp_connect_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1334
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void tcp_connect_init(struct sock * sk)
```
</details>
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
