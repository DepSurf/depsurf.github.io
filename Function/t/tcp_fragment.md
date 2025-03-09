# Function: <code>tcp_fragment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tcp_fragment(struct sock * sk, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586665264,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1135",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665264,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
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
int tcp_fragment(struct sock * sk, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587111520,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1149",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111520,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
int tcp_fragment(struct sock * sk, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587309728,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1168",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309728,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
int tcp_fragment(struct sock * sk, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587441424,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1244",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441424,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587962720,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1295",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587962720,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 917
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588312288,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1298",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312288,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588501408,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1286",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501408,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1284",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588932600,
      "name": "tcp_fragment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588911760,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589135488,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589135488,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590106224,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1366",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590106224,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590153152,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1533",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590153152,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1159
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590066912,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1533",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066912,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590840672,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1533",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590840672,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1175
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592476128,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1530",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592476128,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1168
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594331824,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1527",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tso_fragment",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594331824,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1168
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594719248,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1529",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594719248,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1065
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595523952,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1590",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595523952,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1074
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502751352,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502751352,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235455656,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235455656,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296378784,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296378784,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278875442,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278875442,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588741872,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588741872,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453824,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453824,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178048,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178048,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
int tcp_fragment(struct sock * sk, enum tcp_queue tcp_queue, struct sk_buff * skb, u32 len, unsigned int mss_now, gfp_t gfp)
```

```json
{
  "name": "tcp_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218128,
      "name": "tcp_fragment",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1303",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_match_skb_to_sack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218128,
      "name": "tcp_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum tcp_queue tcp_queue</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, len, mss_now, gfp</code> ➡️ <code>sk, tcp_queue, skb, len, mss_now, gfp</code>
</li>
</ul>
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
