# Function: <code>percpu_down_read_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int percpu_down_read_trylock(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673184,
      "name": "percpu_down_read_trylock",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:85",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673184,
      "name": "percpu_down_read_trylock",
      "section": ".text",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int percpu_down_read_trylock(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579692016,
      "name": "percpu_down_read_trylock",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:86",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692016,
      "name": "percpu_down_read_trylock",
      "section": ".text",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581240305,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:62",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581287677,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:62",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581427213,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:63",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581582119,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:63",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579466965,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:63",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668455,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:63",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579483509,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785833,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579509493,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581858105,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579538325,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082818,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579520485,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580310918,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166188,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266328,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019035,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297250,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579523813,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314294,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189919,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291656,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044843,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321378,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579595893,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580467830,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507231,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582610456,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382123,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583665074,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579688037,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661383,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583030543,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143383,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583895356,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234099,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579811317,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931239,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594799,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715351,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520572,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584877658,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579859669,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017652,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583811472,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933079,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584749420,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585104858,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579897541,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113524,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017623,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584139398,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584982300,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585337226,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:73",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490646176,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493327176,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224722516,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 3226926476,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283466640,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286872976,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273059638,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579483157,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581826841,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579412037,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764505,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579483077,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581818153,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read_trylock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579515925,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581890203,
      "name": "percpu_down_read_trylock",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:61",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int percpu_down_read_trylock(struct percpu_rw_semaphore * brw)
```
</details>
</li>
</ul>
