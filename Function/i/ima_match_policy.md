# Function: <code>ima_match_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ima_match_policy(struct inode * inode, enum ima_hooks func, int mask, int flags)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619184,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:326",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619184,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
int ima_match_policy(struct inode * inode, enum ima_hooks func, int mask, int flags, int * pcr)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582867200,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:336",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867200,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 893
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
int ima_match_policy(struct inode * inode, enum ima_hooks func, int mask, int flags, int * pcr)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582963664,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:336",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963664,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 893
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
int ima_match_policy(struct inode * inode, enum ima_hooks func, int mask, int flags, int * pcr)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583013888,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:365",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583013888,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
int ima_match_policy(struct inode * inode, enum ima_hooks func, int mask, int flags, int * pcr)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583178896,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:365",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583178896,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385472,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:382",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385472,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583504976,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:410",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583504976,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583692448,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:487",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583692448,
      "name": "ima_match_policy",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800432,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800432,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1027
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
int ima_match_policy(struct inode * inode, const struct cred * cred, struct lsmblob * blob, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc, const char * keyring)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194848,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:595",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194848,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int ima_match_policy(struct inode * inode, const struct cred * cred, struct lsmblob * blob, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc, const char * keyring)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313728,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:641",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313728,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int ima_match_policy(struct user_namespace * mnt_userns, struct inode * inode, const struct cred * cred, struct lsmblob * blob, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc, const char * func_data)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348272,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:675",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348272,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int ima_match_policy(struct user_namespace * mnt_userns, struct inode * inode, const struct cred * cred, struct lsmblob * blob, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc, const char * func_data, unsigned int * allowed_algos)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:688",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592309115,
      "name": "ima_match_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071584738784,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
int ima_match_policy(struct user_namespace * mnt_userns, struct inode * inode, const struct cred * cred, struct lsmblob * blob, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc, const char * func_data, unsigned int * allowed_algos)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:722",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594091522,
      "name": "ima_match_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585416976,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int ima_match_policy(struct user_namespace * mnt_userns, struct inode * inode, const struct cred * cred, struct lsmblob * blob, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc, const char * func_data, unsigned int * allowed_algos)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:769",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596102645,
      "name": "ima_match_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586171776,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int ima_match_policy(struct mnt_idmap * idmap, struct inode * inode, const struct cred * cred, struct lsmblob * blob, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc, const char * func_data, unsigned int * allowed_algos)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:771",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596625757,
      "name": "ima_match_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586409392,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int ima_match_policy(struct mnt_idmap * idmap, struct inode * inode, const struct cred * cred, struct lsmblob * blob, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc, const char * func_data, unsigned int * allowed_algos)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:764",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597531371,
      "name": "ima_match_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586674288,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495603752,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495603752,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228964512,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228964512,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1100
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289713328,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289713328,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1844
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274766112,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274766112,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 850
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583769168,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769168,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1027
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583706224,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706224,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1027
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752928,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752928,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1027
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
int ima_match_policy(struct inode * inode, const struct cred * cred, u32 secid, enum ima_hooks func, int mask, int flags, int * pcr, struct ima_template_desc * * template_desc)
```

```json
{
  "name": "ima_match_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583853872,
      "name": "ima_match_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_policy.c:492",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_get_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853872,
      "name": "ima_match_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
<code>int * pcr</code>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * cred</code>
</li>
<li>
<b>Param added. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, func, mask, flags, pcr</code> ➡️ <code>inode, cred, secid, func, mask, flags, pcr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ima_template_desc * * template_desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob * blob</code>
</li>
<li>
<b>Param added. </b>
<code>const char * keyring</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
</li>
</ul>
</details>
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
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param added. </b>
<code>const char * func_data</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * keyring</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, cred, blob, func, mask, flags, pcr, template_desc, keyring</code> ➡️ <code>mnt_userns, inode, cred, blob, func, mask, flags, pcr, template_desc, func_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int * allowed_algos</code>
</li>
</ul>
</details>
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
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
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
