# Function: <code>parse_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581703840,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:1720",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071581975424,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1022",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071582120560,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:248",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071595257344,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:64",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703840,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    },
    {
      "addr": 18446744071581975424,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1397
    },
    {
      "addr": 18446744071582120560,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581896080,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:1837",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582187424,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1105",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071582338848,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:247",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071595438560,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:91",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896080,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446744071582187424,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1546
    },
    {
      "addr": 18446744071582338848,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581985584,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:1864",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582276864,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1105",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071582429648,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:252",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071595690912,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:91",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985584,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
    },
    {
      "addr": 18446744071582276864,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1546
    },
    {
      "addr": 18446744071582429648,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582202048,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:1922",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582361488,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1105",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071582513328,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:261",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071596615325,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:91",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202048,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071582361488,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1442
    },
    {
      "addr": 18446744071582513328,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582350800,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:1925",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582512288,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1105",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071582665168,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:239",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071602945686,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350800,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071582512288,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1429
    },
    {
      "addr": 18446744071582665168,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582539664,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:1963",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1128",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071582858608,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:239",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071603118489,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539664,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071582702000,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
    },
    {
      "addr": 18446744071582711094,
      "name": "parse_options.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071582858608,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582640832,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2019",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1120",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071582966496,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:239",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071604921199,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640832,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071582805344,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
    },
    {
      "addr": 18446744071582814630,
      "name": "parse_options.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071582966496,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582813488,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2063",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1115",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583147392,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071605030277,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582813488,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071582980160,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
    },
    {
      "addr": 18446744071582989597,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583147392,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582916832,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583253488,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071605066886,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916832,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071583086400,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
    },
    {
      "addr": 18446744071583095805,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583253488,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583233136,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2210",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583580224,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:239",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071609355460,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233136,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
    },
    {
      "addr": 18446744071583405744,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1703
    },
    {
      "addr": 18446744071583415044,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071583580224,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071609355460,
      "name": "parse_options.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583334800,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2413",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1126",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583700624,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:239",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071612426557,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:93",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334800,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
    },
    {
      "addr": 18446744071583521280,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1703
    },
    {
      "addr": 18446744071591352907,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071583700624,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071612426557,
      "name": "parse_options.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, struct ext4_parsed_options * ret_opts, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583357424,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2440",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1126",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583725504,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:239",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071614567718,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:93",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357424,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    },
    {
      "addr": 18446744071583544416,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1721
    },
    {
      "addr": 18446744071591295823,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583725504,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071614567718,
      "name": "parse_options.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, struct ext4_parsed_options * ret_opts, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071584086704,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:239",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071615522281,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:93",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701632,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071592270707,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583902448,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1721
    },
    {
      "addr": 18446744071592280132,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584086704,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071615522281,
      "name": "parse_options.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(struct fs_context * fc, char * options)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584255184,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2393",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1131",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071584680912,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:239",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071617326783,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:93",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255184,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071584480048,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1662
    },
    {
      "addr": 18446744071594062456,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071584680912,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071617326783,
      "name": "parse_options.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(struct fs_context * fc, char * options)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584902544,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2370",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071585144672,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1126",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071585366288,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:240",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071628052576,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:93",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:register_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902544,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071585144672,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1732
    },
    {
      "addr": 18446744071585366288,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071628052576,
      "name": "parse_options.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(struct fs_context * fc, char * options)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585131280,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2437",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071585373792,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1126",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071585596688,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:240",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071619818784,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:93",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:register_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585131280,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071585373792,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1767
    },
    {
      "addr": 18446744071585596688,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071619818784,
      "name": "parse_options.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(struct fs_context * fc, char * options)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585363184,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2454",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:parse_apply_sb_mount_options"
      ]
    },
    {
      "addr": 18446744071585608528,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1134",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071585842240,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:237",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071622127488,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:93",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/earlycon.c:register_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363184,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071585608528,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1767
    },
    {
      "addr": 18446744071585842240,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071622127488,
      "name": "parse_options.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 453
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494593200,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446603336494793024,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446603336494981008,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446603336511209224,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494593200,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446603336494793024,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1512
    },
    {
      "addr": 18446603336494981008,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228036160,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 3228214480,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 3228386808,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 3243853768,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228036160,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 3228214480,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1704
    },
    {
      "addr": 3228386808,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288394352,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 13835058055288630880,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 13835058055288862992,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 13835058055302771416,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288394352,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 13835058055288630880,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2528
    },
    {
      "addr": 13835058055288862992,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273971328,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446743936274123274,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446743936274281120,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446743936270789718,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273971328,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446743936274123274,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
    },
    {
      "addr": 18446743936274281120,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582885568,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583222224,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071604966509,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885568,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071583055136,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
    },
    {
      "addr": 18446744071583064541,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583222224,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582822720,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583159376,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071604930848,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582822720,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071582992288,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
    },
    {
      "addr": 18446744071583001693,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583159376,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582874432,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583206256,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071605047209,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874432,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071583043744,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
    },
    {
      "addr": 18446744071583053149,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583206256,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int parse_options(char * options, struct super_block * sb, long unsigned int * journal_devnum, unsigned int * journal_ioprio, int is_remount)
```

```json
{
  "name": "parse_options",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582961152,
      "name": "parse_options",
      "external": false,
      "loc": "fs/ext4/super.c:2066",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 0,
      "name": "parse_options",
      "external": false,
      "loc": "fs/fat/inode.c:1127",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_fill_super"
      ]
    },
    {
      "addr": 18446744071583300144,
      "name": "parse_options",
      "external": false,
      "loc": "fs/pstore/inode.c:227",
      "file": "fs/pstore/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_remount"
      ]
    },
    {
      "addr": 18446744071605071080,
      "name": "parse_options",
      "external": false,
      "loc": "drivers/tty/serial/earlycon.c:88",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/earlycon.c:setup_earlycon"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961152,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071583134160,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
    },
    {
      "addr": 18446744071583142413,
      "name": "parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583300144,
      "name": "parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_parsed_options * ret_opts</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * journal_devnum</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * journal_ioprio</code>
</li>
<li>
<b>Param reordered. </b>
<code>options, sb, journal_devnum, journal_ioprio, is_remount</code> ➡️ <code>options, sb, ret_opts, is_remount</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fs_context * fc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct super_block * sb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ext4_parsed_options * ret_opts</code>
</li>
<li>
<b>Param removed. </b>
<code>int is_remount</code>
</li>
<li>
<b>Param reordered. </b>
<code>options, sb, ret_opts, is_remount</code> ➡️ <code>fc, options</code>
</li>
</ul>
</details>
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
