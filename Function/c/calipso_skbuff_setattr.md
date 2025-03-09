# Function: <code>calipso_skbuff_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587691120,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1314",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587772976,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:673",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587691120,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071587772976,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587899872,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1314",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587988176,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:676",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899872,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071587988176,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588056976,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1314",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588146112,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:676",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588056976,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
    },
    {
      "addr": 18446744071588146112,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588595248,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1314",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588694192,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:676",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588595248,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
    },
    {
      "addr": 18446744071588694192,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588959888,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1311",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589060944,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:676",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588959888,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
    },
    {
      "addr": 18446744071589060944,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589183776,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1311",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589286640,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:676",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589183776,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
    },
    {
      "addr": 18446744071589286640,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589637536,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589742528,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589637536,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071589742528,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861744,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589966656,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861744,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071589966656,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590890864,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1298",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590996896,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590890864,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071590996896,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590952480,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1294",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591061520,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:664",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590952480,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071591061520,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590882464,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1294",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590992288,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:664",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590882464,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
    },
    {
      "addr": 18446744071590992288,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591713120,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1294",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591829968,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:664",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591713120,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
    },
    {
      "addr": 18446744071591829968,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593413248,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1294",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593543952,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:664",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593413248,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071593543952,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595323904,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1294",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595465216,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:665",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595323904,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071595465216,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595718976,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1294",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595972304,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:665",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595718976,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 863
    },
    {
      "addr": 18446744071595972304,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596566800,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1294",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596834800,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:668",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596566800,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 863
    },
    {
      "addr": 18446744071596834800,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503578904,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503701904,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503578904,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
    },
    {
      "addr": 18446603336503701904,
      "name": "calipso_skbuff_setattr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236226916,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236337152,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236226916,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
    },
    {
      "addr": 3236337152,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297384752,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297533792,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297384752,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
    },
    {
      "addr": 13835058055297533792,
      "name": "calipso_skbuff_setattr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279535520,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279632450,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279535520,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    },
    {
      "addr": 18446743936279632450,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589466112,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589570256,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589466112,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071589570256,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191104,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589294832,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191104,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071589294832,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589902976,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590012288,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589902976,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071590012288,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_skbuff_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589955856,
      "name": "calipso_skbuff_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1297",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590062368,
      "name": "calipso_skbuff_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:663",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955856,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071590062368,
      "name": "calipso_skbuff_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int calipso_skbuff_setattr(struct sk_buff * skb, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
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
