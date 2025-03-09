# Function: <code>security_netlbl_secattr_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361280,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3321",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361280,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582400,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3315",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582400,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675616,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3315",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675616,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582768256,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3431",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768256,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924320,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3441",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924320,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122976,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3591",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122976,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583239168,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3557",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239168,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426064,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3575",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426064,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531968,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531968,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881328,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3620",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881328,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001808,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3781",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001808,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584029552,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3860",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029552,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3870",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592301366,
      "name": "security_netlbl_secattr_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584399936,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 602
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3873",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594082666,
      "name": "security_netlbl_secattr_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585026256,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3866",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596097344,
      "name": "security_netlbl_secattr_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585744160,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3805",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596620523,
      "name": "security_netlbl_secattr_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585974816,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3824",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597526111,
      "name": "security_netlbl_secattr_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586222064,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495301688,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495301688,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228681992,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228681992,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289289312,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289289312,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274521288,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274521288,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583500704,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583500704,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437760,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437760,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583484480,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583484480,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int security_netlbl_secattr_to_sid(struct selinux_state * state, struct netlbl_lsm_secattr * secattr, u32 * sid)
```

```json
{
  "name": "security_netlbl_secattr_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583580768,
      "name": "security_netlbl_secattr_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:3582",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583580768,
      "name": "security_netlbl_secattr_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>secattr, sid</code> ➡️ <code>state, secattr, sid</code>
</li>
</ul>
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, secattr, sid</code> ➡️ <code>secattr, sid</code>
</li>
</ul>
</details>
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
