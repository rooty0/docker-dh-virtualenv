# docker-dh-virtualenv

    docker run  --rm -v /Users/stan/me/scripts/python_scripts/hwdiff:/build/src -it rooty0/dh-virtualenv
    cd /build/src
    dpkg-buildpackage -us -uc
Final step is to copy created **.deb** package from _docker_:/build to host