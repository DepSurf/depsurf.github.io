# Function: <code>ipmr_mfc_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586880878,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1123",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587328960,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1111",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328960,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587531824,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1116",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531824,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587676368,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1170",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587676368,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1485
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588202880,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1298",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588202880,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588554624,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1215",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554624,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1895
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588751440,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1221",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588751440,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1891
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589184240,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589184240,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2001
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589409504,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589409504,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2001
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1181",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590393888,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
    },
    {
      "addr": 18446744071590403400,
      "name": "ipmr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1188",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590451600,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
    },
    {
      "addr": 18446744071591635526,
      "name": "ipmr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1188",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590380080,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1407
    },
    {
      "addr": 18446744071591578943,
      "name": "ipmr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1190",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591174944,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1431
    },
    {
      "addr": 18446744071592733439,
      "name": "ipmr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1184",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592833280,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
    },
    {
      "addr": 18446744071594619958,
      "name": "ipmr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1198",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594706848,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
    },
    {
      "addr": 18446744071596354708,
      "name": "ipmr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1198",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595102144,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
    },
    {
      "addr": 18446744071596883613,
      "name": "ipmr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1197",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595914816,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
    },
    {
      "addr": 18446744071597807785,
      "name": "ipmr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503056480,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503056480,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2220
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235744032,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235744032,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2288
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296754256,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296754256,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2596
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279117156,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279117156,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1868
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589014240,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589014240,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2001
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588737296,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588737296,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2001
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589450624,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450624,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2001
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
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ipmr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589496032,
      "name": "ipmr_mfc_add",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1213",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589496032,
      "name": "ipmr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2244
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int ipmr_mfc_add(struct net * net, struct mr_table * mrt, struct mfcctl * mfc, int mrtsock, int parent)
```
</details>
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
