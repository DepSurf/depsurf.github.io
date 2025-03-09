# Function: <code>__percpu_init_rwsem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore * brw, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672576,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:11",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init",
        "kernel/events/uprobes.c:init_uprobes",
        "fs/super.c:sget_userns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672576,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * brw, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691408,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:11",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init",
        "kernel/events/uprobes.c:init_uprobes",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691408,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719120,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:11",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init",
        "kernel/events/uprobes.c:init_uprobes",
        "fs/super.c:sget_userns",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719120,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714976,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:10",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/events/uprobes.c:init_uprobes",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714976,
      "name": "__percpu_init_rwsem",
      "section": ".text",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747584,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:10",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/events/uprobes.c:init_uprobes",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747584,
      "name": "__percpu_init_rwsem",
      "section": ".text",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781968,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:10",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/events/uprobes.c:init_uprobes",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781968,
      "name": "__percpu_init_rwsem",
      "section": ".text",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828528,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:10",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/events/uprobes.c:init_uprobes",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828528,
      "name": "__percpu_init_rwsem",
      "section": ".text",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579862944,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862944,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911648,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911648,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955456,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:12",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955456,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943616,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:12",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943616,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951360,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:12",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951360,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080208,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:12",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080208,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215392,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:14",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215392,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408064,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:14",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408064,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476832,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:14",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_percpu_param_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476832,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580536656,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:14",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_percpu_param_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536656,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491115056,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491115056,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225117228,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225117228,
      "name": "__percpu_init_rwsem",
      "section": ".text",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284006384,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284006384,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271691938,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271691938,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883760,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883760,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818736,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818736,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871920,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871920,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __percpu_init_rwsem(struct percpu_rw_semaphore * sem, const char * name, struct lock_class_key * rwsem_key)
```

```json
{
  "name": "__percpu_init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917440,
      "name": "__percpu_init_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:13",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "fs/super.c:alloc_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917440,
      "name": "__percpu_init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct percpu_rw_semaphore * sem</code>
</li>
<li>
<b>Param removed. </b>
<code>struct percpu_rw_semaphore * brw</code>
</li>
</ul>
</details>
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
<code>struct lock_class_key * key</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lock_class_key * rwsem_key</code>
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
