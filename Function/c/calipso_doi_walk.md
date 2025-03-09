# Function: <code>calipso_doi_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587689008,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:545",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587771200,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:506",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587689008,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071587772720,
      "name": "calipso_doi_walk",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587897760,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:545",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587986400,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:509",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587897760,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071587987920,
      "name": "calipso_doi_walk",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588055072,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:545",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588144336,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:509",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055072,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071588145856,
      "name": "calipso_doi_walk",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588593136,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:545",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588692160,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:509",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593136,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071588693808,
      "name": "calipso_doi_walk",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588958512,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:545",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589058912,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:509",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958512,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071589060560,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589182400,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:545",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589284624,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:509",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589182400,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071589286256,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589636032,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589740480,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589636032,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071589742144,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589860240,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589964624,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860240,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071589966272,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590887584,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590996190,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590887584,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071590996512,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590949312,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:527",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591060814,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:497",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590949312,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071591061136,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590879264,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:527",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590991582,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:497",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590879264,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071590991904,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591709920,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:527",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591829262,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:497",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591709920,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071591829584,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593409840,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:527",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593543048,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:497",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593409840,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071593543456,
      "name": "calipso_doi_walk",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595320320,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:527",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595464088,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:498",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595320320,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071595464592,
      "name": "calipso_doi_walk",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595715344,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:527",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595971176,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:498",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595715344,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071595971680,
      "name": "calipso_doi_walk",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596563120,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:527",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596833672,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:501",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596563120,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071596834176,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503577256,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503699280,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503577256,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446603336503701248,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236224468,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236334804,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236224468,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 3236336688,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297381296,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297530444,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297381296,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 13835058055297533056,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279533676,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279630634,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279533676,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446743936279631970,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589464608,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589568224,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589464608,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071589569872,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589189600,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589292800,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189600,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071589294448,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589901472,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590010256,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589901472,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071590011904,
      "name": "calipso_doi_walk",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
```

```json
{
  "name": "calipso_doi_walk",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589954480,
      "name": "calipso_doi_walk",
      "external": false,
      "loc": "net/ipv6/calipso.c:531",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590060336,
      "name": "calipso_doi_walk",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:496",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589954480,
      "name": "calipso_doi_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071590061984,
      "name": "calipso_doi_walk",
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
int calipso_doi_walk(u32 * skip_cnt, int (*)(struct calipso_doi *, void *) callback, void * cb_arg)
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
