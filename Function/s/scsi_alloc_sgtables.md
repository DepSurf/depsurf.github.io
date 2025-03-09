# Function: <code>scsi_alloc_sgtables</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
blk_status_t scsi_alloc_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_alloc_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587526640,
      "name": "scsi_alloc_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1008",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587526640,
      "name": "scsi_alloc_sgtables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
blk_status_t scsi_alloc_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_alloc_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587407984,
      "name": "scsi_alloc_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:980",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407984,
      "name": "scsi_alloc_sgtables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
blk_status_t scsi_alloc_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_alloc_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587980000,
      "name": "scsi_alloc_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:980",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587980000,
      "name": "scsi_alloc_sgtables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 989
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
blk_status_t scsi_alloc_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_alloc_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589337152,
      "name": "scsi_alloc_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1014",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589337152,
      "name": "scsi_alloc_sgtables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
blk_status_t scsi_alloc_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_alloc_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590903456,
      "name": "scsi_alloc_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1019",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590903456,
      "name": "scsi_alloc_sgtables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
blk_status_t scsi_alloc_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_alloc_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591247616,
      "name": "scsi_alloc_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247616,
      "name": "scsi_alloc_sgtables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 991
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
blk_status_t scsi_alloc_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_alloc_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591594864,
      "name": "scsi_alloc_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1019",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_prepare_cmd",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591594864,
      "name": "scsi_alloc_sgtables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 991
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
blk_status_t scsi_alloc_sgtables(struct scsi_cmnd * cmd)
```
</details>
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
