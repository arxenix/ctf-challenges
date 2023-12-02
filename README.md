# ctf-challenges
Various CTF (capture the flag) security challenges that I've created


| Name  | CTF | Category | Description | Year | Writeup |
--------|-----|----------|-------------|------|---------|
| [uploaders-revenge](https://github.com/osirislab/CSAW-CTF-2023-Finals/tree/main/web/uploaders-revenge) | CSAW CTF 2023 Finals | web | Firefox CSP bypass via controlled mimetype | 2023 | TODO) |
| [webhooktester](https://github.com/osirislab/CSAW-CTF-2023-Finals/tree/main/web/webhooktester) | CSAW CTF 2023 Finals | web | SSRF filter bypassing + Caddy SSRF -> RCE | 2023 | TODO) |
| [rainbow-notes](https://github.com/osirislab/CSAW-CTF-2023-Quals/tree/main/web/rainbow-notes) | CSAW CTF 2023 | web | DOM clobbering + STTF XS-leak | 2023 | [Writeup](https://github.com/osirislab/CSAW-CTF-2023-Quals/blob/main/web/rainbow-notes/SOLUTION.md) |
| [pwnykey](https://2023.uiuc.tf/challenges#pwnykey-16) | UIUCTF 2023 | rev | reversing custom obfuscation of DeviceScript bytecode | 2023 | [Writeup](https://gist.github.com/RubenBrocke/248e80151e2ff4d4ea67a5af792ec4d6) |
| [geminiblog](https://github.com/dicegang/dicectf-2023-challenges/tree/main/misc/geminiblog) | DiceCTF 2023 | misc | bash bugs + SNI injection | 2023 | [Writeup](https://blog.ankursundara.com/dicectf23-writeups/#geminiblog) |
| [impossible-xss](https://github.com/dicegang/dicectf-2023-challenges/tree/main/web/impossible-xss) | DiceCTF 2023 | web | XXE in Chrome XSLT | 2023 | [Writeup](https://blog.ankursundara.com/dicectf23-writeups/#impossible-xss) |
| [jnotes](https://github.com/dicegang/dicectf-2023-challenges/tree/main/web/jnotes) | DiceCTF 2023 | web | cookie smuggling / Jetty 0day | 2023 | [Writeup](https://r0h1t.me/blog/posts/jnotes/), [Writeup](https://blog.ankursundara.com/dicectf23-writeups/#jnotes) |
| [spoink](https://github.com/sigpwny/UIUCTF-2022-Public/tree/main/web/spoink) | UIUCTF 2022 | web | Pebble Spring SSTI 0day | 2022 | [Writeup (CN)](https://blog.maple3142.net/2022/08/01/uiuctf-2022-writeups/), [Writeup (JP)](https://blog.arkark.dev/2022/08/01/uiuctf/) |
| [woeby](https://github.com/sigpwny/UIUCTF-2022-Public/tree/main/web/woeby) | UIUCTF 2022 | web | CSRF+SQLi in OSS search engine | 2022 | [Writeup (CN)](https://blog.maple3142.net/2022/08/01/uiuctf-2022-writeups/) |
| [precisionism](https://github.com/sigpwny/UIUCTF-2022-Public/tree/main/web/precisionism) | UIUCTF 2022 | web | harder prefix injection to bypass CORB | 2022 | [Writeup](https://hackmd.io/@parrot409/ry2mk-0A9) |
| [modernism](https://github.com/sigpwny/UIUCTF-2022-Public/tree/main/web/modernism) | UIUCTF 2022 | web | prefix injection to bypass CORB | 2022 | [Writeup (CN)](https://blog.huli.tw/2022/08/01/uiuctf-2022-writeup/) |
| [shadow](https://github.com/dicegang/dicectf-2022-challenges/tree/master/web/shadow) | DiceCTF 2022 | web | exfiltration from shadow DOM | 2022 | [Writeup](https://github.com/Super-Guesser/ctf/blob/master/2022/dicectf/shadow.md) |
| [uploader](https://github.com/arxenix/uploader-chal) | N/A | web | fileupload XSS bypassing CSP and mimetype filter | 2021 | N/A |
| [pwnyIDE](https://github.com/sigpwny/UIUCTF-2021-Public/tree/master/web/pwnyide) | UIUCTF 2021 | web | chrome 0day (header length bypass) + cross protocol scripting + 2 node-ftpd 0days (race condition, multiple command smuggling) | 2021 | [Writeup](https://hackmd.io/@parrot409/HJJU1B_1t) |
| [yana](https://github.com/sigpwny/UIUCTF-2021-Public/tree/master/web/yana) | UIUCTF 2021 | web | cache probing xs-leak + cache partitioning bypass | 2021 | [Writeup](https://fireshellsecurity.team/uiuctf2021-yana/) |
| [essveegee](https://github.com/sigpwny/UIUCTF-2021-Public/tree/master/web/essveegee) | UIUCTF 2021 | web | SVG LFI + file:// directory brute forcing without JS | 2021 | [Writeup (JP)](https://nanimokangaeteinai.hateblo.jp/entry/2021/08/02/103244#Web-483-essveegee-4-solves) |
| [phpfuck](https://github.com/sigpwny/UIUCTF-2021-Public/tree/master/jail/phpfuck) | UIUCTF 2021 | jail | PHP RCE in 5 unique chars | 2021 | [Writeup](https://mystiz.hk/posts/2021-08-10-uiuctf-phpfuck/) |
| [deserializeme](https://gist.github.com/arxenix/7e3b0093e1bcc40f633e2b2afa300aab) | UIUCTF 2020 | misc | PyYAML 0day | 2020 | [Writeup](https://hackmd.io/@harrier/uiuctf20) |
| nookcrypt | UIUCTF 2020 | crypto | ECC fault attack | 2020 | [Writeup](https://hackmd.io/@mystiz/uiuctf-2020-nookcrypt) |
| fumblr | EasyCTF IV | web | CSRF + CSP bypass | 2018 | [Writeup](https://ctfshellclub.github.io/2018/02/21/easyctf-fumblr/) |
| [Fanfic Studio](https://github.com/easyctf/easyctf-iv-problems/tree/master/fanfic) | EasyCTF IV | pwn | intro heap exploitation | 2018 | [Writeup](https://ctftime.org/writeup/8827) |
| qset 1,2,3 | ABCTF 2017 | ppc | write code in an esolang i made | 2017 | [Writeup](https://github.com/ctfs/write-ups-2016/tree/master/abctf-2016/ppc/qset1-100) |
| [library](https://github.com/easyctf/easyctf-2017-problems/blob/master/library/description.md) | EasyCTF 2017 | ppc | combinatorics fun | 2017 | [Writeup (CN)](https://hackfun.org/2017/04/09/EasyCTF-2017-Misc-Pro-Write-Up/#Library) |
| [Little Crypto Gambler](https://github.com/ctf-x/ctfx-problems-2016/tree/master/crypto/little_crypto_gambler-150) | ctf(x) | crypto | crack generated LCGs | 2016 | [Writeup](http://opensource-thoughts.blogspot.com/2016/08/ctfx-2016-little-crypto-gambler-crypto.html) |
| [customauth](https://github.com/ctf-x/ctfx-problems-2016/tree/master/crypto/customauth-100) | ctf(x) | crypto/web | ECB ciphertext manipulation | 2016 | [Writeup](https://nandynarwhals.org/ctfx2016-customauth/) |
