# Audit
Here described; the audit for the bootstrap docs optimisation. Every test is done locally, throttled at **3G slow** using **Chrome 64**.

## Init
First viable: XXs
DOMContentLoaded: 13.44s   
Load: 30.75s  
!["Init"](/auditscreens/init.png "Init")

## Post minify CSS/JS
First viable: 6.88s
DOMContentLoaded: 12.62s (saved 0.82s)
Load: 30.11s (saved 0.64s)
!["postmin"](/auditscreens/post-min.png "postmin")

