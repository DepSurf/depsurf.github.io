# Function: <code>queue_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164128,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1108",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071585794288,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:723",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164128,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071585794288,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581334480,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1145",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071586192448,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:557",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334480,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071586192448,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413616,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1145",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071586396816,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:557",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413616,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071586396816,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581467904,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1159",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071586499536,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:555",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467904,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071586499536,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610032,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1162",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071586966960,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:562",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610032,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071586966960,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768320,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1163",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071587263296,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:654",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768320,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071587263296,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581854896,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1189",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071587443568,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:709",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854896,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071587443568,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979488,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1204",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071587713696,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979488,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587713696,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054480,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071587917904,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054480,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587917904,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work, long unsigned int dirtied_before)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582294464,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1298",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071588780561,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:702",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294464,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work, long unsigned int dirtied_before)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582347504,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1296",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071588799326,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:698",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dec_pending"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347504,
      "name": "queue_io",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work, long unsigned int dirtied_before)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582374560,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1302",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071588684049,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:703",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dec_pending"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582374560,
      "name": "queue_io",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work, long unsigned int dirtied_before)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582695808,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1445",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071589376593,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:583",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_io_dec_pending"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695808,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work, long unsigned int dirtied_before)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583244832,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1416",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071590850033,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:667",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_io_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244832,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work, long unsigned int dirtied_before)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583826576,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1427",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071592541105,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:661",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:__dm_io_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826576,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work, long unsigned int dirtied_before)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584044112,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1432",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071592972334,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:668",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:__dm_io_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584044112,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work, long unsigned int dirtied_before)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584258912,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1449",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071593722269,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:670",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:__dm_io_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258912,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493591760,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446603336501153416,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493591760,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446603336501153416,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227129556,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 3233663312,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227129556,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 3233663312,
      "name": "queue_io",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287165152,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 13835058055294658752,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287165152,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 13835058055294658752,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273235814,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446743936277861876,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273235814,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446743936277861876,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023216,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071587548880,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023216,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587548880,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960784,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071587316976,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960784,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587316976,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582014496,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071587874048,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014496,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587874048,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_io(struct bdi_writeback * wb, struct wb_writeback_work * work)
```

```json
{
  "name": "queue_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582085472,
      "name": "queue_io",
      "external": false,
      "loc": "fs/fs-writeback.c:1292",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_writeback"
      ]
    },
    {
      "addr": 18446744071587989312,
      "name": "queue_io",
      "external": false,
      "loc": "drivers/md/dm.c:689",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085472,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071587989312,
      "name": "queue_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int dirtied_before</code>
</li>
</ul>
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
