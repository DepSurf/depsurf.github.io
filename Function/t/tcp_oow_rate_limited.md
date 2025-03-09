# Function: <code>tcp_oow_rate_limited</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651920,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3400",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651920,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587096416,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3450",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587096416,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587294016,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3456",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294016,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587424800,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3419",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424800,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587944944,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3364",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587944944,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588294704,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3422",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588294704,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588483456,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3415",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483456,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588890736,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3435",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890736,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589114816,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114816,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590085520,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3426",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085520,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590131072,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3546",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131072,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590045360,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3553",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590045360,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590818704,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3587",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590818704,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592453296,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3604",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592453296,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594307536,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3615",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594307536,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594693728,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3620",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594693728,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595498256,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3694",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595498256,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502730536,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502730536,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235434324,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235434324,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296352272,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296352272,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278856660,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278856660,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588721200,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588721200,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588433184,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433184,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589157376,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157376,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool tcp_oow_rate_limited(struct net * net, const struct sk_buff * skb, int mib_idx, u32 * last_oow_ack_time)
```

```json
{
  "name": "tcp_oow_rate_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589197280,
      "name": "tcp_oow_rate_limited",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3442",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197280,
      "name": "tcp_oow_rate_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
