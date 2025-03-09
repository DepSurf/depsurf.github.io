# Function: <code>percpu_free_rwsem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673136,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:27",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673136,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691536,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:27",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691536,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719248,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:27",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719248,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579715168,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:26",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715168,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579747792,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:26",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747792,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579782176,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:26",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782176,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579828736,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:26",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828736,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579863152,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863152,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579911856,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911856,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579955632,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:31",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955632,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579943792,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:31",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943792,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579951536,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:31",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951536,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580080384,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:31",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080384,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580215600,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:33",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215600,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580408304,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:33",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408304,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580477072,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:33",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477072,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580536896,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:33",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_percpu_param_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536896,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491115248,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491115248,
      "name": "percpu_free_rwsem",
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225117712,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225117712,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284007104,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284007104,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271692388,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271692388,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579883968,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883968,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579818944,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818944,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872128,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872128,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void percpu_free_rwsem(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_free_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917648,
      "name": "percpu_free_rwsem",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:29",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/super.c:destroy_super_work",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917648,
      "name": "percpu_free_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
