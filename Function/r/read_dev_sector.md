# Function: <code>read_dev_sector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830576,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:560",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830576,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110112,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:577",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110112,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583221632,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:642",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221632,
      "name": "read_dev_sector",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275728,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:634",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275728,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583455952,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:646",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583455952,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667360,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:652",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667360,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774464,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:655",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774464,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964304,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964304,
      "name": "read_dev_sector",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067648,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067648,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495911000,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495911000,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229251712,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229251712,
      "name": "read_dev_sector",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290119824,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290119824,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275024998,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275024998,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584036384,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036384,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972144,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972144,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020144,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020144,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
```

```json
{
  "name": "read_dev_sector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122688,
      "name": "read_dev_sector",
      "external": true,
      "loc": "block/partition-generic.c:662",
      "file": "block/partition-generic.c",
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
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122688,
      "name": "read_dev_sector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
unsigned char * read_dev_sector(struct block_device * bdev, sector_t n, Sector * p)
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
