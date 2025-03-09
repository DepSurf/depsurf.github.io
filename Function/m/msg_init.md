# Function: <code>msg_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581314245,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:145",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595195651,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595195651,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581481078,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:145",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595370754,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595370754,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581561745,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:152",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595619100,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1060",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595619100,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581619811,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:172",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596549606,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1061",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596549606,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581764467,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:169",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602877051,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1207",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602877051,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581933203,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:171",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603050356,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1280",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603050356,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582017619,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:170",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604849635,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1290",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604849635,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582154227,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604954477,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1315",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604954477,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582231507,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604989990,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604989990,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582469329,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609271061,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1347",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609271061,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582526369,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612339938,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1347",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612339938,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582555153,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:181",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614480274,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1349",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614480274,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582871281,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:182",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615426532,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1349",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615426532,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583434891,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:184",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617221326,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1349",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594016865,
      "name": "msg_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071617221326,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584024491,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:200",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627928160,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1369",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011120,
      "name": "msg_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071627928160,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584249227,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:230",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619691216,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1369",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619691216,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584465803,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:234",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621997792,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1369",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621997792,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493800640,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511032436,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511032436,
      "name": "msg_init",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227310996,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 3243513716,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243513716,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287416080,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302704036,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302704036,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273387142,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270745260,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270745260,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582200243,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604895450,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604895450,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582137603,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604864502,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604864502,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582190723,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604972634,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604972634,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void msg_init(struct uffd_msg * msg)
```

```json
{
  "name": "msg_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582266835,
      "name": "msg_init",
      "external": false,
      "loc": "fs/userfaultfd.c:180",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_unmap_complete",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:mremap_userfaultfd_complete",
        "fs/userfaultfd.c:dup_userfaultfd_complete",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604994160,
      "name": "msg_init",
      "external": true,
      "loc": "ipc/msg.c:1316",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604994160,
      "name": "msg_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
