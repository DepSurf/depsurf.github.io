# Function: <code>tcp_check_sack_reordering</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587923632,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:859",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923632,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588272528,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:886",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272528,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588461184,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:872",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461184,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588867376,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:882",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588867376,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589092496,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589092496,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590055376,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:886",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590055376,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590100512,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:992",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590100512,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590014448,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:992",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590014448,
      "name": "tcp_check_sack_reordering",
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590786032,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1024",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590786032,
      "name": "tcp_check_sack_reordering",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592419472,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1033",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592419472,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594272512,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1032",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594272512,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594658592,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1031",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594658592,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595462736,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1065",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595462736,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502708560,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502708560,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235409896,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235409896,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296324032,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296324032,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278837370,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278837370,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588698880,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588698880,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588410864,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410864,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589135056,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589135056,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
```

```json
{
  "name": "tcp_check_sack_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589174880,
      "name": "tcp_check_sack_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:884",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174880,
      "name": "tcp_check_sack_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_check_sack_reordering(struct sock * sk, const u32 low_seq, const int ts)
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
