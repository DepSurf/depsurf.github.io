# Function: <code>scsi_mode_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584804704,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2419",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804704,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 957
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585165824,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2292",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585165824,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 882
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585360064,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2333",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585360064,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585436592,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2415",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436592,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585867216,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2493",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585867216,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586113424,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2509",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586113424,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586259760,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586259760,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 811
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586503840,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2053",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586503840,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651728,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651728,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587455904,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2079",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:get_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587455904,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587524208,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2087",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:get_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524208,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587405888,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:get_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587405888,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977184,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2090",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:get_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977184,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589334224,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2156",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:get_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589334224,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590900016,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2161",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:get_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590900016,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, int subpage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591244016,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2171",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_cdl_enable",
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:get_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591244016,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, int subpage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591591280,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2168",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi.c:scsi_cdl_enable",
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:get_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591591280,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499549688,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499549688,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232013124,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232013124,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292842880,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292842880,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1060
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276749276,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276749276,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586342208,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586342208,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586183536,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586183536,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586599696,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599696,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int scsi_mode_sense(struct scsi_device * sdev, int dbd, int modepage, unsigned char * buffer, int len, int timeout, int retries, struct scsi_mode_data * data, struct scsi_sense_hdr * sshdr)
```

```json
{
  "name": "scsi_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586711968,
      "name": "scsi_mode_sense",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2100",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711968,
      "name": "scsi_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int subpage</code>
</li>
<li>
<b>Param reordered. </b>
<code>sdev, dbd, modepage, buffer, len, timeout, retries, data, sshdr</code> ➡️ <code>sdev, dbd, modepage, subpage, buffer, len, timeout, retries, data, sshdr</code>
</li>
</ul>
</details>
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
