# Function: <code>inet_csk_find_open_port</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587368914,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587888530,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588234618,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:168",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588422409,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:177",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588825743,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589049599,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_hashbucket * inet_csk_find_open_port(struct sock * sk, struct inet_bind_bucket * * tb_ret, int * port_ret)
```

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590010368,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:182",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590010368,
      "name": "inet_csk_find_open_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
struct inet_bind_hashbucket * inet_csk_find_open_port(struct sock * sk, struct inet_bind_bucket * * tb_ret, int * port_ret)
```

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590052928,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:182",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590052928,
      "name": "inet_csk_find_open_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
struct inet_bind_hashbucket * inet_csk_find_open_port(struct sock * sk, struct inet_bind_bucket * * tb_ret, int * port_ret)
```

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589967392,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:182",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967392,
      "name": "inet_csk_find_open_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
struct inet_bind_hashbucket * inet_csk_find_open_port(struct sock * sk, struct inet_bind_bucket * * tb_ret, int * port_ret)
```

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590734928,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:190",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734928,
      "name": "inet_csk_find_open_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592364784,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:194",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592364784,
      "name": "inet_csk_find_open_port.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594212784,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:302",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594212784,
      "name": "inet_csk_find_open_port.constprop.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594599920,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:323",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594599920,
      "name": "inet_csk_find_open_port.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595403488,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:321",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595403488,
      "name": "inet_csk_find_open_port.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502665580,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235368260,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296269564,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278800510,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588655983,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588367967,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589092159,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_find_open_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589131811,
      "name": "inet_csk_find_open_port",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:173",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct inet_bind_hashbucket * inet_csk_find_open_port(struct sock * sk, struct inet_bind_bucket * * tb_ret, int * port_ret)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct inet_bind_hashbucket * inet_csk_find_open_port(struct sock * sk, struct inet_bind_bucket * * tb_ret, int * port_ret)
```
</details>
</li>
</ul>
