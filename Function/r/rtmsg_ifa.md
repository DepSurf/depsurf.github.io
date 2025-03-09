# Function: <code>rtmsg_ifa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586778224,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1620",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586778224,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587225504,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1646",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587225504,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587426048,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1646",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587426048,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587562416,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1686",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587562416,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085728,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1695",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085728,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588439264,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1705",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439264,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588631888,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1832",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631888,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1884",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589043952,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071589055635,
      "name": "rtmsg_ifa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589268096,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589268096,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590242816,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1885",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242816,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590295552,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1884",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590295552,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590211168,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1884",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590211168,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590992032,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1884",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590992032,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592637856,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1891",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592637856,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594503984,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1892",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594503984,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594895600,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1895",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594895600,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595706928,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1926",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595706928,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502897832,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502897832,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235591096,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235591096,
      "name": "rtmsg_ifa",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296561760,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296561760,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278994884,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278994884,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874272,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874272,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588586208,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586208,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589310656,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589310656,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rtmsg_ifa(int event, struct in_ifaddr * ifa, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "rtmsg_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589352464,
      "name": "rtmsg_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:1879",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa",
        "net/ipv4/devinet.c:__inet_del_ifa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589352464,
      "name": "rtmsg_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
