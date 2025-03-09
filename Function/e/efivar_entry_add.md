# Function: <code>efivar_entry_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585993872,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:517",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993872,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586399920,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:507",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586399920,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586607456,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:524",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607456,
      "name": "efivar_entry_add",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586732608,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:524",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586732608,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587217024,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:524",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587217024,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587517360,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:524",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517360,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587697920,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:539",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697920,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977280,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977280,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588184480,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184480,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589050480,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589050480,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589059072,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:518",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589059072,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588946032,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:518",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946032,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589654448,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:518",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589654448,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591156896,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:518",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591156896,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585379248,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "fs/efivarfs/vars.c:457",
      "file": "fs/efivarfs/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585379248,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585610224,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "fs/efivarfs/vars.c:457",
      "file": "fs/efivarfs/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585610224,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585856944,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "fs/efivarfs/vars.c:461",
      "file": "fs/efivarfs/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/inode.c:efivarfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856944,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501539808,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501539808,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234054044,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234054044,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587802912,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587802912,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587506336,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506336,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588139008,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588139008,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```

```json
{
  "name": "efivar_entry_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588256528,
      "name": "efivar_entry_add",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:526",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/firmware/efi/efi.c:efivar_ssdt_iter",
        "drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256528,
      "name": "efivar_entry_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int efivar_entry_add(struct efivar_entry * entry, struct list_head * head)
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
