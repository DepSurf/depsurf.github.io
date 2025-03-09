# Function: <code>set_ifa_lifetime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586777040,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:718",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586777040,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587224672,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:722",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587224672,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587425216,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:722",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587425216,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587570116,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:743",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587557152,
      "name": "set_ifa_lifetime",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588093904,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:750",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080784,
      "name": "set_ifa_lifetime",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588447524,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:751",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434144,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588641143,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:761",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626160,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589053163,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038080,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589277674,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589262592,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590255063,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:799",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590237264,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590307959,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:798",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590289776,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590223727,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:798",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590205648,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591006383,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:798",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590987664,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592652745,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:799",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592632496,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594519524,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:800",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594498288,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594911634,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:800",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594889904,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595723380,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:803",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595701184,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502907784,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502891312,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235600784,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235584916,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296574728,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296553168,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279002716,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278989748,
      "name": "set_ifa_lifetime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588883850,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868768,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588595786,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580704,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589320234,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589305152,
      "name": "set_ifa_lifetime",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void set_ifa_lifetime(struct in_ifaddr * ifa, __u32 valid_lft, __u32 prefered_lft)
```

```json
{
  "name": "set_ifa_lifetime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589362106,
      "name": "set_ifa_lifetime",
      "external": false,
      "loc": "net/ipv4/devinet.c:792",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589346864,
      "name": "set_ifa_lifetime",
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
