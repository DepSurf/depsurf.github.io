# Struct: <code>nvdimm_security_ops</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    enum nvdimm_security_state (*)(struct nvdimm *, enum nvdimm_passphrase_type) state;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    enum nvdimm_security_state (*)(struct nvdimm *, enum nvdimm_passphrase_type) state;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable_master;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable_master;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable_master;
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
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
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
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct nvdimm_security_ops {
    enum nvdimm_security_state (*)(struct nvdimm *, enum nvdimm_passphrase_type) state;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>enum nvdimm_security_state (*)(struct nvdimm *, enum nvdimm_passphrase_type) state</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable_master</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nvdimm_security_ops {
    long unsigned int (*)(struct nvdimm *, enum nvdimm_passphrase_type) get_flags;
    int (*)(struct nvdimm *) freeze;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) change_key;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) unlock;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) disable;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *, enum nvdimm_passphrase_type) erase;
    int (*)(struct nvdimm *, const struct nvdimm_key_data *) overwrite;
    int (*)(struct nvdimm *) query_overwrite;
}
```
</details>
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
