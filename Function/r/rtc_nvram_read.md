# Function: <code>rtc_nvram_read</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586296848,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:26",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586296848,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586760368,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:26",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760368,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587032320,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:24",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032320,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192368,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:25",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192368,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457792,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587458192,
      "name": "rtc_nvram_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587660912,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587661312,
      "name": "rtc_nvram_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588528224,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071588528627,
      "name": "rtc_nvram_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500814280,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500814280,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233320872,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233320872,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294272704,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294272704,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277632734,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277632734,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344672,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587345072,
      "name": "rtc_nvram_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112976,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587113376,
      "name": "rtc_nvram_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587612160,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587612560,
      "name": "rtc_nvram_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_read",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:22",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723392,
      "name": "rtc_nvram_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587723792,
      "name": "rtc_nvram_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t rtc_nvram_read(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
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
