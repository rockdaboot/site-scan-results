[![HTTPS page scan 2017-03-09](https://rockdaboot.github.io/site-scan-results/https-page-scan-20170309.svg)](https://rockdaboot.github.io/site-scan-results/https-page-scan-20170309.svg)


This scan contacted the Alexa top 1m sites via HTTPS, followed all redirections until hitting the landing page.

Some sites redirect HTTPS to an HTTP endpoint or with insecure redirections inbetween.
To get an impression of how many sites stay secure, once contacted, the above image shows two plots.

HTTPS secure landing
--------------------

Number of sites without redirection or with just HTTPS redirections, resulting in 200 OK.

HTTPS secure index
------------------     

Number of sites that have 0 insecure HTTP links to the same site (origin) in their landing page.
External links, secure or insecure, are disregarded.
