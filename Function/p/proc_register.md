# Function: <code>proc_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581463056,
      "name": "proc_register",
      "external": false,
      "loc": "fs/proc/generic.c:336",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_create_data",
        "fs/proc/generic.c:proc_create_mount_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463056,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647440,
      "name": "proc_register",
      "external": false,
      "loc": "fs/proc/generic.c:340",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_data",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647440,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581735744,
      "name": "proc_register",
      "external": false,
      "loc": "fs/proc/generic.c:340",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_data",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735744,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581788976,
      "name": "proc_register",
      "external": false,
      "loc": "fs/proc/generic.c:323",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_data",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788976,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581938448,
      "name": "proc_register",
      "external": false,
      "loc": "fs/proc/generic.c:325",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_data",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938448,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123536,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:350",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123536,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217984,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:350",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217984,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382144,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382144,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481056,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481056,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582779728,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:362",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779728,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582853024,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:372",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582853024,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582881184,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:367",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881184,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214800,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:367",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214800,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712032,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:367",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712032,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584323456,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:367",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584323456,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553472,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:366",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553472,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584785328,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:366",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir",
        "fs/proc/generic.c:proc_mkdir_mode",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785328,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494102624,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494102624,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227552476,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227552476,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287770896,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_data",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287770896,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273589218,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273589218,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449792,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449792,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582386960,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386960,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440272,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440272,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct proc_dir_entry * proc_register(struct proc_dir_entry * dir, struct proc_dir_entry * dp)
```

```json
{
  "name": "proc_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582520448,
      "name": "proc_register",
      "external": true,
      "loc": "fs/proc/generic.c:351",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_create_single_data",
        "fs/proc/generic.c:proc_create_seq_private",
        "fs/proc/generic.c:proc_create_mount_point",
        "fs/proc/generic.c:proc_mkdir_data",
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/proc_net.c:proc_create_net_single_write",
        "fs/proc/proc_net.c:proc_create_net_single",
        "fs/proc/proc_net.c:proc_create_net_data_write",
        "fs/proc/proc_net.c:proc_create_net_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520448,
      "name": "proc_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct proc_dir_entry *</code>
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
