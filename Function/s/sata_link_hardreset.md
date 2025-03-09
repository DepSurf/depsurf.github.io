# Function: <code>sata_link_hardreset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584935520,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:3768",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584935520,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585299008,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:3944",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299008,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585498784,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:3986",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585498784,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585582752,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4063",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585582752,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586014448,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4073",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014448,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4069",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266329,
      "name": "sata_link_hardreset.cold.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071586259264,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4070",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586406792,
      "name": "sata_link_hardreset.cold.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071586399712,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651485,
      "name": "sata_link_hardreset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586643840,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798850,
      "name": "sata_link_hardreset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586791392,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587662128,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:529",
      "file": "drivers/ata/libata-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587662128,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587723072,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:529",
      "file": "drivers/ata/libata-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723072,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587602208,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:529",
      "file": "drivers/ata/libata-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587602208,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588186640,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:529",
      "file": "drivers/ata/libata-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186640,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:529",
      "file": "drivers/ata/libata-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-sff.c:sata_sff_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594413583,
      "name": "sata_link_hardreset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071589569152,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591163472,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:529",
      "file": "drivers/ata/libata-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-sff.c:sata_sff_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591163472,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591522624,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:531",
      "file": "drivers/ata/libata-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-sff.c:sata_sff_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591522624,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int sata_link_hardreset(struct ata_link * link, const unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591871040,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:544",
      "file": "drivers/ata/libata-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-sff.c:sata_sff_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591871040,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499717528,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libahci.c:ahci_do_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499717528,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232165032,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libahci.c:ahci_do_hardreset",
        "drivers/ata/sata_highbank.c:ahci_highbank_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232165032,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293053152,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293053152,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276882974,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276882974,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586557465,
      "name": "sata_link_hardreset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586550000,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426041,
      "name": "sata_link_hardreset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586418576,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586753410,
      "name": "sata_link_hardreset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586745952,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int sata_link_hardreset(struct ata_link * link, const long unsigned int * timing, long unsigned int deadline, bool * online, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "sata_link_hardreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sata_link_hardreset",
      "external": true,
      "loc": "drivers/ata/libata-core.c:4054",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_std_hardreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859474,
      "name": "sata_link_hardreset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586852016,
      "name": "sata_link_hardreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const long unsigned int * timing</code> ➡️ <code>const unsigned int * timing</code>
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
