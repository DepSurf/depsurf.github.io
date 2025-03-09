# Function: <code>____sys_sendmsg</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588339776,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588339776,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589198688,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2296",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589198688,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589196576,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2289",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589196576,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589089840,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2283",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589089840,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589807968,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2356",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589807968,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591326976,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2432",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591326976,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2420",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593080304,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
    },
    {
      "addr": 18446744071596321523,
      "name": "____sys_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2457",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593533872,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
    },
    {
      "addr": 18446744071596851252,
      "name": "____sys_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2527",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594306192,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
    },
    {
      "addr": 18446744071597776122,
      "name": "____sys_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501835888,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501835888,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234614588,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234614588,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295235264,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295235264,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278178526,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278178526,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587946560,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946560,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587659664,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587659664,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588278336,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278336,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```

```json
{
  "name": "____sys_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588413488,
      "name": "____sys_sendmsg",
      "external": false,
      "loc": "net/socket.c:2235",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588413488,
      "name": "____sys_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int ____sys_sendmsg(struct socket * sock, struct msghdr * msg_sys, unsigned int flags, struct used_address * used_address, unsigned int allowed_msghdr_flags)
```
</details>
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
