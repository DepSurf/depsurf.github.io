# Function: <code>tcp_rack_advance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock * tp, const struct skb_mstamp * xmit_time, u8 sacked)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721872,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:82",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721872,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock * tp, const struct skb_mstamp * xmit_time, u8 sacked)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587169760,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:82",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587169760,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock * tp, const struct skb_mstamp * xmit_time, u8 sacked)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587369808,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:82",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587369808,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587503296,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:126",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587503296,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588025600,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:115",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025600,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376720,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:134",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376720,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588567200,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588567200,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588978336,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978336,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202784,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202784,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590175056,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590175056,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590224208,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:122",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590224208,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590138288,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:122",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138288,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590918592,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:122",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590918592,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592558768,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:118",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592558768,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594418432,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:118",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594418432,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594807776,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:118",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594807776,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595619024,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:118",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595619024,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502823280,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502823280,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235525140,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_one",
        "net/ipv4/tcp_input.c:tcp_sacktag_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235525140,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296471536,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296471536,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278936872,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278936872,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588809168,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809168,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588521104,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588521104,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245344,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245344,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rack_advance(struct tcp_sock * tp, u8 sacked, u32 end_seq, u64 xmit_time)
```

```json
{
  "name": "tcp_rack_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589285920,
      "name": "tcp_rack_advance",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:135",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589285920,
      "name": "tcp_rack_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 end_seq</code>
</li>
<li>
<b>Param reordered. </b>
<code>tp, xmit_time, sacked</code> ➡️ <code>tp, sacked, end_seq, xmit_time</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct skb_mstamp * xmit_time</code> ➡️ <code>u64 xmit_time</code>
</li>
</ul>
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
