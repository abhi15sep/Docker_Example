Docker Important Links:
======================

1. #Important Links:
https://landscape.cncf.io/

2. #Install bash completion: https://docs.docker.com/docker-for-mac/#install-shell-completion
First install brew: https://brew.sh/

Run: brew install bash-completion

Then paste these lines in terminal:
etc=/Applications/Docker.app/Contents/Resources/etc
ln -s $etc/docker.bash-completion $(brew --prefix)/etc/bash_completion.d/docker
ln -s $etc/docker-machine.bash-completion $(brew --prefix)/etc/bash_completion.d/docker-machine
ln -s $etc/docker-compose.bash-completion $(brew --prefix)/etc/bash_completion.d/docker-compose

Add the following to your ~/.bash_profile:
[ -f /usr/local/etc/bash_completion ] && . /usr/local/etc/bash_completion

#3. Docker desktop for mac
https://hub.docker.com/editions/community/docker-ce-desktop-mac

#4. Github desktop Mac:
https://desktop.github.com/

#5. ITerm2 terminal Mac:
https://www.iterm2.com/

#6. VsCode for development:
https://code.visualstudio.com/

#7. Clone code:
https://github.com/BretFisher/udemy-docker-mastery

#8. Docker for mac troubleshoot:
https://docs.docker.com/docker-for-mac/troubleshoot/

#9. Package Management Basics: apt, yum, dnf, pkg
https://www.digitalocean.com/community/tutorials/package-management-basics-apt-yum-dnf-pkg

#10. How DNS Works
https://dyn.com/blog/dns-why-its-important-how-it-works/
https://howdns.works/

#11. Docker image Specification.
https://github.com/moby/moby/blob/master/image/spec/v1.md

#12. List of official docker images:
https://github.com/docker-library/official-images/tree/master/library

#13. About storage drivers.
https://docs.docker.com/storage/storagedriver/

#14. Dockerfile command reference:
https://docs.docker.com/engine/reference/builder/

#15 Docker Prune commands
- "docker image prune" to clean up just "dangling" images
- "docker system prune" will clean up everything
- The big one is usually "docker image prune -a" which will remove all images you're not using. Use "docker system df" to see space usage.

#16 An introduction to immutable infrastructure
https://www.oreilly.com/ideas/an-introduction-to-immutable-infrastructure

#17. The twelve factor app
https://12factor.net/

#18. 12 Fractured Apps
https://medium.com/@kelseyhightower/12-fractured-apps-1080c73d481c#.cjvkgw4b3

#19. Manage data in Docker
https://docs.docker.com/storage/

#20. Jekyll site generator
https://jekyllrb.com/

#21. Yaml starter
https://yaml.org/start.html

#22. Yaml reference
https://yaml.org/refcard.html

#23. Compose file versions and upgrading
https://docs.docker.com/compose/compose-file/compose-versioning/

#24. Docker composes releases
https://github.com/docker/compose/releases

#25. Production Servers: Compose vs. Swarm
https://github.com/BretFisher/ama/issues/8

#26. Don't use links.
https://docs.docker.com/compose/compose-file/#links

#27. (Docker Docs) Compose file build options
https://docs.docker.com/compose/compose-file/#build

#28. Docker 1.12 Swarm Mode Deep Dive Part 1: Topology
https://www.youtube.com/watch?v=dooPhkXT9yI
Docker 1.12 Swarm Mode Deep Dive Part 2: Orchestration
https://www.youtube.com/watch?v=_F6PSP-qhdA
Heart of the SwarmKit: Topology Management
https://speakerdeck.com/aluzzardi/heart-of-the-swarmkit-topology-management
Heart of the SwarmKit: Store, Topology & Object Model
https://www.youtube.com/watch?v=EmePhjGnCXY
Raft Consensus Visualization (Our Swarm DB and how it stays in sync across nodes)
http://thesecretlivesofdata.com/raft/

#29. Deploy services to a swarm
https://docs.docker.com/engine/swarm/services/

#30. How to Add SSH Keys to Droplets
https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/

#31. Docker Swarm Firewall Ports
https://www.bretfisher.com/docker-swarm-firewall-ports/

#32. How To Configure Custom Connection Options for your SSH Client
https://www.digitalocean.com/community/tutorials/how-to-configure-custom-connection-options-for-your-ssh-client

#33. Microsoft Hyper-V
https://docs.docker.com/machine/drivers/hyper-v/


