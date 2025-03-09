# Function: <code>idr_for_each</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int idr_for_each(struct idr * idp, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948288,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:686",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "lib/idr.c:idr_is_empty",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948288,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int idr_for_each(struct idr * idp, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236000,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:686",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "lib/idr.c:idr_is_empty",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236000,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int idr_for_each(struct idr * idp, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351248,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:686",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "lib/idr.c:idr_is_empty",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351248,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588203184,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:97",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588203184,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588752048,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:84",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588752048,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130384,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:198",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130384,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589364768,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:194",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364768,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821792,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821792,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590048080,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048080,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585042048,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/io_uring.c:__io_uring_show_fdinfo",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid_one",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:unhash_nsid",
        "net/core/net_namespace.c:peernet_has_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042048,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193776,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/io_uring.c:__io_uring_show_fdinfo",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid_one",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:unhash_nsid",
        "net/core/net_namespace.c:peernet_has_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193776,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076864,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid_one",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:peernet_has_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076864,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523696,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid_one",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:peernet_has_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523696,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676768,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid_one",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:peernet_has_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676768,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595756912,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid_one",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:peernet_has_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595756912,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596281232,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid_one",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:peernet_has_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596281232,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597165936,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/gpu/drm/drm_gem.c:drm_gem_release",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_release",
        "drivers/gpu/drm/drm_debugfs.c:drm_gem_name_info",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid_one",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:peernet_has_id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597165936,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503822744,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/firmware/arm_scmi/driver.c:scmi_remove",
        "drivers/firmware/arm_scmi/driver.c:scmi_remove",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503822744,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236444240,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/firmware/arm_scmi/driver.c:scmi_remove",
        "drivers/firmware/arm_scmi/driver.c:scmi_remove",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236444240,
      "name": "idr_for_each",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297667584,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297667584,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279718150,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279718150,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650336,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650336,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589376144,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376144,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590093712,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590093712,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int idr_for_each(const struct idr * idr, int (*)(int, void *, void *) fn, void * data)
```

```json
{
  "name": "idr_for_each",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590143968,
      "name": "idr_for_each",
      "external": true,
      "loc": "lib/idr.c:195",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/shm.c:shm_destroy_orphaned",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_unregister_transfer",
        "drivers/scsi/sg.c:dev_seq_start",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590143968,
      "name": "idr_for_each",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct idr * idr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct idr * idp</code>
</li>
</ul>
</details>
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
