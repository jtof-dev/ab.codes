# ab.codes

a repository to host `ab.codes`. currently, it redirects to [my github profile](https://github.com/jtof-dev)

## hosting

- using [github pages](https://pages.github.com), and don't forget to verify the domain in `github settings > pages > verified domains`, and add the domain in the pages section
- after everything was set up, my domain records looked like this:

| type  | domain name                    | content             |
| ----- | ------------------------------ | ------------------- |
| A     | ab.codes                       | 185.199.108.153     |
| A     | ab.codes                       | 185.199.109.153     |
| A     | ab.codes                       | 185.199.110.153     |
| A     | ab.codes                       | 185.199.111.153     |
| AAAA  | ab.codes                       | 2606:50c0:8000::153 |
| AAAA  | ab.codes                       | 2606:50c0:8001::153 |
| AAAA  | ab.codes                       | 2606:50c0:8002::153 |
| AAAA  | ab.codes                       | 2606:50c0:8003::153 |
| TXT   | `challenge subdomain`.ab.codes | `verification code` |
| CNAME | www.ab.codes                   | jtof-dev.github.io  |

- note that there is no `aname` record, as [namecheap](https://namecheap.com) doesn't support `aname` records. however, it appears that github pages functions fine without an `aname`