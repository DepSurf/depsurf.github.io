# Function: <code>tcp_reinit_congestion_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586712709,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:194",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587160437,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:194",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587359544,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:195",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587491376,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:192",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587491376,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588013664,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:189",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588013664,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588364880,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:189",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364880,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588555264,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:189",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588555264,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966352,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966352,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589190816,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190816,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590162272,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590162272,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590212498,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:191",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590126722,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:191",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590904310,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:191",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592543709,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:201",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594402557,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:201",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594791453,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:253",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595602845,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:253",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502808976,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502808976,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235511800,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235511800,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296452672,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296452672,
      "name": "tcp_reinit_congestion_control",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278925174,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278925174,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797200,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797200,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588509136,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588509136,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589233376,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589233376,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```

```json
{
  "name": "tcp_reinit_congestion_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589273616,
      "name": "tcp_reinit_congestion_control",
      "external": false,
      "loc": "net/ipv4/tcp_cong.c:190",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589273616,
      "name": "tcp_reinit_congestion_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void tcp_reinit_congestion_control(struct sock * sk, const struct tcp_congestion_ops * ca)
```
</details>
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
