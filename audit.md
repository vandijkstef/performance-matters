# Audit
Here described; the audit for the bootstrap docs optimisation. Every test is done locally, throttled at **3G slow** using **Chrome 64**.

## Init
DOMContentLoaded: 7.53s  
Load: 30.75s  
Size: 1.2 MB  
!["Init"](/auditscreens/init.png "Init")

## Minify CSS/JS
First viable: 6.88s
DOMContentLoaded: 12.62s (saved 0.82s)
Load: 30.11s (saved 0.64s)  
Size: 1.2 MB  
!["postmin"](/auditscreens/post-min.png "postmin")

## Optimize images
First viable:  
DOMContentLoaded:   
Load:  
Size:  
<!-- !["postimg"](/auditscreens/post-img.png "postimg") -->

