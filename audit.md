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
First viable: 6.86s  
DOMContentLoaded: 12.59s   
Load: 22.88s  
Size: 843kb  
!["postimg"](/auditscreens/imgoptim.png "postimg")

## Optimize with Webp
First viable: 6.86s  
DOMContentLoaded: 12.84s  
Load: 20.36s  
Size: 729kb  
!["postwebp"](/auditscreens/webp.png "postwebp")

## Enable GZIP
First viable: 6.00s
DOMContentLoaded: 8.32s
Load: 15.76s
Size: 490kb
!["gzip"](/auditscreens/gzip.png "gzip")

