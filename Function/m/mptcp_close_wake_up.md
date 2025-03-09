# Function: <code>mptcp_close_wake_up</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_close_wake_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591162886,
      "name": "mptcp_close_wake_up",
      "external": false,
      "loc": "net/mptcp/protocol.c:336",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_check_fastclose"
      ],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_check_fastclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591145328,
      "name": "mptcp_close_wake_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void mptcp_close_wake_up(struct sock * sk)
```

```json
{
  "name": "mptcp_close_wake_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591077136,
      "name": "mptcp_close_wake_up",
      "external": false,
      "loc": "net/mptcp/protocol.c:332",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591077136,
      "name": "mptcp_close_wake_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_close_wake_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591939058,
      "name": "mptcp_close_wake_up",
      "external": false,
      "loc": "net/mptcp/protocol.c:341",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker"
      ],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591917632,
      "name": "mptcp_close_wake_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void mptcp_close_wake_up(struct sock * sk)
```

```json
{
  "name": "mptcp_close_wake_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593642304,
      "name": "mptcp_close_wake_up",
      "external": false,
      "loc": "net/mptcp/protocol.c:405",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593642304,
      "name": "mptcp_close_wake_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void mptcp_close_wake_up(struct sock * sk)
```

```json
{
  "name": "mptcp_close_wake_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595573536,
      "name": "mptcp_close_wake_up",
      "external": false,
      "loc": "net/mptcp/protocol.c:397",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595573536,
      "name": "mptcp_close_wake_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void mptcp_close_wake_up(struct sock * sk)
```

```json
{
  "name": "mptcp_close_wake_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596083184,
      "name": "mptcp_close_wake_up",
      "external": false,
      "loc": "net/mptcp/protocol.c:412",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596083184,
      "name": "mptcp_close_wake_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void mptcp_close_wake_up(struct sock * sk)
```

```json
{
  "name": "mptcp_close_wake_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596951376,
      "name": "mptcp_close_wake_up",
      "external": false,
      "loc": "net/mptcp/protocol.c:400",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596951376,
      "name": "mptcp_close_wake_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void mptcp_close_wake_up(struct sock * sk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void mptcp_close_wake_up(struct sock * sk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void mptcp_close_wake_up(struct sock * sk)
```
</details>
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
