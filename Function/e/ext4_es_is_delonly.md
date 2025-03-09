# Function: <code>ext4_es_is_delonly</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582365228,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:186",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414352,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:186",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357136,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071582414352,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582533190,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:186",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582583296,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:186",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525120,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582583296,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582634694,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684256,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624704,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582684256,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582936706,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995376,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933200,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582995376,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583011138,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583071056,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007792,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583071056,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583043726,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096784,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033520,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583096784,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583372238,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583436432,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370288,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583436432,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583886135,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583955152,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882336,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071583955152,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584510887,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584582224,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584506832,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071584582224,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584740727,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584808944,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735328,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071584808944,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584972999,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_delayed_clu",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:get_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585041824,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967856,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585041824,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494286056,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494338856,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494274168,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336494338856,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227719940,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:count_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 3227772944,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227708320,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3227772944,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287999356,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:count_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288064352,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287985184,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 13835058055288064352,
      "name": "ext4_es_is_delonly",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273730564,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:count_rsvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273771458,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273721536,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446743936273771458,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582603430,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582652992,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593440,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582652992,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582540598,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582590160,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530608,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582590160,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582593542,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582642848,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583552,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582642848,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```

```json
{
  "name": "ext4_es_is_delonly",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582675609,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582726144,
      "name": "ext4_es_is_delonly",
      "external": false,
      "loc": "fs/ext4/extents_status.h:187",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665104,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582726144,
      "name": "ext4_es_is_delonly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int ext4_es_is_delonly(struct extent_status * es)
```
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
