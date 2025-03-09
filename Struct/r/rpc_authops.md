# Struct: <code>rpc_authops</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
    int (*)(struct rpc_clnt *) ping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
    int (*)(struct rpc_clnt *) ping;
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
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
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
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct auth_cred *, unsigned int) hash_cred</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct rpc_auth * (*)(struct rpc_auth_create_args *, struct rpc_clnt *) create</code> ➡️ <code>struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create</code>
</li>
</ul>
</details>
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
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    int (*)(rpc_authflavor_t *, int) list_pseudoflavors;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct rpc_authops {
    struct module * owner;
    rpc_authflavor_t au_flavor;
    char * au_name;
    struct rpc_auth * (*)(const struct rpc_auth_create_args *, struct rpc_clnt *) create;
    void (*)(struct rpc_auth *) destroy;
    int (*)(struct auth_cred *, unsigned int) hash_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int) lookup_cred;
    struct rpc_cred * (*)(struct rpc_auth *, struct auth_cred *, int, gfp_t) crcreate;
    rpc_authflavor_t (*)(struct rpcsec_gss_info *) info2flavor;
    int (*)(rpc_authflavor_t, struct rpcsec_gss_info *) flavor2info;
    int (*)(struct rpc_auth *, struct rpc_cred *) key_timeout;
}
```
</details>
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
<b>Field added. </b>
<code>int (*)(struct rpc_clnt *) ping</code>
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
