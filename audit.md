# Audit
Here described; the audit for the bootstrap docs optimisation. Every test is done locally, throttled at **3G slow** using **Chrome 64**.

## Init
DOMContentLoaded: 7.53s  
Load: 30.75s  
Size: 1.2 MB  
!["Init"](/auditscreens/init.png "Init")

## Post minify CSS/JS
First viable: xxxs  
DOMContentLoaded: 12.62s (saved 0.82s)  
Load: 30.11s (saved 0.64s)  
Size:    
!["postmin"](/auditscreens/post-min.png "postmin")

