# Function: <code>read_part_sector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582836116,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582837186,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582839159,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582841666,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846609,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582851538,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
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
      "caller_func": []
    },
    {
      "addr": 18446744071582855586,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856002,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856450,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857250,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857736,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861922,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862418,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583118913,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120926,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583122990,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125756,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583131623,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138997,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
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
      "caller_func": []
    },
    {
      "addr": 18446744071583140603,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141131,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141675,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142587,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143196,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583147483,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583148107,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583230833,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583232846,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234910,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583237676,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243543,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250917,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
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
      "caller_func": []
    },
    {
      "addr": 18446744071583252523,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583253051,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583253595,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254507,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255116,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259403,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260027,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583284913,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583286424,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288302,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583290886,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583296727,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303671,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
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
      "caller_func": []
    },
    {
      "addr": 18446744071583304923,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305367,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305899,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583306711,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583307247,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311271,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311819,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:30",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583465158,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583466872,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583469038,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471815,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583477959,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485580,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071583487147,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487703,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583488331,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489223,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489839,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583493911,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494571,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583677729,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583679945,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583681582,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583684686,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583689415,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698261,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071583699915,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700487,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701147,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702055,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702675,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707145,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707819,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583785009,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583787241,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583788878,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583791982,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583796839,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805717,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071583807371,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583807943,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808603,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583809513,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583810131,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814121,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814795,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583974801,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583977095,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583978750,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583981882,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988548,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995795,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071583997419,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583997993,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998667,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583999579,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584000203,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004251,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004923,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584078161,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584080894,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082126,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584085258,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584091924,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584099159,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071584100779,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584101353,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102027,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102939,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103559,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584107611,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584108283,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```

```json
{
  "name": "read_part_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584472432,
      "name": "read_part_sector",
      "external": true,
      "loc": "block/partitions/core.c:761",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584472432,
      "name": "read_part_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```

```json
{
  "name": "read_part_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584586608,
      "name": "read_part_sector",
      "external": true,
      "loc": "block/partitions/core.c:685",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584586608,
      "name": "read_part_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```

```json
{
  "name": "read_part_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618656,
      "name": "read_part_sector",
      "external": true,
      "loc": "block/partitions/core.c:662",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618656,
      "name": "read_part_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```

```json
{
  "name": "read_part_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585033392,
      "name": "read_part_sector",
      "external": true,
      "loc": "block/partitions/core.c:717",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585033392,
      "name": "read_part_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```

```json
{
  "name": "read_part_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585750576,
      "name": "read_part_sector",
      "external": true,
      "loc": "block/partitions/core.c:705",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:read_lba",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585750576,
      "name": "read_part_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```

```json
{
  "name": "read_part_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_part_sector",
      "external": true,
      "loc": "block/partitions/core.c:707",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:read_lba",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596108583,
      "name": "read_part_sector.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586533856,
      "name": "read_part_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```

```json
{
  "name": "read_part_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_part_sector",
      "external": true,
      "loc": "block/partitions/core.c:707",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:read_lba",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596632386,
      "name": "read_part_sector.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586780352,
      "name": "read_part_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```

```json
{
  "name": "read_part_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_part_sector",
      "external": true,
      "loc": "block/partitions/core.c:716",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:read_lba",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597538709,
      "name": "read_part_sector.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587057088,
      "name": "read_part_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495920348,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495923044,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495924332,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495927524,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495935636,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495941952,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446603336495943920,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495944632,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495945368,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495946348,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495947720,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495950768,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495951512,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229263764,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229266584,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229267800,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229271292,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229279824,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 3229285324,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 3229287104,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229287632,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229288256,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229289164,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229289928,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 3229294292,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229294972,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290132092,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290135988,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290137640,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290141876,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290153104,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290160864,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 13835058055290162560,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290163632,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290164584,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290165840,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290166796,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290172032,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290173072,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275032640,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275035878,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275037132,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275039744,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275048108,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275052772,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446743936275053834,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275054228,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275054890,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275055760,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275056188,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275061410,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275061874,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584046897,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584049630,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584050862,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584053994,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060660,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584067895,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071584069515,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070089,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070763,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584071675,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072295,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076347,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584077019,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583982657,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583985390,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583986622,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583989754,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583996420,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584003655,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071584005275,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005849,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006523,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584007435,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584008055,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012107,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012779,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584030657,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584033390,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034622,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037754,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044420,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584051655,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071584053275,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584053849,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584054523,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055435,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056055,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060107,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060779,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
  "name": "read_part_sector",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584133153,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584135886,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137118,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584140250,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146916,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584154151,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
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
      "caller_func": []
    },
    {
      "addr": 18446744071584155771,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584156345,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157019,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157931,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158551,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584162603,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584163275,
      "name": "read_part_sector",
      "external": false,
      "loc": "block/partitions/check.h:31",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * read_part_sector(struct parsed_partitions * state, sector_t n, Sector * p)
```
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
