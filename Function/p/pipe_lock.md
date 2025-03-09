# Function: <code>pipe_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581026736,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:68",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:splice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026736,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581187036,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:69",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/splice.c:splice_to_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185856,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581264252,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:69",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263072,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581313196,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:69",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312112,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581453372,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:70",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:SyS_splice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581452144,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581613004,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:65",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611776,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699356,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:65",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698128,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581817099,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815760,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581889659,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888320,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582117102,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:69",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115760,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582163470,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:69",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162192,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582187966,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:84",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186704,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582505342,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:84",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504080,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583031326,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:85",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583027296,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583595598,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:85",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:generic_splice_sendpage",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591376,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583812366,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:85",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583807936,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584018366,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:85",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_wait_writable",
        "fs/pipe.c:pipe_wait_readable"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_filter",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014160,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493367668,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493365368,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226954768,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226953068,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286913992,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286911168,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273087366,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273085674,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581858395,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857056,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581795995,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794656,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581849707,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848368,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void pipe_lock(struct pipe_inode_info * pipe)
```

```json
{
  "name": "pipe_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581919211,
      "name": "pipe_lock",
      "external": true,
      "loc": "fs/pipe.c:66",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_wait"
      ],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:splice_from_pipe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "fs/fuse/dev.c:fuse_dev_splice_write",
        "drivers/char/virtio_console.c:port_fops_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917888,
      "name": "pipe_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
