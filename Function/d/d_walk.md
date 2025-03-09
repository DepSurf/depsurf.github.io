# Function: <code>d_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter, void (*)(void *) finish)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085424,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1159",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:have_submounts",
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:do_one_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085424,
      "name": "d_walk",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter, void (*)(void *) finish)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248752,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1167",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:have_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248752,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter, void (*)(void *) finish)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326512,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1167",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326512,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter, void (*)(void *) finish)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581381856,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1200",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381856,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter, void (*)(void *) finish)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581523296,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1212",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:d_invalidate",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523296,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688400,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1241",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688400,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773456,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1250",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773456,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892256,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892256,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581964848,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964848,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196688,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1288",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196688,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246288,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1295",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246288,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271872,
      "name": "d_walk",
      "external": false,
      "loc": "fs/dcache.c:1323",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271872,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582590064,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1323",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590064,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113408,
      "name": "d_walk",
      "external": false,
      "loc": "fs/dcache.c:1348",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113408,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682224,
      "name": "d_walk",
      "external": false,
      "loc": "fs/dcache.c:1348",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682224,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900368,
      "name": "d_walk",
      "external": false,
      "loc": "fs/dcache.c:1348",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900368,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107792,
      "name": "d_walk",
      "external": false,
      "loc": "fs/dcache.c:1222",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107792,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493462400,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493462400,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227025408,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227025408,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287022320,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287022320,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1296
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273147718,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273147718,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933584,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933584,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871168,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871168,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924896,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924896,
      "name": "d_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void d_walk(struct dentry * parent, void * data, enum d_walk_ret (*)(void *, struct dentry *) enter)
```

```json
{
  "name": "d_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989264,
      "name": "d_walk",
      "external": true,
      "loc": "fs/dcache.c:1267",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_genocide",
        "fs/dcache.c:do_one_tree",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:path_has_submounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989264,
      "name": "d_walk",
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
<b>Param removed. </b>
<code>void (*)(void *) finish</code>
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
