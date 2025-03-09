# Function: <code>__tcp_mtu_to_mss</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586664696,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1285",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587122471,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1300",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
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
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587320184,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1322",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587451972,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1401",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436496,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587973434,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1455",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961760,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588323205,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1446",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311600,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588512310,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1434",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500688,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588917286,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1448",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909728,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589141062,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129168,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590111654,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1530",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590102736,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590159110,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1697",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149680,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590072710,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1697",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063760,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590846838,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1697",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590830512,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592482929,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1692",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592465920,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594338785,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1689",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594320352,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594725794,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1681",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594706768,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595530882,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1742",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502756920,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502744568,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235461392,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235453364,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296385796,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296369952,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278880390,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278869088,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588747446,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735552,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588459398,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447536,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589183622,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589171728,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "__tcp_mtu_to_mss",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589223686,
      "name": "__tcp_mtu_to_mss",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211760,
      "name": "__tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int __tcp_mtu_to_mss(struct sock * sk, int pmtu)
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
