# Function: <code>debugfs_create_files</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407584,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:789",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407584,
      "name": "debugfs_create_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583586992,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:786",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583586992,
      "name": "debugfs_create_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583803712,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:812",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583803712,
      "name": "debugfs_create_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583888568,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:839",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886688,
      "name": "debugfs_create_files.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584078939,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077360,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584201627,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200064,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595941,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:812",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594304,
      "name": "debugfs_create_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584714885,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:813",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713280,
      "name": "debugfs_create_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584743045,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:811",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584741456,
      "name": "debugfs_create_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585171109,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:812",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585169408,
      "name": "debugfs_create_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585908065,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:668",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586697057,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:668",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586957573,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:642",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587237829,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:623",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496071192,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496067960,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229399084,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229397456,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290310104,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290307392,
      "name": "debugfs_create_files.part.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275144138,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275142294,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584170363,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584168800,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584105611,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104048,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584154123,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152560,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "debugfs_create_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584258507,
      "name": "debugfs_create_files",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:808",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584257040,
      "name": "debugfs_create_files.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
bool debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void debugfs_create_files(struct dentry * parent, void * data, const struct blk_mq_debugfs_attr * attr)
```
</details>
</li>
</ul>
