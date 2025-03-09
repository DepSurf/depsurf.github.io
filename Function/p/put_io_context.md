# Function: <code>put_io_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582772832,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:129",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/bio.c:bio_disassociate_task",
        "block/ioprio.c:set_task_ioprio",
        "block/cfq-iosched.c:__cfq_slice_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772832,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583050656,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:129",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_disassociate_task",
        "block/ioprio.c:set_task_ioprio",
        "block/cfq-iosched.c:__cfq_slice_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583050656,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156432,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:129",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_disassociate_task",
        "block/blk-core.c:__blk_put_request",
        "block/ioprio.c:set_task_ioprio",
        "block/cfq-iosched.c:__cfq_slice_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156432,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583214288,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:137",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_disassociate_task",
        "block/blk-core.c:__blk_put_request",
        "block/blk-mq.c:blk_mq_free_request",
        "block/cfq-iosched.c:__cfq_slice_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214288,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583390912,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:138",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_disassociate_task",
        "block/blk-core.c:__blk_put_request",
        "block/blk-mq.c:blk_mq_free_request",
        "block/cfq-iosched.c:__cfq_slice_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390912,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583600704,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:138",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_disassociate_task",
        "block/blk-core.c:__blk_put_request",
        "block/blk-mq.c:blk_mq_free_request",
        "block/cfq-iosched.c:__cfq_slice_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600704,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583706992,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706992,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583895584,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583895584,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583998944,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998944,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387968,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:136",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387968,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584502176,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:142",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502176,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536592,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:142",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536592,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584947712,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:142",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947712,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585651872,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:209",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:exit_io_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585651872,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586425056,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:209",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:exit_io_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586425056,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586672608,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:205",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:exit_io_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672608,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586943504,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:205",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:exit_io_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943504,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495826992,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495826992,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229176212,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229176212,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290016896,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290016896,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274961292,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274961292,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583967680,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967680,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583904592,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904592,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583951440,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951440,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void put_io_context(struct io_context * ioc)
```

```json
{
  "name": "put_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584053440,
      "name": "put_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:135",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584053440,
      "name": "put_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
