# Function: <code>put_partition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582835888,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071582837620,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582839825,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840992,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582841936,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582850879,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582851360,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_minix"
      ]
    },
    {
      "addr": 18446744071582855733,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856147,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856685,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857374,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860822,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862011,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862224,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835888,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071582840992,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071582851360,
      "name": "put_partition.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582862224,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583118688,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071583120578,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123262,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124672,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583125698,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134846,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138855,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071583140757,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141278,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141897,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142778,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583146265,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583147583,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583147920,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583118688,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071583124672,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071583135504,
      "name": "put_partition.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583147920,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583230608,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071583232498,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235182,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236592,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583237618,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246766,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250775,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071583252677,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583253198,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583253817,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254698,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258185,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259503,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259840,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230608,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071583236592,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071583247424,
      "name": "put_partition.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583259840,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583284672,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071583286288,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288707,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583289904,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583290948,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583299486,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303063,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071583305088,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305512,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583306145,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583306877,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310191,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311506,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311632,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:41",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284672,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071583289904,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071583300464,
      "name": "put_partition.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583311632,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583464912,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071583466736,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583469392,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583470784,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583471877,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480880,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583484926,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071583487312,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487848,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583488577,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489431,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492831,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494202,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494384,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583464912,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071583470784,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071583481904,
      "name": "put_partition.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583494384,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583677536,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071583679573,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583682875,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683328,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583684767,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583691837,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698909,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071583700103,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700631,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701367,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702285,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583706041,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707348,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707632,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677536,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583683328,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583694560,
      "name": "put_partition.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583707632,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583784816,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071583786869,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790171,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790624,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583792063,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799274,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583806365,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071583807559,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808087,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808827,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583809746,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813160,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814324,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814608,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583784816,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583790624,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583802016,
      "name": "put_partition.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583814608,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583974608,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071583976669,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583980117,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583980544,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583981971,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583989426,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583996442,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071583997579,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998134,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998886,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583999816,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584003320,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004458,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004736,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974608,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583980544,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583992112,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584004736,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584077968,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071584079895,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584083493,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584083920,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584085347,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584092802,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584099806,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071584100939,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584101494,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102246,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103176,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106686,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584107818,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584108096,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077968,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584083920,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584095488,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584108096,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584473104,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071584474944,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584478430,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584478864,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584480285,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584485659,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_create_data_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584495344,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071584496409,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497004,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497729,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584498611,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584502328,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584503423,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584503632,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473104,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071584478864,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071584491088,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071584503632,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584586864,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071584588681,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592007,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592384,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584593725,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584599051,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_create_data_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584606240,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071584607305,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584607900,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584608611,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584609520,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584613170,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584613916,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614112,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584586864,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071584592384,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071584602080,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071584614112,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618912,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071584620729,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584624055,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584624432,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584625732,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584630377,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_create_data_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584637899,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071584638889,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584639483,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640201,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584641072,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584644778,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584645516,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584645712,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618912,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071584624432,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071584633712,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071584645712,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585033632,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071585035286,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585038673,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585039040,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/cmdline.c:cmdline_partition"
      ]
    },
    {
      "addr": 18446744071585041716,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585046089,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_create_data_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585054206,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071585055481,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585056062,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585056741,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585057709,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585061705,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585062441,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585062640,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:38",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585033632,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071585039040,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071585050016,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071585062640,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585750944,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071585753061,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585757063,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585757472,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/cmdline.c:cmdline_partition"
      ]
    },
    {
      "addr": 18446744071585760459,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585765273,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_create_data_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585775245,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071585776893,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777752,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778781,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585779833,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585784038,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585784835,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785248,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585750944,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071585757472,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071585769760,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071585785248,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586534096,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071586535885,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586538941,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586539344,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/cmdline.c:cmdline_partition"
      ]
    },
    {
      "addr": 18446744071586542486,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586548649,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_create_data_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586557624,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": [
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071586558733,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559188,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559751,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586560556,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586564878,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586565685,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586565888,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534096,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071586539344,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071586553312,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071586565888,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586780576,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071586784351,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ]
    },
    {
      "addr": 18446744071586785856,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/aix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071586788912,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/cmdline.c:add_part"
      ]
    },
    {
      "addr": 18446744071586792320,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/mac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/mac.c:mac_partition"
      ]
    },
    {
      "addr": 18446744071586795344,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_create_data_partitions"
      ]
    },
    {
      "addr": 18446744071586811157,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended"
      ]
    },
    {
      "addr": 18446744071586812336,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/osf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/osf.c:osf_partition"
      ]
    },
    {
      "addr": 18446744071586813216,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sgi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sgi.c:sgi_partition"
      ]
    },
    {
      "addr": 18446744071586814144,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sun.c:sun_partition"
      ]
    },
    {
      "addr": 18446744071586815456,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/ultrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ultrix.c:ultrix_partition"
      ]
    },
    {
      "addr": 18446744071586817184,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    },
    {
      "addr": 18446744071586821552,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/karma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/karma.c:karma_partition"
      ]
    },
    {
      "addr": 18446744071586822400,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780576,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586783456,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071586785856,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586788912,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586792320,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586795344,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586804432,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071586812336,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586813216,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586814144,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586815456,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586817184,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586821552,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071586822400,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587057328,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071587061103,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ]
    },
    {
      "addr": 18446744071587062608,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/aix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071587065664,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/cmdline.c:add_part"
      ]
    },
    {
      "addr": 18446744071587069152,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/mac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/mac.c:mac_partition"
      ]
    },
    {
      "addr": 18446744071587072176,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_create_data_partitions"
      ]
    },
    {
      "addr": 18446744071587088197,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended"
      ]
    },
    {
      "addr": 18446744071587089376,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/osf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/osf.c:osf_partition"
      ]
    },
    {
      "addr": 18446744071587090256,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sgi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sgi.c:sgi_partition"
      ]
    },
    {
      "addr": 18446744071587091184,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sun.c:sun_partition"
      ]
    },
    {
      "addr": 18446744071587092496,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/ultrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ultrix.c:ultrix_partition"
      ]
    },
    {
      "addr": 18446744071587094224,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    },
    {
      "addr": 18446744071587098640,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/karma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/karma.c:karma_partition"
      ]
    },
    {
      "addr": 18446744071587099488,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:37",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057328,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587060208,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071587062608,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587065664,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587069152,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587072176,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587081472,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071587089376,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587090256,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587091184,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587092496,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587094224,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587098640,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071587099488,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495920104,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446603336495922076,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495925648,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495926136,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495927616,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495937040,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495941856,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446603336495944080,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495944792,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495945620,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495946596,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495950072,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495951036,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495951304,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495920104,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336495926136,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336495938304,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446603336495951304,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229263508,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 3229265644,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229269076,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229269416,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229271364,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229280740,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229286804,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 3229287284,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229287812,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229288528,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229289416,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229293496,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229294572,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229294744,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229263508,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 3229269416,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 3229281508,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3229294744,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290131776,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 13835058055290136040,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290139552,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290140000,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290141952,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290154284,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290161612,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 13835058055290162780,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290163844,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290164888,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290166240,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290171304,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290172380,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290172816,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290131776,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 13835058055290140000,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 13835058055290155264,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 13835058055290172816,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275032478,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446743936275034506,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275037892,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275038628,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275039694,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275048852,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275052694,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446743936275053914,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275054392,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275055124,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275055886,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275060330,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275061476,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275061744,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275038628,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446743936275032478,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446743936275049612,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446743936275061744,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584046704,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071584048631,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584052229,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584052656,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584054083,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061538,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584068542,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071584069675,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070230,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070982,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584071912,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584075422,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076554,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076832,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584046704,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584052656,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584064224,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584076832,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583982464,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071583984391,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583987989,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988416,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583989843,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583997298,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004302,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071584005435,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005990,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006742,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584007672,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584011182,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012314,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012592,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982464,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583988416,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071583999984,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584012592,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584030464,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071584032391,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584035989,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584036416,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584037843,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584045298,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584052302,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071584053435,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584053990,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584054742,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055672,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584059182,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060314,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060592,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030464,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584036416,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584047984,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584060592,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void put_partition(struct parsed_partitions * p, int n, sector_t from, sector_t size)
```

```json
{
  "name": "put_partition",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584132960,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/amiga.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition"
      ]
    },
    {
      "addr": 18446744071584134887,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138485,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138912,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584140339,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147794,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584154798,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware"
      ]
    },
    {
      "addr": 18446744071584155931,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584156486,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157238,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158168,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161678,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584162810,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584163088,
      "name": "put_partition",
      "external": false,
      "loc": "block/partitions/check.h:42",
      "file": "block/partitions/sysv68.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132960,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584138912,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584150480,
      "name": "put_partition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584163088,
      "name": "put_partition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
