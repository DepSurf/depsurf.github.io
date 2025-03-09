# Function: <code>__efivar_entry_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585992608,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1029",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/vars.c:efivar_entry_iter"
      ],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585992608,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586400165,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1020",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/vars.c:efivar_entry_iter"
      ],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398752,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586609664,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1041",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586609664,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586735408,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1041",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735408,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587219856,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1041",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587219856,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587520800,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1041",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520800,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587701024,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1098",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587701024,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587979168,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587979168,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588186368,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186368,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589048976,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048976,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589057600,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1077",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589057600,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588944848,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1077",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944848,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589653392,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1080",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653392,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591155808,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1080",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591155808,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501541928,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501541928,
      "name": "__efivar_entry_iter",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234056104,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234056104,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587804800,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587804800,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587508224,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587508224,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588140896,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140896,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```

```json
{
  "name": "__efivar_entry_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588258416,
      "name": "__efivar_entry_iter",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1085",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_kill_sb",
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258416,
      "name": "__efivar_entry_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __efivar_entry_iter(int (*)(struct efivar_entry *, void *) func, struct list_head * head, void * data, struct efivar_entry * * prev)
```
</details>
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
