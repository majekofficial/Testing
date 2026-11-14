PHADEMY GO-LIVE GUIDE (domain: phademy.com, bought at Namecheap, site hosted on GitHub Pages)

A. BUY THE DOMAIN (Namecheap)
1. Add phademy.com to your cart. Pick 1 year. Keep "Domain Privacy" ON (it is free). Keep Auto-Renew ON.
2. Say NO to all extras (hosting, email, SSL, security). You do not need them.
3. Turn on two-step login (Account > Security).

B. CONNECT IT TO GITHUB PAGES
1. Upload the files from the WEBSITE zip to your GitHub repository and commit.
2. GitHub: your repository > Settings > Pages > Custom domain. Type: www.phademy.com and Save.
3. Namecheap: Domain List > Manage > Advanced DNS. Delete any parking records, then add:
   - 4 "A Record" rows: Host @ , Value 185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153
   - 1 "CNAME Record": Host www , Value ajekofficial.github.io
4. Wait 10 minutes to a few hours. In GitHub Pages, tick "Enforce HTTPS" when it appears.

C. YOUR EMAIL hello@phademy.com
Namecheap > Domain List > Manage > "Redirect Email" > add alias "hello" forwarding to your Gmail. Send yourself a test.

D. GOOGLE
1. Search Console (search.google.com/search-console) > Add property > Domain > phademy.com. Copy the TXT record into Namecheap Advanced DNS (Host @). Click Verify. Then Sitemaps > submit sitemap.xml
2. Analytics: Admin > Data streams > your stream > change the website address to https://www.phademy.com
3. Bing Webmaster Tools: sign in and import from Google Search Console.

E. SOCIAL
Create @phademy on Instagram, X, TikTok, Facebook and YouTube (even if you post later), to protect the name.
