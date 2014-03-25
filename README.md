Twitter Hosts
=============

Twitter and Tweetdeck hosts file to access from blocked countries.

## Unblock

It's easy to unblock Twitter in your country if it's not blocked from IP.

### Windows

Follow [this link][1] to edit your `hosts` file and paste the contents of [hosts][/hosts] file in this repository.

Open `cmd` and write this:

    ipconfig /flushdns

### Linux

Write the code below in your Terminal:

    sudo sh -c 'curl -kLss http://git.io/_wzNcQ >> /etc/hosts'
    nscd -i hosts
    

### Mac OS X

Write the code below in your Terminal:

    sudo sh -c 'curl -kLss http://git.io/_wzNcQ >> /etc/hosts'
    dscacheutil -flushcache
    
## Clear Chrome DNS Cache

Open Chrome's ["net internals"][2] page: `chrome://net-internals` and select "DNS" from the select box. Press the "Clear host cache" button.

[1]: http://helpdeskgeek.com/windows-7/windows-7-hosts-file/
[2]: chrome://net-internals
