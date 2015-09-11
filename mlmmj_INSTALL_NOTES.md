# Install

    sudo apt-get install mlmmj

    // create mailing list
    sudo mlmmj-make-ml -c list:list -L duang

    // add list to /etc/aliases (line provided by program)
    sudo vim /etc/aliases  
    //  duang:  "|/usr/bin/mlmmj-receive -L /var/spool/mlmmj/duang/"

    // start the mailing list server 
    sudo /usr/bin/mlmmj-maintd -L /var/spool/mlmmj/duang 
    
    // If you're not starting mlmmj-maintd in daemon mode,
    // don't forget to add this to your crontab:
    // 0 */2 * * * "/usr/bin/mlmmj-maintd -F -L /var/spool/mlmmj/duang/"

    // install node with NVM as current user and  make it global*
    ...

    // run as 'list' user 
    sudo su list -c "node index.js"

 [Install NVM as global](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-with-nvm-node-version-manager-on-a-vps)


