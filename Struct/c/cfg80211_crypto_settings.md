# Struct: <code>cfg80211_crypto_settings</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    bool control_port_no_preauth;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    bool control_port_no_preauth;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
    enum nl80211_sae_pwe_mechanism sae_pwe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    bool control_port_no_preauth;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
    enum nl80211_sae_pwe_mechanism sae_pwe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    bool control_port_no_preauth;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
    enum nl80211_sae_pwe_mechanism sae_pwe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    bool control_port_no_preauth;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
    enum nl80211_sae_pwe_mechanism sae_pwe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[10] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    bool control_port_no_preauth;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
    enum nl80211_sae_pwe_mechanism sae_pwe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[10] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    bool control_port_no_preauth;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
    enum nl80211_sae_pwe_mechanism sae_pwe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[10] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    bool control_port_no_preauth;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
    enum nl80211_sae_pwe_mechanism sae_pwe;
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
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
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
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cfg80211_crypto_settings {
    u32 wpa_versions;
    u32 cipher_group;
    int n_ciphers_pairwise;
    u32[5] ciphers_pairwise;
    int n_akm_suites;
    u32[2] akm_suites;
    bool control_port;
    __be16 control_port_ethertype;
    bool control_port_no_encrypt;
    bool control_port_over_nl80211;
    struct key_params * wep_keys;
    int wep_tx_key;
    const u8 * psk;
    const u8 * sae_pwd;
    u8 sae_pwd_len;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct key_params * wep_keys</code>
</li>
<li>
<b>Field added. </b>
<code>int wep_tx_key</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const u8 * psk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool control_port_over_nl80211</code>
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
<b>Field added. </b>
<code>const u8 * sae_pwd</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sae_pwd_len</code>
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
<b>Field added. </b>
<code>bool control_port_no_preauth</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum nl80211_sae_pwe_mechanism sae_pwe</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u32[2] akm_suites</code> ➡️ <code>u32[10] akm_suites</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct key_params * wep_keys</code>
</li>
<li>
<b>Field removed. </b>
<code>int wep_tx_key</code>
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
