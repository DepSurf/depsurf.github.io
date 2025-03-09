# Function: <code>tcp_fastretrans_alert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_fastretrans_alert(struct sock * sk, const int acked, const int prior_unsacked, bool is_dupack, int flag)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586647840,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2759",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586647840,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2708
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
void tcp_fastretrans_alert(struct sock * sk, const int acked, bool is_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587090064,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2761",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587090064,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2869
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
void tcp_fastretrans_alert(struct sock * sk, const int acked, bool is_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286960,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2815",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286960,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2971
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
void tcp_fastretrans_alert(struct sock * sk, const int acked, bool is_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587419936,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2797",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587419936,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2438
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, bool is_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939792,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2743",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939792,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2325
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, bool is_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289424,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2774",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289424,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2366
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588478064,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2765",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588478064,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2265
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2785",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884944,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2418
    },
    {
      "addr": 18446744071588905154,
      "name": "tcp_fastretrans_alert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589109024,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589109024,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2418
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590079312,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2776",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590079312,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2834
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590125040,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2889",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125040,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2858
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590039264,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2892",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590039264,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3021
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590812112,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2926",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590812112,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3021
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592446880,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2942",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592446880,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2928
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594301088,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2953",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594301088,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2887
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594687312,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2952",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594687312,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2878
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595492160,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2999",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595492160,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2851
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502725720,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502725720,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235429396,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235429396,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2076
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296346480,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296346480,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2524
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278852742,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278852742,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1676
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588715408,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588715408,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2418
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427392,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427392,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2418
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589151584,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151584,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2418
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
void tcp_fastretrans_alert(struct sock * sk, const u32 prior_snd_una, int num_dupack, int * ack_flag, int * rexmit)
```

```json
{
  "name": "tcp_fastretrans_alert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191488,
      "name": "tcp_fastretrans_alert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2791",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191488,
      "name": "tcp_fastretrans_alert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2418
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * ack_flag</code>
</li>
<li>
<b>Param added. </b>
<code>int * rexmit</code>
</li>
<li>
<b>Param removed. </b>
<code>const int prior_unsacked</code>
</li>
<li>
<b>Param removed. </b>
<code>int flag</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, acked, prior_unsacked, is_dupack, flag</code> ➡️ <code>sk, acked, is_dupack, ack_flag, rexmit</code>
</li>
</ul>
</details>
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
<code>const u32 prior_snd_una</code>
</li>
<li>
<b>Param removed. </b>
<code>const int acked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int num_dupack</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_dupack</code>
</li>
</ul>
</details>
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
