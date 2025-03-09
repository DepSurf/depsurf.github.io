# Function: <code>tcp_send_syn_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586675826,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3149",
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
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587122326,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3201",
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
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587320038,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3325",
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
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587451900,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3351",
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
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587973362,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3404",
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
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588323119,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3386",
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
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588512224,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3418",
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588917168,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3452",
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
      "addr": 18446744071588917168,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1050
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589140944,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 18446744071589140944,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590111536,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3557",
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
      "addr": 18446744071590111536,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590158992,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3737",
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
      "addr": 18446744071590158992,
      "name": "tcp_send_syn_data",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590072592,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3734",
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
      "addr": 18446744071590072592,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590846720,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3735",
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
      "addr": 18446744071590846720,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592482800,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3742",
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
      "addr": 18446744071592482800,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594338656,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3744",
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
      "addr": 18446744071594338656,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3826",
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
      "addr": 18446744071594725616,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
    },
    {
      "addr": 18446744071596870037,
      "name": "tcp_send_syn_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3925",
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
      "addr": 18446744071595530704,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1325
    },
    {
      "addr": 18446744071597793641,
      "name": "tcp_send_syn_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502756808,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 18446603336502756808,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235461284,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 3235461284,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296385664,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 13835058055296385664,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1464
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278880290,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 18446743936278880290,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588747328,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 18446744071588747328,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588459280,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 18446744071588459280,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589183504,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 18446744071589183504,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
```

```json
{
  "name": "tcp_send_syn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589223568,
      "name": "tcp_send_syn_data",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:3484",
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
      "addr": 18446744071589223568,
      "name": "tcp_send_syn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int tcp_send_syn_data(struct sock * sk, struct sk_buff * syn)
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
