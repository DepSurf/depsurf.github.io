# Function: <code>tomoyo_assign_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440416,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:504",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440416,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 673
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582662288,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:504",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582662288,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582755344,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:504",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582755344,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847664,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:506",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847664,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004528,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:507",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004528,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205200,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:507",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205200,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322112,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:507",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322112,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583509616,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:520",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583509616,
      "name": "tomoyo_assign_domain",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583615504,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615504,
      "name": "tomoyo_assign_domain",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972608,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972608,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584092464,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:522",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092464,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584119728,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:522",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584119728,
      "name": "tomoyo_assign_domain",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:522",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592304227,
      "name": "tomoyo_assign_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584501168,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:522",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594085438,
      "name": "tomoyo_assign_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585138048,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:522",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596099430,
      "name": "tomoyo_assign_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585862848,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:522",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596622528,
      "name": "tomoyo_assign_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586094800,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:522",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597528837,
      "name": "tomoyo_assign_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586343904,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495398672,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495398672,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228771284,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228771284,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289427712,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289427712,
      "name": "tomoyo_assign_domain",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274598912,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274598912,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583584240,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583584240,
      "name": "tomoyo_assign_domain",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583521296,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583521296,
      "name": "tomoyo_assign_domain",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583568016,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568016,
      "name": "tomoyo_assign_domain",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tomoyo_domain_info * tomoyo_assign_domain(const char * domainname, const bool transit)
```

```json
{
  "name": "tomoyo_assign_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665152,
      "name": "tomoyo_assign_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:524",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665152,
      "name": "tomoyo_assign_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
