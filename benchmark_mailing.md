# Benchmark

We need

* own the data on our servers (no Mailchimp)
* have a nice web interface to browse archives
* custom subscription messages 


Available softwares :

* **mailman** : python, [ugly web interface](http://quantrimang.com/photos/image/102011/25/Mailman-8.png)
* **[mlmmj](http://mlmmj.org)** : lightweight, looks quite good but no decent web interface, written in C
* **sympa** : well-maintained, good community support . heavy, may be overkill for 200 people 
* **PHP list** : for hipster-based reasons, I'll try to avoid PHP
* **[Majordomo](http://www.sympa.org/documentation/sympa-versus-majordomo-gb.html)** :  a bit outdated but solid, low customization, pure Perl.


Based on quick research, mlmmj looks fine but we need to run a separate web interface.
There is a good start in 

