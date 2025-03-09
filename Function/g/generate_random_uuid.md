# Function: <code>generate_random_uuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void generate_random_uuid(unsigned char * uuid_out)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584168544,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "drivers/char/random.c:1634",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584168544,
      "name": "generate_random_uuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583309216,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:39",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309216,
      "name": "generate_random_uuid",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428528,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:39",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428528,
      "name": "generate_random_uuid",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583449840,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:42",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449840,
      "name": "generate_random_uuid",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629936,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:42",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629936,
      "name": "generate_random_uuid",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846496,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:41",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846496,
      "name": "generate_random_uuid",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930208,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:41",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930208,
      "name": "generate_random_uuid",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584109760,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109760,
      "name": "generate_random_uuid",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584232608,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232608,
      "name": "generate_random_uuid",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584639472,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639472,
      "name": "generate_random_uuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584759008,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759008,
      "name": "generate_random_uuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787440,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787440,
      "name": "generate_random_uuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218208,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218208,
      "name": "generate_random_uuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586056016,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056016,
      "name": "generate_random_uuid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039904,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039904,
      "name": "generate_random_uuid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587296992,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587296992,
      "name": "generate_random_uuid",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587582816,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587582816,
      "name": "generate_random_uuid",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496108136,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496108136,
      "name": "generate_random_uuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229433320,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229433320,
      "name": "generate_random_uuid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290356320,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290356320,
      "name": "generate_random_uuid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275173676,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275173676,
      "name": "generate_random_uuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201344,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201344,
      "name": "generate_random_uuid",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584136560,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136560,
      "name": "generate_random_uuid",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584185104,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185104,
      "name": "generate_random_uuid",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char * uuid)
```

```json
{
  "name": "generate_random_uuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289456,
      "name": "generate_random_uuid",
      "external": true,
      "loc": "lib/uuid.c:33",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289456,
      "name": "generate_random_uuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<b>Param added. </b>
<code>unsigned char * uuid</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char * uuid_out</code>
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
