# Function: <code>tcp_set_ca_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586611785,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:918",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586624576,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:918",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586708616,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:918",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587056424,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:935",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587091422,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:935",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587156392,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:935",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587252283,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:982",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587288310,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:982",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587355320,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:982",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587383985,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1034",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587421237,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1034",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_enter_cwr",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587484488,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1034",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587915919,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1036",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587941076,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1036",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_enter_cwr",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588010424,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1036",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588264328,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1053",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588291010,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1053",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588362296,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1053",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588452581,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1093",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588479550,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1093",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588552680,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1093",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588858391,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1095",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588886397,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1095",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588963809,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1095",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589081991,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589110537,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589184609,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590046330,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1136",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590080499,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1136",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159601,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1136",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590087913,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1141",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590126244,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1141",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590208593,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1141",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590002588,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1133",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590042076,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1133",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590122705,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1133",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590773169,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1126",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590814924,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1126",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590896977,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1126",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_set_ca_state(struct sock * sk, const u8 ca_state)
```

```json
{
  "name": "tcp_set_ca_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592541072,
      "name": "tcp_set_ca_state",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:37",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592541072,
      "name": "tcp_set_ca_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tcp_set_ca_state(struct sock * sk, const u8 ca_state)
```

```json
{
  "name": "tcp_set_ca_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594399728,
      "name": "tcp_set_ca_state",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:37",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594399728,
      "name": "tcp_set_ca_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tcp_set_ca_state(struct sock * sk, const u8 ca_state)
```

```json
{
  "name": "tcp_set_ca_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594788048,
      "name": "tcp_set_ca_state",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:37",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594788048,
      "name": "tcp_set_ca_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tcp_set_ca_state(struct sock * sk, const u8 ca_state)
```

```json
{
  "name": "tcp_set_ca_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595599440,
      "name": "tcp_set_ca_state",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:37",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595599440,
      "name": "tcp_set_ca_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502698048,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502726872,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502801860,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235399472,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235430720,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 3235509156,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296309936,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296348024,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296443392,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278827568,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278853822,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278919234,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588688375,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588716921,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588790993,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588400359,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588428905,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588502929,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589124551,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589153097,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589227169,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
  "name": "tcp_set_ca_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589164375,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589193001,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_try_keep_open",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589267299,
      "name": "tcp_set_ca_state",
      "external": false,
      "loc": "include/net/tcp.h:1116",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void tcp_set_ca_state(struct sock * sk, const u8 ca_state)
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
