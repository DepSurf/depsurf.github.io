# Function: <code>__inet_del_ifa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586778480,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:326",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586778480,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587225760,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:326",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587225760,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587426304,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:326",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587426304,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587562640,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:326",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587562640,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085952,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:332",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085952,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588439504,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:333",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439504,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588632160,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:343",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588632160,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589044224,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589044224,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589268368,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589268368,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590243088,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:348",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:inetdev_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590243088,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590295824,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:348",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:inetdev_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590295824,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590211440,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:348",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590211440,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:348",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590992304,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
    },
    {
      "addr": 18446744071592722897,
      "name": "__inet_del_ifa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:351",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592638144,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071594609182,
      "name": "__inet_del_ifa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:352",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:inetdev_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594504288,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071596344413,
      "name": "__inet_del_ifa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:352",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:inetdev_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594895904,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071596873480,
      "name": "__inet_del_ifa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:352",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr",
        "net/ipv4/devinet.c:inetdev_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595707232,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    },
    {
      "addr": 18446744071597797565,
      "name": "__inet_del_ifa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502898104,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502898104,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235591388,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235591388,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296562112,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296562112,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278995096,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278995096,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874544,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874544,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588586480,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586480,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589310928,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589310928,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
void __inet_del_ifa(struct in_device * in_dev, struct in_ifaddr * * ifap, int destroy, struct nlmsghdr * nlh, u32 portid)
```

```json
{
  "name": "__inet_del_ifa",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589352736,
      "name": "__inet_del_ifa",
      "external": false,
      "loc": "net/ipv4/devinet.c:347",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_deladdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589352736,
      "name": "__inet_del_ifa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
