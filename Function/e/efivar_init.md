# Function: <code>efivar_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool atomic, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994720,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:428",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994720,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586400512,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:421",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586400512,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586610768,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:429",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610768,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586735920,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:429",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735920,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587220368,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:429",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587220368,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:429",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587522279,
      "name": "efivar_init.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071587521312,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:439",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703107,
      "name": "efivar_init.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071587702096,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 913
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efivar_ssdt_load",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982115,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587981168,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efivar_ssdt_load",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189315,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071588188368,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589054648,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071589053040,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:414",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591606201,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071589061584,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:414",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591550034,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588948272,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:414",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592669464,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071589656768,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:414",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594554804,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071591159504,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585378496,
      "name": "efivar_init",
      "external": true,
      "loc": "fs/efivarfs/vars.c:372",
      "file": "fs/efivarfs/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378496,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585609408,
      "name": "efivar_init",
      "external": true,
      "loc": "fs/efivarfs/vars.c:372",
      "file": "fs/efivarfs/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609408,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *, struct list_head *) func, void * data, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585856096,
      "name": "efivar_init",
      "external": true,
      "loc": "fs/efivarfs/vars.c:371",
      "file": "fs/efivarfs/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856096,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 821
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501543880,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501543880,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234058140,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234058140,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efivar_ssdt_load",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807747,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587806800,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efivar_ssdt_load",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587511171,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587510224,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efivar_ssdt_load",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588143843,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071588142896,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```

```json
{
  "name": "efivar_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_init",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:426",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/efivarfs/super.c:efivarfs_fill_super",
        "drivers/firmware/efi/efi.c:efivar_ssdt_load",
        "drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588261363,
      "name": "efivar_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071588260416,
      "name": "efivar_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool atomic</code>
</li>
<li>
<b>Param reordered. </b>
<code>func, data, atomic, duplicates, head</code> ➡️ <code>func, data, duplicates, head</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool duplicates</code>
</li>
<li>
<b>Param reordered. </b>
<code>func, data, duplicates, head</code> ➡️ <code>func, data, head</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func</code> ➡️ <code>int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *, struct list_head *) func</code>
</li>
</ul>
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
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int efivar_init(int (*)(efi_char16_t *, efi_guid_t, long unsigned int, void *) func, void * data, bool duplicates, struct list_head * head)
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
