# cloudflare-nginx-snippets

Assuming you clone this project in the `/root` directory, you can set up scheduled tasks like this.

```
0 0 * * * /root/cloudflare-nginx-snippets/update-cf-ips.sh 2>&1
0 1 * * * /root/cloudflare-nginx-snippets/update-cf-real-ip.sh 2>&1
```
