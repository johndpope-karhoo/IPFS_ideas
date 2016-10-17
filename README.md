# IPFS ideas

*IPFS all the things!*

- [ ] **download auto-seed** `webtorrent`
  - When downloading with Chrome automatically seed.
  - Seed till seeding factor `2.0` is reached.
- [ ] **apt-ipfs**  
  - `apt-get` wrapper.
  - Seeding by just grabbing and pinning the cache.
  - First check IPFS then/if slow degrade to http.
  - showcase reduced http traffic when using docker containers
- [ ] **inotify-ipfs**  
- [ ] **ipfs-ify**  
  Browser plugin that just adds every ressource into IPFS and tries to speed up receiving them by using IPFS too.
- [ ] **ipfs-cdn**  
  JS lib that does what PeerCDN did using IPFS.
- [ ] **ipfs-twitter**  
  - See http://vole.cc/
  - Browser plugin that extends Twitter.
  - Transparently dual publish.
  - Automatic IPFS-twitter subscription to Twitter-subscribed peers by using their website (the IPFS txt record).
  - Then add surplus like anonymous subscription (when subscribed only via IPFS-twitter just add those tweets from there to the twitter site).
- [ ] **ipfs-file-buoy**  
  https://github.com/pguth/IPFS_file_buoy
