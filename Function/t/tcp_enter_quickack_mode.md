# Function: <code>tcp_enter_quickack_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586621175,
      "name": "tcp_enter_quickack_mode",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:189",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587105397,
      "name": "tcp_enter_quickack_mode",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:191",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
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
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587303034,
      "name": "tcp_enter_quickack_mode",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:212",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
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
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587433036,
      "name": "tcp_enter_quickack_mode",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:211",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
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
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587954360,
      "name": "tcp_enter_quickack_mode",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:197",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588305259,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:218",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266400,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588494093,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:219",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588454880,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588901530,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588860960,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589125658,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084544,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590092768,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:226",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590049104,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590138914,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:289",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590094240,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590053446,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:289",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590008976,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590827126,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:290",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590779872,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592463045,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:290",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592412752,
      "name": "tcp_enter_quickack_mode",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594317429,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:290",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594265728,
      "name": "tcp_enter_quickack_mode",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594703828,
      "name": "tcp_enter_quickack_mode",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:290",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595508702,
      "name": "tcp_enter_quickack_mode",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:306",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502741236,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502700472,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235445440,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235401488,
      "name": "tcp_enter_quickack_mode",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296366020,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296312496,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278866040,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278829362,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588732042,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690928,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588444026,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588402912,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589168218,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589127104,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```

```json
{
  "name": "tcp_enter_quickack_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589208218,
      "name": "tcp_enter_quickack_mode",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:225",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce",
        "net/ipv4/tcp_input.c:__tcp_ecn_check_ce"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589166928,
      "name": "tcp_enter_quickack_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void tcp_enter_quickack_mode(struct sock * sk, unsigned int max_quickacks)
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
