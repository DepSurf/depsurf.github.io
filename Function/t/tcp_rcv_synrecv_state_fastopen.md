# Function: <code>tcp_rcv_synrecv_state_fastopen</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588890656,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6044",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890656,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589114736,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114736,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590094438,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6147",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590140587,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6283",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590055095,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6289",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590828795,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6324",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592464262,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6392",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594318662,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6414",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594705062,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6421",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595498048,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6578",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595498048,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502730456,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502730456,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235417916,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235417916,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296332000,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296332000,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278842788,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278842788,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588721120,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588721120,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588433104,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433104,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589157296,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157296,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_synrecv_state_fastopen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589197200,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197200,
      "name": "tcp_rcv_synrecv_state_fastopen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void tcp_rcv_synrecv_state_fastopen(struct sock * sk)
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
